# Unit-14---LSTM-Stock-Predictor

![Ai-Stock](Images/AI-Stock.jpg)

## Background
Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the **Crypto Fear and Greed Index (FNG)** which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

In this assignment, you will use deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.

You will need to:

 1. Prepare the data for training and testing
 2. Build and train custom LSTM RNNs
 3. Evaluate the performance of each model


Finally, use the testing data to evaluate each model and compare the performance.
Use the above to answer the following:

* Which model has a lower loss?

* Answer:The model with the lower loss is the closing prices predictor

![loss](Images/lower_loss_CP.png)

* Which model tracks the actual values better over time?

* Answer:The model with better results over time is the closing prices predictor

![model_predicted](Images/actual_vc_predictedCP.png)

* Which window size works best for the model?

* Answer:The window size that works better is 1