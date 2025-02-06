# Outlier Prediction Using LSTM and Time-Series Data

## Overview
This project demonstrates the use of deep learning (LSTMs) for predicting outliers in data based on simulated sensor time-series data. The model is trained to detect patterns in movement and identify potential outlier cases using simulated sensor data.

## Features
- **Synthetic Data Generation**: Simulates time-series data mimicking sensor readings.
- **LSTM-Based Model**: Uses a recurrent neural network for sequence-based predictions.
- **Hyperparameter Optimization**: Utilizes Optuna for tuning model parameters.
- **Model Training & Evaluation**: Computes metrics like ROC-AUC, Precision, Recall, and F1-score.
- **Anomaly Detection Visualization**: Displays outlier threshold against sensor data.
- **SHAP Explainability**: Provides insights into feature importance.

## Model Architecture
- **LSTM layers** for sequence modeling
- **Fully connected layer** for final classification
- **Binary Cross-Entropy Loss** for training optimization

## Results
- The model predicts outlier conditions based on time-series data with measurable accuracy.
- Evaluation metrics (ROC-AUC, F1-score) provide performance insights.
- SHAP visualizations explain model predictions.

## Contributing
Feel free to submit issues or pull requests to improve this project.

## License
This project is open-source under the MIT License.
