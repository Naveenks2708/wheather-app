# 🌤️ WeatherNow – Quick Weather Checker for Jamie

## 🧭 Overview  
**WeatherNow** is a fast, lightweight weather application built for **Jamie**, an *Outdoor Enthusiast* who wants to **quickly check the current weather conditions** for any city around the world.  

The app provides an easy-to-use interface, real-time weather updates, and a clean design optimized for speed and simplicity.

---

## 👤 User Persona
**Name:** Jamie  
**Occupation:** Outdoor Enthusiast  
**Goal:** Quickly check current weather conditions for any city before planning outdoor activities.  
**Needs:**  
- Fast, minimal interface  
- Quick search for any city  
- Essential weather info (temperature, humidity, wind speed, latitude, longitude)

---

## 🎯 Key Features
✅ **City Search:** Instantly fetches live weather data for any city.  
✅ **Personalized Greeting:** Greets Jamie with a warm message.  
✅ **Clean UI:** Focused on simplicity with weather details only.  
✅ **Responsive Layout:** Works on desktop and mobile.  
✅ **Live API Integration:** Powered by [Open-Meteo API](https://open-meteo.com/).

---

## 🏗️ Tech Stack
| Technology | Purpose |
|-------------|----------|
| **React.js (Vite)** | Frontend Framework |
| **JavaScript (ES6)** | Logic and API integration |
| **CSS3** | Styling and layout |
| **Open-Meteo API** | Real-time weather data |

---

## 📁 Project Structure
```
wheather-Project-main/
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
│
└── src/
    ├── App.jsx              # Main React component (greeting + search + display)
    ├── main.jsx             # Entry point for React
    ├── Whetherdetsil.jsx    # Weather details component
    ├── index.css            # Styling for the app
    └── assets/ (optional)   # GIFs & icons
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/weathernow.git
cd wheather-Project-main
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Run the development server
```bash
npm run dev
```

Open the link displayed in your terminal (e.g. `http://localhost:5173/`).

---

## 🌦️ API Reference – Open-Meteo

The app fetches weather data using **Open-Meteo’s free API**:

Example URL:
```
https://api.open-meteo.com/v1/forecast?latitude=19.07&longitude=72.87&current_weather=true
```

Data includes:
- Temperature  
- Wind Speed  
- Humidity  
- Latitude & Longitude

---

## 🖼️ UI Highlights
- Simple search bar for quick city lookup  
- Animated weather GIF/image  
- Data displayed inside small info boxes  
- Greeting message: “Hi Jamie 👋 Check the weather instantly!”

---

## 💡 Future Enhancements
- Auto-detect user’s current location  
- Add 3-day forecast  
- Save favorite cities  
- Support multiple themes (dark/light)

---

## 👨‍💻 Author
**Developed by:** Naveen  
**Inspired by:** Jamie’s need for a fast and clear outdoor weather app  

---

## 📜 License
This project is open-source under the **MIT License** — feel free to use and modify it.
