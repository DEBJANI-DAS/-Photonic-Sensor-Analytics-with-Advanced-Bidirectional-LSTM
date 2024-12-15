# Photonic-Sensor-Analytics-with-Bidirectional-LSTM
Enhancing the Performance of Photonic Sensors Using Bidirectional LSTM

This project implements a Bidirectional LSTM model to enhance the performance of photonic sensors. The model processes sequential data in groups and evaluates its performance using metrics like MSE, MAE, RMSE, and R².

Dataset
Due to privacy concerns, the dataset used for this project cannot be shared. The dataset contains numerical features, with the target variable in the last column.

Objective
To develop a machine learning model that improves the performance of photonic sensors using Bidirectional RNN (LSTM).

Model Overview
Architecture: The model consists of two Bidirectional LSTM layers, followed by dense layers for regression.
Input: Grouped sequential data for efficient processing.
Output: Predicted target sequences optimized for sensor performance.
Results
Achieved high accuracy with metrics like R² and low errors (MSE, MAE).
Improved sensor performance through better prediction of key metrics.
Usage
Clone the repository and navigate to the project directory.
Ensure all dependencies are installed using pip install -r requirements.txt.
Place your dataset files (train_dataset.csv, test_dataset.csv) in the root directory.
Run the script:
bash
Copy code
python train_and_evaluate.py
Visualizations of performance metrics and predictions will be saved/printed.
