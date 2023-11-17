# Stock price prediction using LSTM
This project uses Long Short-Term Memory (LSTM) neural networks to predict stock prices based on historical data. The LSTM model is trained on a sequence of stock prices and aims to forecast future prices.

Overview:

This Python script utilizes an LSTM neural network to predict stock prices using historical data from the "netflix.csv" file. The dataset is preprocessed and split into sequences of a defined length (seq_len). The LSTM model is then trained on a portion of this data to learn the patterns in stock prices.

Requirements:

Python 3.x

Libraries: numpy, pandas, scikit-learn, torch, matplotlib

Code Explanation:-

Data Preparation:

Loads historical stock data and scales the closing prices using MinMaxScaler. Prepares sequences (X) and corresponding target values (y) based on a sequence length (seq_len).

LSTM Model:

Defines an LSTM neural network using PyTorch, consisting of an LSTM layer and a fully connected (linear) output layer.

Training the Model:

Trains the LSTM model using a defined number of epochs and optimizes it using the Adam optimizer.

Predictions and Visualization:

Evaluates the trained model on test data and generates predictions for future stock prices. Inversely transforms the predicted and actual values for visualization.

Usage:-

Data Setup:

Ensure your historical data file is named "netflix.csv" or update the script to reflect your file's name and format.

Run the Script:

Execute the provided script in a Python environment with the required dependencies installed.

Results:

The script generates predictions for future stock prices using the trained LSTM model and visualizes the predicted and actual prices in a plot.

Contributing:

Contributions are welcome! Feel free to improve the code, add features, or optimize the model for better predictions. Open issues or submit pull requests to collaborate.
