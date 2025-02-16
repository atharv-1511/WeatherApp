🌦️ Weather App  

📌 Description  
The **Weather App** is a Python-based GUI application built using **Tkinter** that fetches real-time weather data from the **OpenWeatherMap API**. Users can enter a city name to get **temperature, humidity, wind speed, pressure, sunrise, and sunset times** in an intuitive interface.  

---

## 🚀 Features  
✅ **Real-time Weather Data** - Fetches live weather conditions using OpenWeatherMap API.  
✅ **Temperature Conversion** - Displays temperature in **Celsius**.  
✅ **Sunrise & Sunset Times** - Shows human-readable sunrise & sunset times.  
✅ **Simple GUI** - Built using **Tkinter** for easy interaction.  
✅ **Keyboard Support** - Press **Enter** to get weather details.  

---

## 🛠️ Technologies Used  
- **Python** - Core programming language.  
- **Tkinter** - For building the graphical user interface.  
- **Requests** - To fetch weather data from OpenWeatherMap API.  
- **Time Module** - To format sunrise and sunset timings.  

---

## 📌 How to Run  
### **Step 1: Install Required Libraries**  
Ensure you have Python installed. Then, install dependencies:  
``bash
pip install requests
``
## Step 2: Run the Application
Execute the Python script: python weather_app.py

📜 API Key Configuration
This app uses OpenWeatherMap API. Get your API key from OpenWeatherMap and replace it in the code:
``api = "https://api.openweathermap.org/data/2.5/weather?q="+city+"&appid=YOUR_API_KEY"``

📂 Directory Structure
``weather-app/
│-- weather_app.py  
│-- README.md  
│-- requirements.txt`` 

⚠️ Limitations
Requires an active internet connection to fetch data.
API requests are limited based on OpenWeatherMap’s free-tier restrictions.

📌 Author
Developed by Atharv Raskar
