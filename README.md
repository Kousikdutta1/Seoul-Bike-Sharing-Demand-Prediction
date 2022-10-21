# Seoul Bike Sharing Demand Prediction
# Problem Description
  Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to   the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
  
# Summary :
   * Step 1: The first exercise involved exploratory data analysis where we tried to dig for insights from the data in hand. It included univariate and multivariate analysis in which we identified certain trends, relationships, and correlations and found out the features that had some impact on our dependent variable.
  
   * Step 2: The second step was to clean the data and perform modifications. We checked for missing values and outliers and removed irrelevant features. We also encoded the categorical variables.

   
   * Step 3: In step 3 we tried various machine learning algorithms on our split and standardized data. We tried 5 different algorithms namely; Linear regression, Decision Tree, Random Forest, XGBoost, and Gradient boosting. We did hyperparameter tuning and evaluated the performance of each model using various metrics. The best performance was given by the XGBoost model where the R2_score for training and test set was 0.99 and 0.89 respectively.

   
   * Step 4: Next, we implemented SHAP techniques to understand the working of our optimum model.

   
   * The most important features which had a major impact on the model predictions were : Hour, Temperature, Humidity, Rainfall. 

# Result :
![jhedb](https://user-images.githubusercontent.com/106880838/189750939-c9783f13-3ba8-4777-8b48-9557e57ab6ff.PNG)

# Conclusion :

As we can interpret from above, XG Boost has the lowest RMSE, MSE, MAE among all and with a R2 score of 0.89 on test data which is
highest among all, so we can consider XG Boost model as the best model.
Though, final selection of model totally depends on business point  of view, if it is absolutely necessary to have 
a model with the best accuracy, then XG boost will be the best choice. We also know that higher the complexity the
lower is the model explainability. if the predictions must be explained to stakeholers, then XG Boost is not an
ideal choice. Hence In this case decision tree can be used, since they are easier to explain. By choosing a simpler model we will be compromising 
with the models accuracy.


  
