## conditional probability table 
each row contains the conditional probability of each node value for a conditional 
- each row much be sum 1 
- A ndoe with no parent has only one row , representing the prior probabilieties of each possible value of variable 
this


### inference 



p(x1,x2, .. , xn) =$\prod_{i=1}^{n}$ (xi|parent(xi)

$P(xy) = P(x)P(y)$ 
$P(A) = A \in {{a1,a2,an}}$
$\sum_{i}^{n} P(ai)=1$ 
P(x1,y2,z3)= $P(X = x1 \land Y=y2 \land Z =z3)$ 
P(a ,-b) = P(A = T $\land$ B=F)
P(j , m, a ,-b, -e) = P( j|a ) P(m|a) P(a|-b $\land$ -e) P(-b )P(-e)

P(R|G) = P(R = T | G = T ) =  $P(R,G) /P(G )=\sum_{S} P(R,S,G)/P(R,SG)+P(~R,~S,G)+P(R,~S,G)+P(~R,S,G)$
DỂ TRA CỨU XÁC SUẤT TRONG BN PHẢI MỞ RỘNG ASSGINMENT SAO CHO CÁC BIẾN CỦA ASSIGNMENT ĐỒNG THỜI XUẤT HIỆN TRONG MỘT CBT 

$P(G|R) = P(GR)/P(R)= \sum_{s}P(G,S,R)/P(G)= P(G,S,R)+P(G,~S,R)/P(R)$

### NOTATION 
- X denote the query bariable 
- e denotes the set of evidence variables E1,...,En and e is a  particular observed even
sự kiện mà ta quan sát được P(R|G) đậy e là cỏ ước 
- hidden những biến không xuất hiện tron công thức 
- A typical query asks for the posterior probability $P(X|e)$ 

Inference by emulation 
P(X|e)= $\alpha \sum_{y} P(X,e,y)$
$\alpha$ is the denominator 
P(B|j,m) = $\alpha P(B,j,m) = \sum_{e}\alpha P(B,j,m,e) = \alpha \sum_{e} P(B,j,m,e) = \alpha \sum_{e} \sum_{a} P(B,j,m,e,a)$  






