# 🌍 Smart Indoor Air Quality Monitoring using IoT & Machine Learning

![ESP8266](https://img.shields.io/badge/ESP8266-NodeMCU-blue)
![Arduino IDE](https://img.shields.io/badge/Arduino-IDE-00979D)
![Python](https://img.shields.io/badge/Python-3.10-yellow)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![IoT](https://img.shields.io/badge/IoT-Blynk-brightgreen)
![License](https://img.shields.io/badge/License-MIT-success)

> A real-time Indoor Air Quality Monitoring System built using **ESP8266 NodeMCU**, **MQ-135**, **DHT11**, and **LDR** sensors. The system continuously monitors environmental conditions, visualizes live data through **Blynk IoT**, stores sensor readings in **Google Sheets**, and applies **Machine Learning** techniques for air quality prediction.

---

# 🖼️ Project Overview

<p align="center">
  <img src="Images/system_architecture.png" width="900">
</p>

---

# 📖 Project Overview

Indoor air quality has a significant impact on human health, comfort, and productivity. This project provides a complete IoT-based solution for continuously monitoring indoor environmental conditions. Sensor data is transmitted to the cloud in real time, logged automatically, and later analyzed using Machine Learning algorithms to classify air quality.

---

# 🎯 Objectives

- Monitor indoor air quality in real time.
- Measure gas concentration, temperature, humidity, and light intensity.
- Display live sensor data on a Blynk IoT dashboard.
- Automatically log readings to Google Sheets.
- Build a Machine Learning dataset from collected sensor readings.
- Compare multiple Machine Learning models for air quality prediction.

---

# 🚀 Features

- ✅ Real-time Indoor Air Quality Monitoring
- ✅ ESP8266-based IoT System
- ✅ Live Blynk IoT Dashboard
- ✅ Automatic Google Sheets Logging
- ✅ Machine Learning-Based Prediction
- ✅ Temperature & Humidity Monitoring
- ✅ Gas Concentration Detection
- ✅ Light Intensity Monitoring
- ✅ Occupancy Estimation

---

# ⚙️ Hardware Components

| Component | Purpose |
|-----------|----------|
| ESP8266 NodeMCU | Main Controller |
| MQ-135 Gas Sensor | Air Quality Monitoring |
| DHT11 Sensor | Temperature & Humidity |
| LDR Module | Light Detection |
| Breadboard | Circuit Assembly |
| Jumper Wires | Electrical Connections |

---

# 📷 Circuit Diagram

<p align="center">
  <img src="Circuit_Diagram/circuit_diagram.png" width="700">
</p>

---

# 💻 Software & Technologies

- Arduino IDE
- ESP8266
- Python
- Google Colab
- Blynk IoT
- Google Sheets API
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

# 📚 Skills Gained

- Embedded Systems
- ESP8266 Programming
- Arduino Programming
- IoT Development
- Sensor Interfacing
- Cloud Integration
- Data Logging
- Machine Learning
- Python Programming
- Data Analysis

---

# 📂 Repository Structure

```text
Smart-Indoor-Air-Quality-Monitoring
│
├── Code
│   ├── ESP8266
│   └── Machine_Learning
│
├── Circuit_Diagram
├── Dataset
├── Images
├── Presentation
├── Report
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📊 Machine Learning Models

The collected sensor dataset was used to train and evaluate several Machine Learning algorithms.

- Logistic Regression
- Random Forest
- Artificial Neural Network (ANN)
- K-Nearest Neighbors (KNN)

These models were compared to evaluate their effectiveness in predicting indoor air quality from environmental sensor data.

---

# 🔄 System Workflow

```text
        MQ-135
        DHT11
         LDR
          │
          ▼
   ESP8266 NodeMCU
          │
          ▼
      Wi-Fi Network
          │
          ▼
      Blynk IoT App
          │
          ▼
    Google Sheets
          │
          ▼
 Machine Learning Models
          │
          ▼
 Air Quality Prediction
```

---

# 📈 Results

The project successfully demonstrates:

- Real-time environmental monitoring.
- Cloud-based visualization using Blynk IoT.
- Automatic logging of sensor data.
- Dataset generation for Machine Learning.
- Comparative analysis of multiple Machine Learning models.
- Air quality classification based on sensor readings.

---

# 📁 Dataset

The collected dataset contains the following attributes:

- Gas Concentration (MQ-135)
- Temperature
- Humidity
- Light Intensity
- Timestamp
- Occupancy Status

The dataset is available inside the **Dataset** folder.

---

# ▶️ How to Run

## Hardware Setup

1. Connect MQ-135, DHT11, and LDR to ESP8266 NodeMCU.
2. Open the Arduino sketch from the **Code/ESP8266** folder.
3. Configure Wi-Fi credentials and Blynk Authentication Token.
4. Upload the sketch using Arduino IDE.
5. Open the Blynk IoT Dashboard.

## Machine Learning

1. Open the notebook from the **Code/Machine_Learning** folder.
2. Load the dataset.
3. Install required Python libraries.
4. Train the Machine Learning models.
5. Evaluate the models.
6. Generate predictions.

---

# 🔮 Future Improvements

- TinyML Deployment on ESP32
- Mobile Application
- Email & SMS Alerts
- OLED Display
- Cloud Database Integration
- AQI Standard Classification
- Battery Backup
- Voice Assistant Integration

---

# 🙏 Acknowledgements

Special thanks to:

- Jorhat Institute of Science & Technology
- Arduino Community
- Blynk IoT
- Google Colab
- Scikit-learn Developers

---

# 👨‍💻 Author

**Bishnujyoti Gogoi**

B.Tech Electronics & Telecommunication Engineering

Jorhat Institute of Science & Technology

📧 Email: **bishnujyotigogoi01@gmail.com**

🔗 GitHub: https://github.com/bishnujyoti-gogoi

💼 LinkedIn: https://www.linkedin.com/in/bishnujyoti-gogoi-24b908247/

---

# 📜 License

This project is licensed under the **MIT License**.

If you found this project helpful, consider giving it a ⭐ on GitHub.
