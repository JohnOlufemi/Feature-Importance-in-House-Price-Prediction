# House-Price-Prediction

## Background and Feature Importance 
Features, otherwise known as variables, are properties of a data set and are used as inputs for machine learning models. Although they are typically numeric, they can also be strings. Selecting relevant and reliable features is essential for algorithms, making features one of the most important components in machine learning modelling 

The quality of features directly impacts model predictions, further emphasizing the importance of feature selection in machine learning. By measuring feature importance, we can determine which features contribute most to a model's predictions. Feature importance techniques assign a score to each input feature based on its usefulness in predicting a target variable, indicating the degree of usefulness for a current model and prediction.

## Data Set
The dataset included both numeric and binary variables. The number of rooms, kitchens, and French doors were all numerical features. Binary features, represented by 0 for "no" and 1 for "yes," included whether the house has a backyard, is furnished, is painted green, has a wood floor, has security, and has club access. 

## RF, XGBoost, MAE
To predict and extract the necessary information and insights from a dataset, various machine learning algorithms can be utilized. In this case, the dataset was subjected to two major algorithmic tests, employing Python to execute Random Forest (RF), and Extreme Gradient Boosting (XGBoost). The primary objective was to identify the algorithm that provides the more accurate prediction of house prices. The comparison was based on the Mean Absolute Error (MAE), with the general understanding that a low MAE indicates a better prediction while a larger MAE implies otherwise.

![image](https://github.com/JohnOlufemi/House-Price-Prediction/assets/104203741/949dd90a-d3eb-4291-adc7-9a036a141593)

Information provided in Figures 1 and 2 reveals the values between the truth and predicted regression values of the two selected algorithms. The figures show that the values are closer in XGBoost than RF. Likewise, the MAE score of 171 for RF, and 60 for XGB indicates that the magnitude of difference between the prediction and the true value of the observation is lower in XGBoost than RF. Given this, XGBoost is considered more suitable in this context for predicting house prices given the data set. Furthermore, the value of the R-squared of 0.999 and 0.9984 for XGB and RF respectively also lends credence to this. While they are both “good” R-squared values, it however indicates that 99.9% and 99.8% of the variance of the dependent variable (house prices) is explained by the variance of the independent variable (features). 

## Ranking Feature Importance 

A summary of feature importance and ranking for the two algorithms are presented 
![image](https://github.com/JohnOlufemi/House-Price-Prediction/assets/104203741/0a0efb1b-e867-4200-ac71-2009b942a3c5)
