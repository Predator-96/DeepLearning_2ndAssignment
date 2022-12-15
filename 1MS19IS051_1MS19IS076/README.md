# Using Recurrent Neural Networks to Predict stock prices

A dataset containing historical minute data of the stock "State Bank of India" was used to train and test Recurrent neural networks with various time periods as the window.

We also explored LSTM and how it varied with window size.

## Observation
- For Simple RNN, we find that a window size of 70 tends to give better results and 30 tends to overestimate prices.
- For LSTM, we find that window size didn't really play a major role is deviating the results.