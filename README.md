Tesla Stock Price Prediction using LSTM
This project uses a Long Short-Term Memory (LSTM) neural network to predict Tesla's stock prices based on historical data. The LSTM model is designed to capture temporal dependencies in the stock market, providing accurate forecasts of future stock prices.

Overview
Data: Historical stock prices of Tesla, focusing on the 'Close' price.
Preprocessing: Data scaling using MinMaxScaler and sequence creation for LSTM input.
Model: A sequential LSTM model with dropout layers to prevent overfitting.
Training: Model trained on 80% of the data, validated on 20%, using the Adam optimizer and Mean Squared Error (MSE) loss.
Results: Predicted stock prices are visualized against actual prices to evaluate model performance.
How to Run
Clone the repo and install dependencies.
Run the Jupyter Notebook or Python script to train the model and visualize results.
Requirements
Python, Pandas, NumPy, scikit-learn, Keras, TensorFlow, Matplotlib
