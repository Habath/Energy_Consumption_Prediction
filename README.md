# Appliance Energy Consumption Prediction
 ### Project Overview :
   - This project aims to predict the energy consumption of appliances present in a house based on indoor factors like temperature, humidity and pressure.
 ### Dataset:
   - The data set used is a opensource data which has readings recorded every 10 min for about 4.5 months. The house temperature and humidity conditions were monitored with a ZigBee wireless sensor network. Each wireless node transmitted the temperature and humidity conditions around 3.3 min. Then, the wireless data was averaged for 10 minutes periods.
   -  The energy data was logged every 10 minutes with m-bus energy meters. Weather from the nearest airport weather station (Chievres Airport, Belgium) was downloaded from a public data set from Reliable Prognosis (rp5.ru), and merged together with the experimental data sets using the date and time column.
   -  Two random variables have been included in the data set for testing the regression models and to filter out non predictive attributes (parameters).

 ### Data Preprocessing:
   - Handling missing values
   - Feature scaling
   - Feature Selection

 ### Modeling:
  The following machine learning models were implemented and their performance was analysed:
 
  **Improved Linear regression models**
  
  - Ridge regression
  
  - Lasso regression
  
  **Support Vector Machine**
  
  - Support vector regression
  
  - Random Forest 
  
  - ExtraTreeRegressor

  ### Evaluation:
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
  ### Conclusion:
  - Best results over test set are given by ExtraTree Regressor with R2 score of 0.63
  - Least RMSE score is also by ExtraTree Regressor 0.60
  - Lasso regularization over Linear regression was worst performing model
  
