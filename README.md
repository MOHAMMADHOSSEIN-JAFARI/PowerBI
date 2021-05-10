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
 
