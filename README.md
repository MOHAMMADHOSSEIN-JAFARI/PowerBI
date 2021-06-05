# Statistical-Learning
# 26-April
if the absolute value of the t-value is greater than the critical value, you reject the null hypothesis. If the absolute value of the t-value is less than the critical value, you fail to reject the null hypothesis.
Read the article about the critical value:
https://stattrek.com/statistics/dictionary.aspx?definition=critical%20value
significance level:
The significance level, also denoted as alpha or α, is the probability of rejecting the null hypothesis when it is true. 
study this matter!!!!!!!!!!
https://blog.minitab.com/en/adventures-in-statistics-2/understanding-hypothesis-tests-significance-levels-alpha-and-p-values-in-statistics
bivariate 
numbering cathergorial values 
what is ANOVA
f test all means are equal 
full.model <- lm(log(rent_pr) ~., data = dd)
summary(full.model)  the dot is important hear 
part 7 spoke about dummy vairables 
vif for  collinearity 

# 3-May
Alpha, confidence level, critical value 
If the P-value is less than alpha (or equal to) , then the null hypothesis is rejected in favor of the alternative hypothesis. And, if the P-value is greater than alpha , then the null hypothesis is not rejected.
# 4-May 
cross validation adn the cross validation 
the trade of between bias and vairance 
select the type of validation 
min square for 
exist other method of error 
classifation 
likelihood 
## 18-May 

regularization 
test set is different form the validation set 
training set and vailsarion set 
trian a linear model, 
how you devide the data set!!!!!!
car data quadratic model with respect to 
min square model, 
degree of the polynomial 
each time, I produce the spiliting between 
the estimation of mean square error 
 SLIDE 7
 negative points: reduce the trainnng set 
 k-fold cross validation
 extreme 
 for each observation 
 min square voccl 
 computational problem 
 each time only one is excluded. 
 extreme correlation 
 increase the vairalblility of total 
 the vairabilkity of 
 stronly co
 k-fold 
 single only training between two extrimes 
 for each k i select 
 it is not a resampling and each group has 
 the sample is 
 the bias of the 
 final cross validation 
 LOOCV 
 N different erro and i get the mean. 
 k-fold 
 
 only in linear 
 possibility, cross validation:
 calculate, 
 define the leverage: h was based on comn=nimations of x, the value of h in chap 3 can be min 1/n and max can be 1. leverage is equal to 0 and max is 1. the contribution each. 
 residuals
 if h is zero, it is quaite equal to residuals. the unit ahs hartgr 
 in cahpter 3: 
 14 Means flexibility is k fold 
the truth: the cross validation 
infact the best model is 5\
Cross validation 
needing to tale into account 
two amin goals on cross: measutre the standard error 
select the best model 
in the minimum, 
include all the vairables 
in the case of one jsut square error, but with K YOU CAN have jsut the varianlilituy 
knowig the unceritinity 
error if I have only one 
If I do not know 
I need to verify 
confidence interval test 
calculus of the standard error 
abd points:
do the model for select the variables that are relevant
if in the training
k-fold 
change also the results that are significant in your model 
in order to k-fold we need to follow all the steps 
you need to apply the cross validation 
degree of the polynomials 
which kind of variable I can choose.
No or yes: when you select, the k fold, 
the case of classification, in step one and two 
use the same variable in each one not, apply in the same 
the min square error 
produce, book chapter 
employed data set, 
boot strap exam, 
lecture 7, code for boos strap and cross validation 
boot strap:
test and confidence or other but we do not anbo any thing ab9tuy the distribution, waht happens not normal and small 
boot strap: two method parametric and not-parametric 
moncarlo 
simulation, generate on the same distribution, parametric boot strap
having the observed sample 
calculate thepsitive standard error of the 
value that minimize 
the property of the variance and do the derivative 
----use sample, 
different replications of the 
boot strap: you can not you ahve
boot strap, statistical appraoch 
apply, I do not have i.i.d dsitribution, rock curve, 
the problem is that: boot strap 
you can  not use 
do during the boot-strap 
at the end:
in the more complex 
boot strap is complicated 
time-series data
boot-strap: confidence interval. 

bootstrap: interval 
paired sample and independent sample 
lab3 : the formula of confidence interval 
LL lower limit 
UL upper limit 
I do not have a new uonit but 
fitst ,manually and an the same time we have acesst to the library "booststrap" 
# 5-May
reading the slides of bootstrap and cross validation. it definitely needs reviewing 
# 6-May
when the coefficient is near to zweor u
reduce the variance of 
PLS this reduction consider the directon of y and x not like PCA which is just for x 
degree of freedom is the # of parameters 
forward- you can not delete the variable you have chosen before 
always the test erroir is largertr than training error 
 th unique way does not exist. more than criteria aic bic and r2 
 ? speak which is better
 not necessary:
 shrinkage: ridge and lasso,  intermediate like elastic net, application
 perersent: focus on ridge regression 
 Ridge and regression slides jsut for studies 
 use some kind fo constraints 
 ridge regression on original value 
 L2 norm for ridge coeeficient and l2 norm of ols 
 the bias variance tradeoff 
 really useful 
 
# 11-May 
when wwe have many p, infact we can increase the R2 in trainng data but in the large p, ridge and lasso 
ridge regression coefficient, they are not invariant with scale. 
standardized, 
standardized false
look the previous example, 
the LASSO
instead of L2 NORM we use l2 norm. 
lasso and ridge: gurantee the level of the 
the difference. int he calse of the ridge
the lasso some b is equal to 0. 
ols solution jsut 4
s in number 36 is cost 
38 quite identically result for bothe apppproach 
jsut some variables , best predictors , 
additive model, ridge regression, avoid their fitting
do prediction: apply ridge 
 when p is large variables are really corrolated
