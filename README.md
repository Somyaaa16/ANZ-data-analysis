# ANZ-data-analysis
There were 2 tasks in this virtual internship:
1) Exploratory data analysis
2)Predictive analytics

1) Exploration Outcomes:

There are 23 column in the dataset and 12043 observations/rows of data.​
From summary we can see that columns ‘card_present_flag’, ‘bpay_biller_code’, ’merchent_code’ have 92% and 36% of missing values, so we’ll discard these columns.​

In august total no. of transaction are: 3943​
In September total no. of transaction are: 4013​
In October total no. of transaction are: 4087

Avg no. Of transaction in 3 months are: 4014

Avg no. of transaction in august is : 127
Avg no. of transaction in september : 134
Avg no. of transaction in october : 132

Maximum spending is done in the 'pay/salary' part
Next big spending is done in the payment part followed by Inter-bank transactions
Minimum spending is done in POS sector.

The most amount of transactions are made in state NSW
Then in SA and VIC
And lowest amount of transaction is made in Tasmania

2) Prediction Outcomes:

Correlation between salary and age: -0.1385938
There is negative correlation, meaning older people have comparatively lower salary than young generation
Correlation between salary and gender: It seems men have higher salary range than women.
By conducting welch  t-test we see that men have greater salary than female as we fail to reject our null hypothesis
that male have higher salary than females as the p-value is more than the significance value.

Regression Model: I build the linear model for predicting salary based on 2 factors: age and gender.
The r squared value is 5.3% means 5.3% of variance in salary the predicted variable is been explained by the 2 factors (age and gender) 
Th residual is quite high: 13440 and the root mean squared value is 675.79

DECISION TREE:
The Root mean squared value is quite high in the decision tree than the model I built.
Here the RMSE value is 102202.18

The accuracy of the linear model I built is very low as we can see from the rmse value as compared to decision tree.
Hence, ANZ should use the decision tree model rather than my model for segmenting the customers into income brackets for reporting purposes.
More accurate accuracy may be achieved by proper pruning and considering more variables for predicting the salary.
