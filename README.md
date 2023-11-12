# timeSeriesPrediction
Reads financial price data from a CSV file into a Pandas DataFrame.
Splits the data into training and testing sets.
Scales the data using MinMaxScaler.
Uses Keras' TimeseriesGenerator to generate sequences of data for training.
Defines an LSTM (Long Short-Term Memory) model using Keras.
Compiles and trains the LSTM model on the training data.
Plots the loss per epoch during training.
Predicts the next data point using the trained model and compares it to the actual value from the testing set.
