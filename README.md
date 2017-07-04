                                          SUMMARY   REPORT
Introduction:
The data set we have used in this analysis contains data of 6 different airlines and we had to create a regression model to classify the reasons for the difference in economy prices and premium prices of tickets in a flight.
I created a regression model in which i took the dependent variable as PRICE_RELATIVE and checked for various dependent variables by checking their correlation values and plotted boxplots for visualization by converting them into factor variables.
The goodness of the fit was checked by the R-squared value, Residual error sum and AIC value using the lm() for the first two and generalized linear model command for the third one.
Ggvis command really proved beneficial in doing multi-variate analysis.

INFERENCES:
1.	Huge difference in RELATIVE_PRICE for domestic and international flights.
2.	As quality increased, the RELATIVE_PRICE also increased montonically.
3.	With Width_premium increase, the relative prices increased.
4.	Delta airlines had the lowest relative price while jet had the most prominent difference.
5.	Positive correlation is observed between quality and pitch and width premium, width premium and international and pitch-premium and international.
6.	R-squared value of 0.79 is observed.
7.	The predicted value through this model for PRICE_RELATIVE was 1.51 whereas the actual was 1.64.
8.	AIC value for the model was -123.11 . 
9.	Residual standard error for the model was 0.2073.
T-test
#As the p-value of the model is 2.2e-16 which is much lower than the significant levels of 0.05, so we can safely reject the null hypothesis that the value for the co-efficient is zero.(or in other words that the predictor variable has no explanatory relationship with the response variable.)
10.	The F-statistics of the model is 103.7 which is considerably high.                                   


