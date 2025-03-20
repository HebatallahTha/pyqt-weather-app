# 🌦️ PyQt Weather App  

This **Python** application is a simple yet visually appealing **weather app** built using **PyQt5**. It allows users to enter a city name and retrieve real-time weather data, including temperature, weather description, and an emoji representation of the current weather conditions.  

## ✨ Features  
- 🌍 **Real-Time Weather Data**: Fetches weather information using the **OpenWeatherMap API**.  
- 🎨 **Modern UI with PyQt5**: Styled with **Times New Roman** and emojis for a sleek look.  
- ⚡ **Error Handling**: Displays meaningful error messages for API failures and connection issues.  
- 📏 **Temperature in Fahrenheit**: Converts from Kelvin to **Fahrenheit** and displays it clearly.  
- ☁️ **Weather Emojis**: Provides an emoji representation based on weather conditions.  

## 🖥️ How to Run  

1. **Clone the repository**:  
    ```bash
    git clone <repository_url>
    ```  

2. **Navigate to the project directory**:  
    ```bash
    cd pyqt-weather-app
    ```  

3. **Create and activate a virtual environment** (optional but recommended):  
    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows
    ```  

4. **Install dependencies**:  
    ```bash
    pip install -r requirements.txt
    ```  

5. **Run the application**:  
    ```bash
    python weather_app.py
    ```  

## 📂 File Structure  

- 📜 `weather_app.py` - The main Python script containing the GUI and weather-fetching logic.  
- 📖 `README.md` - Project documentation.  
- 📄 `requirements.txt` - List of dependencies required to run the app.  

## 🔧 Dependencies  
- **Python 3.x**  
- **PyQt5**  
- **Requests**  

To install them manually:  
```bash
pip install PyQt5 requests
