# Linear-Regression
<br>
- To perform linear regression on the given data, and train the model for prediction. After training, evaluate the model with MAE, MSE, and RMSE. 
<br> 
- Also to perform homoscedasticity test

<br>
- The data contains scores obtained by 25 students in an exam, along with the number of hours spent studying. 

### Data
https://github.com/sidiquegithub/Linear-Regression/blob/main/DATA/student_scores.csv

### Analysis
https://github.com/sidiquegithub/Linear-Regression/blob/main/CODE/REGRESSION%20MODEL.ipynb

## Scatter Plot 
![download](https://github.com/sidiquegithub/Linear-Regression/assets/110783832/fee20aed-aa3b-4d7e-93d4-ed0cce877135)

## Pearson correlation coefficient

- The correlation coefficient between the number of hours spent studying and the scores obtained is 0.976191 . 
- This indicates a strong linear relationship between the two variables, suggesting that as the number of hours spent studying increases, the scores tend to increase as well.


## Regression Line

![download](https://github.com/sidiquegithub/Linear-Regression/assets/110783832/22c7e401-9645-4280-9319-25384bedd7c2)

## Metrics


Mean Absolute Error is =  4.859304931231131

Mean Squared Error is =  30.159672050910384

Root Mean Squared Error is; RMSE =  5.491782229013673

## Homoscdesticity test

- Homoscedasticity means that the residuals (differences between observed and predicted values) have constant variance across all levels of the predicto

For this we can make use of following
   
   - Graphical Test
   - Statistical Test
     
Graphical Test Result

![download](https://github.com/sidiquegithub/ML-MODEL-LINEAR-REGRESSION/assets/110783832/c6344e12-2f4e-435f-9ae5-d37ffb19fb09)   


Statistical Test Result 

Breusch-Pagan Test: A statistical test for homoscedasticity. It tests the null hypothesis that the variance of the residuals is constant across the range of data.

Since p value = 0.1191 >  0.05 no evidence against the null hypothesis

So we can continue our assumption of homoscedasticity
