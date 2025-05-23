# 🌦 Real-Time Weather Forecasting

A hybrid machine learning application that integrates real-time weather data from the OpenWeatherMap API with historical weather datasets to predict rainfall and forecast temperature and humidity trends. The system leverages classification and regression models to provide actionable weather insights.

## 🚀 Features

- 🌐 **Real-time Data**: Fetches current weather metrics from the OpenWeatherMap API.
- 📊 **Historical Dataset**: Uses a cleaned and encoded dataset for model training.
- 🌧 **Rain Prediction**: Employs a Random Forest Classifier to predict if it will rain tomorrow.
- 🌡 **Temperature Forecasting**: Predicts future hourly temperatures using regression.
- 💧 **Humidity Forecasting**: Projects future hourly humidity levels.
- 🧠 **Machine Learning**: Built using Scikit-learn's Random Forest models.
- 🖥 **Command-Line Interface**: Terminal-based weather input, analysis, and output.

## 📁 Project Structure


## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- OpenWeatherMap API
- Random Forest Classifier & Regressor
- Label Encoding
- Pytz for timezone handling

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/real-time-weather-forecasting.git
   cd real-time-weather-forecasting
pip install -r requirements.txt
API_KEY = 'your_api_key_here'
python weather_forecast.py
