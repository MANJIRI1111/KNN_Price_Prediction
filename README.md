# KNN_Price_Prediction

Summary:

Use Case for predicting property prices based on various features. Initially, the dataset was cleaned, and properties were categorized into price levels. A KNN classifier was built to classify properties into these price levels using geographic coordinates. Additionally, Multivariate Logistic and KNN regression models were developed to predict the sold price directly, with features like square footage, lot acres, and no. of bedrooms. Performance metrics, including R-squared and MAE, were used to assess accuracy. Residuals and prediction scatter plots provided insights into model reliability. This analysis compared both approaches, showing how spatial data and traditional features can enhance property price prediction.

Key Points:

1.	Data Preparation:
a.	Cleaned the dataset, calculated price per square foot, and categorized it into 20 quantiles for a discrete price category variable.
2.	KNN Classification:
a.	Implemented a KNN classifier to categorize properties based on their price category using latitude and longitude as features.
b.	Calculated accuracy and visualized the classification results with a scatter plot showing actual vs. predicted categories.
3.	Feature Engineering for Regression:
a.	Created a 'rooms' feature by combining bedrooms and bathrooms for use in the regression model.
b.	Prepared features for regression, including KNN price category, square footage, lot acres, fireplaces, garage, and rooms.
4.	Multivariate Linear Regression:
a.	Developed a linear regression model using gradient descent to predict sold price.
b.	Evaluated the model’s performance with R-squared and Mean Absolute Error (MAE) metrics, and plotted actual vs. predicted sold prices and residuals.

5.	KNN Regression:
a.	Implemented a KNN regressor with weighted averaging of neighbouring values for predicting sold price.
b.	Visualized the KNN regression predictions vs. actual sold prices and examined the residuals for evaluation.
6.	Performance Comparison:
a.	Compared the R-squared and MAE results for both linear regression and KNN regression models.
7.	Results Visualization:
a.	Displayed key visualizations, including scatter plots and residual plots for both models, providing insights into the accuracy and reliability of predictions.
