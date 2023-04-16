bases on this video : [Decision Tree Classification Clearly Explained! - YouTube](https://www.youtube.com/watch?v=ZVR2Way4nwQ)
#sumarize 
**Decision Trees (DTs)** are a non-parametric supervised learning method used for [classification](https://scikit-learn.org/stable/modules/tree.html#tree-classification) and [regression](https://scikit-learn.org/stable/modules/tree.html#tree-regression). The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.
too make it more simple to understand decision tree are like a game of 20 question , when some one e

![[khởi nghiệp.PNG]]
the decsion tree is a tree that can sort out node that are diffrent form each other
- the sort in the decision tree should take out all node that are of diffrent color 
- it should slipt the data into optimal root 
-> the machine need to learn which slipt to choose 
![[de.PNG]]
- the tree should choose the second spilt because it have the purest data slipt that being all red as apose to the first spilt which is a combination of both green and red 
### information gain 

- to know the purity of the data set we will used entropy it is gain of information in a state $entropy=\sum_{}^{}-pi log(pi)$ 
![[log.PNG]]
the highest entopy being one and the lowest being 0
$-0.5log(0.5)-0.5log(0.5) =1$ 
with the 0.5 being the percentage that the red and green dot take up in the decision making 
then we will apply the information gain 
$IG =  E(parent) - \sum_{}^{}E(child)$ 
![[INFORMATION GAIN.PNG]]
WE CAN SEE that IG 2 give the most information gain compare with IG 1 

