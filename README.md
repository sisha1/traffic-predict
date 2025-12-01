Traffic Flow Prediction using LSTM

This Google Colab notebook demonstrates a simple traffic flow prediction model using a Long Short-Term Memory (LSTM) neural network. The goal is to predict future vehicular traffic based on a synthetic time-series dataset.

Project Overview
The notebook walks through the following steps:

Synthetic Data Generation: Creates a simulated traffic flow dataset with a sinusoidal pattern and added noise to represent realistic traffic variations.
Data Preparation for LSTM: Transforms the time-series data into sequences suitable for LSTM input, where a window of past observations is used to predict the next value.
LSTM Model Building: Constructs a basic LSTM model using TensorFlow/Keras, consisting of an LSTM layer followed by a Dense output layer.
Model Training: Trains the LSTM model on the prepared synthetic data.
Prediction: Uses the trained model to predict traffic counts for the next 10 minutes, using a rolling prediction approach.
Visualization: Plots the original synthetic traffic data alongside the model's predictions for the future, providing a clear visual representation of the forecast.
Dependencies
This notebook requires the following libraries:

numpy
matplotlib
tensorflow
keras
These are typically pre-installed in Google Colab environments.

How to Run
Open the notebook in Google Colab.
Run all cells sequentially from top to bottom.
Observe the generated synthetic data plot, model summary, training output, and the final prediction plot.
Output
The final output includes:

A plot of the synthetic vehicle count data.
A summary of the LSTM model architecture.
Training loss values for each epoch.
A list of predicted vehicle counts for the next 10 minutes.
A visualization showing the original traffic data extended with the 10-minute prediction, allowing for easy comparison and understanding of the model's forecast.

