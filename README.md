# Blood Glucose Prediction Project
This project aims to predict blood glucose levels for patients with Type I diabetes by exploring and comparing several time-series forecasting methods. Specifically, it uses three approaches: ARIMA models implemented in R, Long Short-Term Memory (LSTM) models in Python, and XGBoost, a popular machine learning algorithm for structured data. The dataset used for this analysis comes from a Kaggle competition focused on blood glucose prediction.

## Project Goals:
The primary objectives of this project are to practice and refine skills in Python and machine learning, focusing on time-series forecasting and deep learning, and to gain insights into the performance of traditional statistical, machine learning, and deep learning models for time-series data.
This project is part of my journey to deepen my expertise in Python and machine learning, specifically in time-series prediction tasks. By implementing multiple model types, I aim to build a stronger understanding of different forecasting techniques.

### Main outcome - Blood Glucose Prediction: 
Assess how each model performs in predicting future blood glucose levels. The goal is to evaluate the practical applications and performance differences between traditional statistical, machine learning, and deep learning approaches for this type of health-related data.

### Model Comparison: 
Implement and evaluate three different time-series models to identify strengths and limitations:
1. ARIMA (AutoRegressive Integrated Moving Average), a classic statistical model for time-series forecasting, using R.
2. LSTM (Long Short-Term Memory), a type of recurrent neural network that is well-suited for sequential data, using Python.
3. XGBoost: A machine learning algorithm known for its high performance with structured data, using Python.

## Project Structure

1. 00_data_preprocess.ipynb: Preprocesses and organizes the dataset.
2. 01_LSTM.ipynb: Implements and evaluates an LSTM model for blood glucose forecasting.
3. 02_XGBoost.ipynb: Uses XGBoost to predict blood glucose levels and compares results to other models.
4. 03_TabNet.ipynb: Demonstrates the best performance among the these models, making it particularly suitable for tabular data.
   TabNet employs an encoder-decoder architecture designed for tabular datasets. The encoder consists of two main components:  
    - **Feature Transformer**: Extracts high-level feature representations.  
    - **Attentive Transformer**: Dynamically selects the most important features for learning through sparse attention mechanisms.  
   This unique architecture not only ensures high performance but also enhances interpretability by identifying key features contributing to predictions.  
6. R_AutoArima.Rmd: Implements an ARIMA model in R for blood glucose prediction.


Through this project, I aim to develop a comprehensive understanding of different modeling techniques and their applications in time-series prediction for healthcare data.
