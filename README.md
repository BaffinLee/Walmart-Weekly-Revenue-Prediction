# Walmart-Weekly-Revenue-Prediction

This project is based on the [Walmart Sales](https://www.kaggle.com/datasets/mikhail1681/walmart-sales/data) dataset, from the Kaggle platform.

The primary objective of this project is to develop a predictive model for Walmart's weekly sales using machine learning techniques. This project aims to tackle a regression problem, which involves predicting continuous values—in this case, the weekly sales figures for Walmart stores. By leveraging historical sales data, along with various external factors such as holidays, promotions, and economic indicators, we aim to accurately forecast future sales and provide actionable insights.

Two regression models are used in this project, Linear Regression and Random Forest, to get a better prediction of Walmart's weekly sales data and compare results of different models.

## Code and Report

Please view the code with description in the [Jupyter notebook](https://github.com/BaffinLee/Walmart-Weekly-Revenue-Prediction/blob/main/Walmart%20Weekly%20Revenue%20Prediction.ipynb).

## Discussion and Conclusion

In the model training part, I used linear regression model first, and that didn't went well, why is that? My guess is that the first column of my dataset is the ID of a Walmart store, even that's a number, it's kind of a category value, not linear number value. And linear model is too simple for this problem, so my linear regression model didn't work well.

Then I did some fine tuning about the n_estimators superparameter of the random forest model, I changed it to make sure my model performs well and the time of training process is reasonable.

That's all of it, the Walmart's weekly sales model should predict the future sale well and have great business value about helping store managers to estimate sales data and prepare for the future arrangement.
