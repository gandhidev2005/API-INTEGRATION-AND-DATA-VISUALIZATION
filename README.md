# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Dev Nilesh Gandhi

*INTERN ID*: CT04DM1209

*DOMAIN*: Python Programming

*DURATION*: 4 weeks

*MENTOR*: Neela Santhosh Kumar

# 🌦️ Weather Forecast Visualization using OpenWeatherMap API
This project is a Python-based weather forecasting tool that fetches 5-day weather data from the [OpenWeatherMap API](https://openweathermap.org/forecast5) and visualizes key parameters such as **temperature** and **humidity** trends over time using `matplotlib` and `seaborn`.

## 📌 Features
* Connects to the OpenWeatherMap API to fetch real-time weather forecast data.
* Parses and visualizes **temperature** and **humidity** data for the next five days at 3-hour intervals.
* Uses **matplotlib** and **seaborn** to create easy-to-understand line plots.
* Simple and modular code, easy to customize for different cities or weather parameters.

## 🛠️ Technologies Used
* **Python 3**
* **Requests** – For making HTTP API calls.
* **Matplotlib** – For plotting line charts.
* **Seaborn** – For enhanced data visualization aesthetics.
* **Datetime** – For converting timestamps into human-readable format.

## 🚀 Getting Started
### Prerequisites
Make sure the following Python libraries are installed:

```bash
pip install requests matplotlib seaborn
```
## 🔐 API Key
This script uses the **OpenWeatherMap API**, which requires a free API key.

1. Sign up at [https://openweathermap.org/](https://openweathermap.org/)
2. Get your API key from the dashboard.
3. Replace the placeholder API key in the script:

```python
API_KEY = "your_actual_api_key_here"
```

> ⚠️ Do **not** expose your API key publicly. Consider using environment variables for production use.

## 📊 Sample Output

* **Temperature Plot**: Shows how the temperature fluctuates throughout the next 6 days in the specified city.
  ![Image](https://github.com/user-attachments/assets/0f2647ec-8a22-48e5-85f5-5cb9db1dfbc9)
* **Humidity Plot**: Gives a view of how the humidity level changes, useful for health and travel planning.
  ![Image](https://github.com/user-attachments/assets/428699d3-0b54-4f97-96e5-db67d9797755)

## 🧩 Possible Improvements
* Add more weather parameters (pressure, wind speed, etc.)
* Save plots to image files
* Export data to CSV
* Build a GUI using Tkinter or a web app using Flask/Streamlit
* Deploy using Docker
