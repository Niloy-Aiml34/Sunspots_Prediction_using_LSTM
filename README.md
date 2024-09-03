# Sunspot Time Series Forecasting with LSTM

<img src="http://i.imgur.com/NVN9eOK.gif?1" alt="Sunspot Animation" width="500"/>

This project involves the use of Long Short-Term Memory (LSTM) networks for the prediction of sunspots based on historical time series data. The objective is to model the complex patterns within the dataset to make accurate future predictions.

## Project Overview

### 1. Understanding Sunspots
A comprehensive introduction to sunspots, their importance in solar physics, and the relevance of predicting their occurrence.

### 2. Dataset Exploration
An initial exploration of the sunspot dataset, including key statistical analyses and visualizations to understand underlying trends and seasonality.

### 3. Sequence Models for Time Series Data
A detailed introduction to sequence models, with a focus on LSTM networks, and their suitability for time series forecasting tasks.

### 4. Data Preparation
Custom functions and techniques are employed to preprocess the dataset, generate sequences, and prepare the data for model training and evaluation.

### 5. Huber Loss Function
Discussion on the choice of the Huber loss function, balancing the trade-off between mean squared error and mean absolute error, and its implementation in the model.

### 6. Model Development & Learning Rate Optimization
Construction of the LSTM model architecture, followed by a systematic approach to finding the optimal learning rate for model training.

### 7. Model Training
Training the LSTM model using the optimal learning rate and monitoring performance metrics to prevent overfitting and underfitting.

### 8. Results & Predictions
Presentation of the model’s performance on the validation set, including visualizations of the predicted versus actual sunspot counts.

### 9. Future Work
Suggestions for further exploration, including potential improvements in model architecture, alternative sequence models, and hyperparameter tuning.

## Key Results
- **Model Used**: LSTM Network
- **Validation Mean Absolute Error (MAE)**: 13.122861862182617

## Visual Insights
![Sunspot Prediction Results](https://github.com/Niloy-Aiml34/Sunspots_Prediction/blob/main/predictionVSvalidation.png)

*Figure: Predicted versus actual sunspot counts visualized over the test period.*

## Getting Started

### Prerequisites
Ensure that the following dependencies are installed:
- Python 3.x
- TensorFlow
- NumPy
- Pandas
- Matplotlib

### Running the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/Spartificial/yt-acad-projs.git
