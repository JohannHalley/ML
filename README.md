# ML

## simple LD
### one line for one class
$c_1$ and not $c_1$

### none linear( gradient descent
$c_1$ and not $c_1$  

Squared Error  
* closed-from-solution
* penality on too correct
* sensitive to outlier

### regression( 
posterior probability  
hier line for $C_1$ or $C_2$  

Cross-Entropy Error
* posterior probability
* minimun exists
* iterative estimation
* rough linear


## SVM  

通过找到最小的 $（\frac{1}{w}）^2$，相当于寻找${x}^2$  
此时support vectors are _points on marigin_.


slack variable, Xi  
此时support vectors are _points with $\xi > 0$_.  
$xi \in [0,1]$ means correct but in margin range.  
$xi \in [1,\inf]$ means in wrong side.  

non seperable Data  
C: trade off parameter  
（它能修正到更好的结果？）

Hinge Error
* 0 Error on too correct( outside margin     : sparsity
* linear penality for missclassification     : robostness
* not differentiable, hard to have optimal solution

## AdaBoost


exponient Error
* fast convergence
* less robust to cross-entorypy( regression) ( looks like)
* no penality on too correct but too wrong

## NN
perceptron learning

gradient descent( bp


## CNN for graphic



## RNN for language
