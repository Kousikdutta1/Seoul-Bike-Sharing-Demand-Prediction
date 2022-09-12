# Seoul Bike Sharing Demand Prediction
# Problem Description
  Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to   the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial     part is the prediction of bike count required at each hour for the stable supply of rental bikes.
# Summary :
 **  The first step in the exercise involved exploratory data analysis where we tried to dig insights from thedata in hand. It included univariate and multivariate            analysis in which we identified certain trends, relationships, correlation and found out the features who had some impact on our dependent variable.
  
   The second step was to clean the data and perform modifications. We checked for missing values and outliers and removed irrelevant features. We also encoded the          categorical variables.
   
   The third step was to try various machine learning algorithms on our splitted and standardized data. We tried 4 different algorithms namely; Linear regression,          Randomforest regressor with GridSearchCV ,XGBoost regressor with GridSearchCV and SVR with GridSearchCV. We did hyperparameter tuning and evaluated the performance      of each model using various metrics. The best performance was given by the XGBoost model where the R2_score for training and test set was 0.84 and 0.77                  respectively.       
   
   Next, we implemented shap techniques to understand the working of our model. The most important features who had a major impact on the model predictions were; hour,      temperature, windspeed, solar-radiation and month. Demand for bikes got higher when the temperature and hour values were more. Demand was high for low values of          windspeed and solar radiation. Demand was high during springs and summer and very low during winters. The model performed good in this case but as the data is time      dependent, values of temperature, windspeed, solar radiation etc. will not always be consistent.
   
   Therefore, there will be scenarios where the model might not perform well. As Machine learning is an exponentially evolving field, we will have to be prepared for all    contingencies and also keep checking our model from time to time.
