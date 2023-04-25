# Tetuan City Power Consumption Time Series Analysis

This project is a multivariate time series analysis of power consumption in Tetuan City built using LSTM. It aims to forecast power consumption in the city based on various environmental factors such as temperature, humidity, wind speed, and others.

# Dataset
The dataset used for this project is the Tetuan City Power Consumption [dataset](https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city) taken from the UCI Machine Learing Repository.

# Model
  * Pre-Processed Data: Performed Label Encoding, Normalization and other nesseasry pre-processing steps.
  * Visualization: A multivariate time series plot was created to visualize the relationship between the different variables and power consumption.
  * TIme Series Model: A Long Short-Term Memory (LSTM) neural network was used to forecast power consumption based on the environmental factors.
                       The LSTM network had two layers with 50 units each, and a dense layer with one unit.
  * Evaluation: The performance of the model was evaluated using Root Mean Squared Error (RMSE) and R-squared (R2) score. 
                An RMSE of 2.18 was achieved, which indicates that the model has an average error of 2.18 units in predicting power consumption. 
                The R2 score was 0.94, which indicates that the model explains 94% of the variance in the data.
  * Libraries Used: Pandas, Numpy, Matplotlib, Scikit-learn, and TensorFlow

# Plots
  * Relation
  <img src="https://github.com/11acm11/NeuralNetwork/blob/main/Multivariate%20Time%20Series%20Forecasting%20With%20LSTM/images/relation.jpg"/>
  
  * Predictions
  <img src="https://github.com/11acm11/NeuralNetwork/blob/main/Multivariate%20Time%20Series%20Forecasting%20With%20LSTM/images/predictions.jpg"/>
  
