
# ⛅ YB Weather App

A simple desktop GUI weather application built with Python and Tkinter, allowing users to check real-time weather information of Indian states using OpenWeatherMap API.

---

## 🚀 Features

- 🌦️ Displays current weather (climate, description, temperature, and pressure)
- 🌐 Select any Indian state from dropdown
- 🎨 Clean and colorful GUI using Tkinter
- ⚡ Uses OpenWeatherMap for live weather data

---

## 🖼️ Screenshot Placeholder

> *(Add screenshots in a `screenshots/` folder and link here)*

---

## 🛠️ Built With

- **Python**
- **Tkinter**
- **OpenWeatherMap API**

---

## 🔑 API Setup

This app uses the OpenWeatherMap API. To run it:
1. Sign up at [https://openweathermap.org/api](https://openweathermap.org/api)
2. Get your API key
3. Replace the API key inside the script:
   ```python
   data = requests.get("https://api.openweathermap.org/data/2.5/weather?q=" + city + "&appid=YOUR_API_KEY").json()
   ```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```

2. Run the app:
   ```bash
   python demo_temp.py
   ```

---

## 🌐 Live Demo

> This is a desktop app, so no online demo is available.

---

## 🙋‍♂️ Author

**YB (Your Name)**  
[LinkedIn](https://www.linkedin.com/in/your-username/) • [GitHub](https://github.com/your-username)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
