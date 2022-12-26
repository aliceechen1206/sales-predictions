# Sales Prediction

***Author***: Alice Chen

**Business problem:**

Understanding the properties of products and outlets that play crucial roles in predicting sales. Based on features of the items sold we will try maximizing the sales of products and determine Items that need sale boost for future sales.

# Methods
- Building a linear regression model
- Building regression tree model
- Using Histogram, Barplot, Boxplot, and Seaborn for exploration of relationshipp between groups.

# Results

**Heat Map for Numerical Features**

![heatmap](https://user-images.githubusercontent.com/110635256/209582318-f86550b2-ea2f-4c5e-9173-9014984fddf7.png)

> The best correlation with the target is with MRP.


**Distribution of Item Type Sales**

![Distribution of Item type Sales](https://user-images.githubusercontent.com/110635256/209582353-2357cf01-f3e3-4990-8168-3640487ff8d8.png)

> The Distribution of the highest median items are Household, Snack Food, Starchy Food, and Seafood. 


**Distribution of Item Outlet Sales**
![Distribution of Item MRP](https://user-images.githubusercontent.com/110635256/209582798-e93a3a8e-4143-4e53-8f21-2310410d7790.png)

> Graph shows that the average MRP is 140.99 and median MRP 143.01.

**Showing metrics for testing data**

| Model | RMSE | R2 |
| ----- | ---- | -- |
| Linear Regression | 138913693735.8824 | 3.3670670528059e-06 |
| Decision Tree | 3027332338176.8823 | -3.32178924642665e+18 |

# Recommendations
With a negative R2 score, you can safely assume that the model is a very poor fit to the data and a super large RMSE will only confirm that. So based on the metrics results I wouldn't suggest a Decision Tree model to this data.

# For further information
For any additional questions, please contact aliceechen1206@gmail.com
