# 🌦️ Weatherly – Weather Forecast Application

Weatherly is a simple and modern weather forecasting web application developed using Python Flask and the OpenWeatherMap API. It allows users to search for any city and view its current weather conditions, temperature, and humidity through a clean and responsive interface.

## ✨ Features

- 🌍 Search weather information by city name.
- 🌡️ Display current temperature in Celsius.
- 💧 Show humidity levels.
- ☁️ Display current weather descriptions.
- ⚡ Fetch real-time weather information using OpenWeatherMap API.
- 🎨 Clean and modern user interface.
- 📱 Responsive design for different screen sizes.
- 🔐 Secure API key management using environment variables.

## 🛠️ Technologies Used

- **Python** – Backend programming
- **Flask** – Web framework
- **HTML5** – Page structure
- **CSS3** – Styling and responsive design
- **OpenWeatherMap API** – Real-time weather data

## 📁 Project Structure

```text
Weatherly/
│
├── app.py
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository


git clone https://github.com/nimithajosy11-lang/Weather-App-Prediction.git


### 2. Navigate to the Project Folder

```bash
cd Weatherly
```

### 3. Install Required Libraries

```bash
pip install flask requests
```

### 4. Get an OpenWeatherMap API Key

- Visit [OpenWeatherMap](https://openweathermap.org/api).
- Create an account.
- Generate your API key.

### 5. Set the API Key

For Windows PowerShell:

```powershell
$env:OPENWEATHER_API_KEY="YOUR_ACTUAL_API_KEY"
```

Keep your API key private. Do not upload it to GitHub.

### 6. Run the Application


python app.py

### 7. Open in Browser


http://127.0.0.1:5000


## 🌐 How It Works

1. Enter a city name in the search field.
2. Submit the search request.
3. The Flask backend communicates with the OpenWeatherMap API.
4. The API returns the latest available weather information.
5. Weatherly displays the temperature, humidity, and weather description.

## 🎯 Project Objective

The main objective of this project is to develop a user-friendly weather application that demonstrates API integration, Python Flask development, and frontend design while providing accessible weather information.

## 👩‍💻 Developed By

**Nimitha Josy**

---

⭐ If you find this project useful, consider giving it a star!
