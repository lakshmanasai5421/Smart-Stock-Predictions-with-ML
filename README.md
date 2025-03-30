# Stock Market Prediction Using Data-Driven Ensemble ML Methods

## Overview
This project utilizes **ensemble machine learning techniques** to predict stock market trends based on historical data. The model combines multiple ML algorithms to improve accuracy and robustness in forecasting stock prices. The web-based interface displays predictions and insights, making it user-friendly for traders and investors.

## Features
- **Data Preprocessing**: Cleans and transforms stock market data.
- **Feature Engineering**: Computes technical indicators (SMA, EMA, Bollinger Bands, RSI, etc.).
- **Machine Learning Models**: Uses ARIMA, LSTM, and RMSE-based Linear Regression models for accurate predictions.
- **Model Evaluation**: Uses MAE, RMSE, and R-squared scores for performance measurement.
- **Interactive Web Interface**: Visualizes stock trends and predictions.
- **Automated Model Training**: Periodic updates with the latest market data.

## Technologies Used
- **Programming Languages**: Python, JavaScript, HTML, CSS
- **Machine Learning Libraries**: TensorFlow/Keras (for LSTM), Scikit-Learn, Pandas, NumPy, Statsmodels (for ARIMA)
- **Web Technologies**: Flask (for backend), Bootstrap (for UI)

## Algorithms Used
This project applies a combination of **time-series forecasting** and **deep learning techniques** to predict stock prices. The following models are used:

✅ **ARIMA (AutoRegressive Integrated Moving Average)**: A statistical model for analyzing and forecasting time series data.  
✅ **LSTM (Long Short-Term Memory)**: A deep learning model specifically designed for time-series prediction.  
✅ **RMSE-based Linear Regression**: A linear regression model optimized using RMSE to reduce error and improve accuracy.  

## Workflow of the Project
### 1️⃣ Data Collection & Preprocessing
- Historical stock data is collected (CSV format or through APIs).
- Data preprocessing steps include:
  - Handling missing values
  - Feature scaling & normalization
  - Creating new features (like moving averages, RSI, etc.)
  - Splitting data into training and testing sets

### 2️⃣ Feature Engineering
- Computes technical indicators like SMA, EMA, Bollinger Bands.
- Applies time-series transformations, such as lag features.
- Sentiment analysis (if included) processes news data.

### 3️⃣ Model Training
The dataset is split into training and testing sets, and models are trained using historical stock data. The ensemble approach helps improve prediction accuracy and reduces overfitting.

### 4️⃣ Model Evaluation
The trained models are evaluated using metrics like:
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R-squared (R²) score**

### 5️⃣ Prediction & Visualization
- The trained model predicts stock trends.
- Forecasted values are visualized using graphs and tables.
- The web interface (Flask + HTML/CSS) displays predictions.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- pip (Python package manager)
- Virtual environment (optional but recommended)

### Steps
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the application:
   ```bash
   python main.py
   ```
3. Open the web interface:
   ```
   http://127.0.0.1:5000
   ```

## Usage
1. **Upload Stock Data**: Provide a CSV file with historical stock prices.
2. **Train the Model**: The system preprocesses data and applies ML models (ARIMA, LSTM, RMSE Linear Regression).
3. **View Predictions**: Predictions are displayed on an interactive dashboard.
4. **Analyze Trends**: Use visualizations to make informed decisions.

## File Structure
- **main.py**: Core ML model implementation and API.
- **index.html**: Web UI for user interaction.
- **results.html**: Displays predicted stock trends.
- **static/**: Contains CSS and JavaScript files.
- **templates/**: Stores HTML templates.

## Future Enhancements
- Implement Transformer-based deep learning models for improved accuracy.
- Integrate real-time stock data APIs for live predictions.
- Improve UI with interactive charts and better data visualization.

---
**Author:**K.Lakshmana sai 
**GitHub:** https://github.com/lakshmanasai5421
**Contact:** lakshmanasai.karumuri2k22@gmail.com