there is a theory for which I know there is a relation between 
only to variables ae corolateed 

#### i you are able to, bivariate, when you want to decide which model is better for robustness check, the more importatn think is the variablity. You know how noisy your variable is. uncertainity is always 
you can check for single individual 
the most importatn part of a data scientist is the data manipulation
Cross-VALIDATION 
-Use the split to choose the better, consider all the data
- I do not need regression, high dimentionality problem
- decide: a part to be more in 
- approach a problem in a data scientist way.
- adv and disadvan of 
- less models and well commented of a topic.
- details of ridge and lasso 
- why lasso is better in the casesof less variables 
- Elastic net 
- - the approach the ridge use 
- - we will represent: at the end 
only a small number of 
- principal component regression 
- the relation between principal component and dimention reduction
- principal component 
- chanmimatrics, we have always situation p than n can not ols,
- ols new dimention x matrix by a of vairables really corrolated vaorianles, I can not appraoch 
- a lot information that describe the same things. there is not an observed to describle to 
- typically questioners, test food understaned if the probability not chemical, there is no major that, the relation of single attribute but about some dimention
- the dimention of increase 
- - I have a lot of moninfested variables
- factor analysis: unsuperwised approach 
- two different method: 
- major Vieef collinearity 
- m has to be less than p 
- first includes the largest 
- pca method gurantee according to the 
- the second one jsut can explian the residual part!!!!!!!!!
- what is bias, whst is bias-variance and etc...
- best that explain x 
- -reduction is not really corolated to 
- - reduction is not really 
- -- i do the regression model 
- phy1j is the weight 
- in the lab section I will discuss. 
- PAartial least , the reserach 
## 18-may 
pros and cons- very is to interpret, everybody can understand the resuot 
Typically representation is easy. Combining a large number of trees, if we want one tree .
Compare the regression with others- svm is not covered here.

the mnean of the responsible variable in thsi gorup 
Anova: between variance, grid search
- test other vairables spilit that produce means that are statistically different. There are some 
- in general we can have some 
- variable does not discriminate 
- sometimes trees: 
- knn: we need a more depth model 
- -risk of overfitting 
- rank of featrues 
- what are the optiimal number of each group 
- non linear relationship, it is not easy, intutive way to  describle non-linearities
- interperation of results
- mean of the response variable 
- differe variabliity
- classification: the same prediction 
- see exactly the value, in two regions
- vairance is begier than the mean, the predicion is not reliable 
- tOP Down greedy approach: testing 
- chapter review of the decision tree. there is no other method, not binary 
- greeds can nbe changeed 
- the largest distance.
- test all the vairables. min of the trianing 
- strongly non linear 
- if the tree has many nodes you cna face over fitting. the approach prune a tree. instead of considering
- which final node we decide. According to the data. Basically we can not test. one part is the minimuzation, lest number of final node, select different level on alpha. 
-Train ever each result. Return to choose thev alue of alpha. 
rate the performance model, in orther to calculate 
having ghe idea of the variablility 
heterogiity for analyzing the cathegorical Gini 
variablility 
cathegories- Gini Variables- study the distribution how many poor person can be based 
heteroginity based on 
maximum concentration 33 region, Gini Index: the value of the 
in teh decision tree, we want to spilit that maximize the difference the 
the antropy 
gini index all the close 
reduce the impurity 
- chid is not binary spilit, k-squre is Maximum when the conditional 
- Maximize the k-sqaure: spilit for each distribution 
- library, not jsut yes or now, and the percentage, 
- the same value, and really important, when you are asked 
- the largertst test error 
- the algorithm choose, teh accuracy of the test increase. 
- if the variable is ordered. Two cathegories. Check the two cathegories 
- trees better than linear. the trees can 
- linear and tree depends on. 
- the accuracy.
- trees problem is variability. th bagging use boostrap,get the meaning 
- generate, the things that happen all the samples can be related. pagging automatically. when I boostrap b times form the same set of data, in each bootstrapping sample, terminology, out of bag, hat is associated to prediction, each b traing set, be different estimation. At the end, we need to have.
- 150 is enough. 
- Random fOREST: OOB: what is the main.
- if the variable is corrolateed the 
- the simple mean is 
- add the covariance. original variable, we suppose, random forest as bagging, when the number of predictos inside each m
- when m is equal to 
- the idea 
- m is the square root of p. At the end, when the varuable has differen variable with the 
- random forest a lot of computations. nice representation of tree but the bad point is that. That 
- boosting does 
- not use bootstrap. a procedure learn slowly, learn step by step. nested approach
- boosting in rally situations it is the best, 
# 31-May
You have to do analysis with different options in 
are realy in different options the clusters are neutral or not. If I am able to reduce the dimentionality. PCA can be used to clustring.
How many clustting ways///; advanced multivariate clsutiring. Other k-means'; we wantt to calculate the variriablitityance. Spilit the total va. Compare the minimum of clsuters: 
Post Analysis, you have to explore. Manoies distance. In GENERAL, the problem is done, Eif you planc=uclidian distance is by defult. if you plan to use eclidian measute, it is better to standardized the matter. if K increase the distance increase. 
channel  is an outlier. Gower is for mixed data type. 
# 5-June
https://support.minitab.com/en-us/minitab/18/help-and-how-to/modeling-statistics/multivariate/how-to/principal-components/interpret-the-results/key-results/
this explains about the interpret principal component analysis. 
