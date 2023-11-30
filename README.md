# Abstract

The time-series forecasting field is crucial and encourages ongoing research into areas of interest for various applications. Choosing the appropriate number of historical observations is an important step in time-series forecasting (lags). This project investigates forecasting accuracy based on the selection of an appropriate time-lag value between Regression method and LSTM (Long-Short Term Memory) in stock price prediction.The performance metrics were: Root Mean Square Error (RMSE), and R-squared. The investigation demonstrated that the both proposed algorithms were able to provide high accuracy with least RMSE and R-squared for respective time gaps and forecasting period.

#Introduction

Time series forecasting is a technique for the prediction of events through a sequence of time. The technique is used across many fields of study, from geology to behavior to economics. The techniques predict future events by analyzing the trends of the past, on the assumption that future trends will hold similar to historical trends. Long Short-Term Memory(LSTM) and ARIMA are two widely used models for time series forecasting.

Forecasting the average surface temperature of Kathmandu valley means that we will be known with the temperature of the next day, or even later than that before the day even begins, obviously, in variance with accuracy. Forecasting the average surface temperature using machine learning algorithms helps you to predict/discover the future temperature based on the past data that has been trained in it.

ARIMA model is one of the approaches to time series forecasting. ARIMA is a statistical analysis model that uses time series data to either better understand the data set or to predict future trends. It is an autoregressive model as it is a statistical model that predicts the future value based on the past data that has been provided to it. ARIMA models aim to describe the autocorrelations in the data.

Long Short-Term Memory (LSTM) networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems. This is a behavior required in complex problem domains like machine translation, speech recognition and more.

# System Design

This design is logically divided into three parts. The first block represents phase 1, the second block represents phase 2, and the third & fourth block represents phase 3. 
The first phase’s is a basic phase as it consists all the data collection and preprocessing parts
Phase 2 is the phase where all the models are made and  forecast the temperature using the X test dataset, which was created by dividing our identical data into test and training sets. 
Phase 3 involves all the testing and report writing part.

# Result and Output

We adopted two of the most commonly applied models in time series prediction to establish and compare forecasting models for monthly, weekly and daily incidence of average surface temperature of Kathmandu valley . The results demonstrated that both ARIMA and LSTM could be used to build prediction models for the average surface temperature  while different models might be suitable for average surface temperature prediction at different time scales.

To compare how good the model is doing, we have taken mse/rmse (root mean square error) and r2 square as our metrics. Even though based on a rule of thumb, it can be said that RMSE values between 0.2 and 0.5 shows that the model can relatively predict the data accurately. In addition, Adjusted R-squared more than 0.75 is a very good value for showing the accuracy. In some cases, Adjusted R-squared of 0.4 or more is acceptable as well. But we can take here lowest RMSE and r2 square more than 0.75 as a good model while comparing.

We concluded that ARIMA model produced lower error values than LSTM model in monthly and weekly series which indicated that ARIMA was more successful than LSTM for monthly and weekly forecasting. While the error values produced by LSTM were lower than those by ARIMA for daily forecasting in a rolling forecasting model. Both ARIMA and LSTM predicted the seasonal fluctuation well, particularly in rolling forecasting models.

# Conclusion
Both ARIMA and LSTM could be adapted to build prediction models for the  average surface temperature .The best fitting model of ARIMA and LSTM were adopted to forecast the temperature ,direct forecasting method was used while prediction .Predicted values were compared with the actual values to test the prediction effect of the models. RMSE was applied to evaluate the prediction performance of the models and lower value means better performance.. ARIMA model produced lower error values than LSTM model in monthly and weekly series which indicated that ARIMA was more successful than LSTM for monthly and weekly forecasting. While the error values produced by LSTM were lower than those by ARIMA for daily forecasting in a direct forecasting model.  
