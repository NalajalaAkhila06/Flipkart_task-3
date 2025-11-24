# Flipkart_task-3
# Real-Time Weather Information & Data Logger
# Author : Nalajala Akhila

A Python application that fetches **real-time weather data**, displays it to the user, and securely logs every weather query into a local file.  
The program uses the **OpenWeatherMap API**, demonstrates **API integration**, **error handling**, and **Object-Oriented Programming (OOP)** concepts.

---

##  Task Overview

### **Task Title:**  
Real-Time Weather Information & Data Logger

### **Task Description:**  
The goal of this project is to create a Python program which:

- Fetches live weather data from an open API (OpenWeatherMap)
- Accepts city names from user input
- Displays:
  - Temperature (°C)
  - Feels-like temperature
  - Humidity (%)
  - Weather condition
  - Wind speed (m/s)
- Logs each response with timestamp into a CSV (or SQLite database)
- Implements proper error handling
- Uses OOP concepts (classes & methods)

---

## 🌤️ Features

### ✔ Live Weather Fetching  
Retrieves up‑to‑date weather information for any city.

### ✔ User-Friendly Output  
Displays neatly formatted weather details on the screen.

### ✔ Automatic Logging  
Stores each valid request in **weather_data.csv**, including:
- Timestamp  
- City  
- Country  
- Temperature  
- Humidity  
- Condition  
- Wind Speed  

### ✔ Robust Error Handling  
Handles:
- Invalid cities  
- Wrong API keys  
- Rate limit errors  
- Network issues  
- API server failures  

### ✔ OOP-Based Architecture  
Organized using:
- `Weather` class → fetch & display  
- `logging` class → store data  

---

## 📂 Project Structure

```
weather-app/
│── main.py               # Main program and class definitions
│── weather_data.csv      # Auto-created log file
│── README.md             # Documentation
```

---

## ▶️ How to Run

### 1. Install required library:
```bash
pip install requests
```

### 2. Run the program:
```bash
python main.py
```

### 3. Output
```
<img width="302" height="131" alt="Screenshot 2025-11-24 230539" src="https://github.com/user-attachments/assets/ed8cbc54-fb37-46ea-9ebf-b7a361f6a186" />

## 🧱 OOP Structure
### **Weather Class**
Handles:
- API call  
- Validating response  
- Displaying weather details  

### **logging Class**
Handles:
- Writing data to CSV  
- Adding header on first run  

### **main() Function**
Coordinates input and class interactions.

## 🚀 Future Enhancements

- SQLite database logging  
- Graphical User Interface (GUI)  
- Weather forecast (5-day or hourly)  
- Web application version (Flask/FastAPI)  
- Export logs to Excel/JSON


