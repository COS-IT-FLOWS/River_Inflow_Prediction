# River_Inflow_Prediction
Spatio-temporal Attention Long Short Term Memory model for handling river inflow prediction on a river basin level.
River flow Predictions using AI - LSTM

code has the 4 class

data.py: load and split the data into training and testing. It also transform the data

Attention.py In this code attention is not specified. It assign weightage to inputs.

Model base Select models- the models included here are SA-LSTM, TA- LSTM, STA-LSTM, LSTM, FCN. We have selected the STA-LSTM in this code

main.py Specify input and run specifications and call above classes. Run the model and save outputs

plot Plot outputs saved according to the date

**Model Performance ** using Root mean square error and volume biase
