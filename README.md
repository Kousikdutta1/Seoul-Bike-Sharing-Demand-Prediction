# Seoul Bike Sharing Demand Prediction
# Problem Description
  Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to   the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial     part is the prediction of bike count required at each hour for the stable supply of rental bikes.
  
# Summary :
   * Step 1 : first exercise involved exploratory data analysis where we tried to dig insights from the data in hand. It included univariate and multivariate            analysis in which we identified certain trends, relationships, correlation and found out the features who had some impact on our dependent variable.
  
   * Step 2 : Second step was to clean the data and perform modifications. We checked for missing values and outliers and removed irrelevant features. We also encoded the categorical variables.
   
   * Step 3 : In step 3 we tried various machine learning algorithms on our splitted and standardized data. We tried 5 different algorithms namely; Linear regression, Decision Tree, Randomforest , XGBoost , Gradient Boost. We did hyperparameter tuning and evaluated the performance of each model using various metrics. The best performance was given by the XGBoost model where the R2_score for training and test set was 0.99 and 0.89 respectively.       
   
   * Step 4 : Next, we implemented shap techniques to understand the working of our optimum model. 
   
   * The most important features who had a major impact on the model predictions were : hour, Temperature, Humidity, Rainfall. Demand for bikes got higher when the temperature and hour values were more. 
  
