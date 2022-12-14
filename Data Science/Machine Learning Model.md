## Regression

Regression is a statistical method that attempts to determine the strength and character of the relationship between one dependent variable and a series of other variables. 

###  Simple Linear Regression
$\color {teal} y=ax+b$
parameter: intercept, slope
$x$ is called feature
$y$ is called label
$MSE(Mean\ Squared\ Error) =\frac{\sum(y_i-\hat{y})^2}{n}$
$RMSE=\sqrt{MSE}$
P value
### Multivariable Regression
$y=a_1x+a_2x+a_3x+...a_nx+b$
$SSE(sum\ of\ square\ of\ error)=\sum(y_i-\hat{y})^2$
$SST(total\ sum\ of\ squares)=\sum(y_i-\bar{y})^2$
$R^2= 1-\frac{SSE}{SST}$

### Polynomial Regression
### Logistic Regression


## Classification

$Confusion\ Martix$
|                 | Actual True         | Actual False        |     
| --------------- | ------------------- | ------------------- |
| Predicted Ture  | True Positive (TP)  | False Positive (FP) |    
| Predicted False | True Negative (TN)  ) | False Negative (FN)|   

$Accuracy = \frac{TP+TN}{ALL}$
$Percision= \frac{TP}{TP+FP}$
$Recall = \frac{TP}{TP+FN}$
$F1 Score = \frac{2*Accuary*Percisoin}{Accuary+Percisoin}$
$AUC$

 
## Clustering
