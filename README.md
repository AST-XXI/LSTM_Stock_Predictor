# LSTM Stock Predictor

Deep learning recurrent neural networks used  to model bitcoin closing prices. One model will uses the Fear and Greed indicators to predict the closing price. The second model will use a window of closing prices to predict the nth closing price.

1. Prepare the data for training and testing
2. Build and train custom LSTM RNNs
3. Evaluate the performance of each model

Results:
> Which model has a lower loss?
> The model that uses Closing price had a lower loss.
![loss.PNG](Data\Loss.PNG)
> Which model tracks the actual values better over time?
> The model that uses Closing price tracked the actual values over time. 
![BtcPriceprediited.PNG](Data\BtcPriceprediited.PNG)
> Which window size works best for the model?
The window size that works best for this model is 10.
