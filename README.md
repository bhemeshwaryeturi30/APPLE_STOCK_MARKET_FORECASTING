# APPLE_STOCK_MARKET_FORECASTING

The Stock Market Prediction and Forecasting project using Stacked LSTM neural networks in Python leverages deep learning techniques to forecast the future stock prices of Apple Inc. The project involves data collection from the Tiingo API, preprocessing of the collected data, and building a Stacked Long Short-Term Memory (LSTM) model using Keras and TensorFlow.

The process starts with collecting historical stock data for Apple using the Tiingo API and storing it in a CSV file. Then, the data is preprocessed, including scaling using MinMaxScaler, splitting into training and testing sets, and reshaping for input into the LSTM model.

The Stacked LSTM model architecture consists of three LSTM layers followed by a Dense layer for prediction. The model is compiled using the mean squared error loss function and the Adam optimizer.

Training the model involves fitting it to the training data and validating it using the testing data. The training process involves iterating over epochs, with each epoch updating the model's weights to minimize the loss.

Finally, the trained model can be used for making predictions on unseen data to forecast future stock prices.

<img src="https://github.com/bhemeshwaryeturi30/APPLE_STOCK_MARKET_FORECASTING/blob/main/Visualisation-3.png" width="70%" height="70%">



This project demonstrates the application of deep learning techniques, particularly LSTM neural networks, for stock market prediction and forecasting, providing insights into potential future trends in stock prices for Apple Inc.

Link to dataset using API: https://www.tiingo.com/documentation/general/overview
