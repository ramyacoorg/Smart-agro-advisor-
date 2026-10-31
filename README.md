# 🌾 Smart Agro Advisor – AI Agricultural Decision Support

An end-to-end full-stack Machine Learning web application designed to empower farmers with data-driven decision-making tools. Built using **Flask**, **Random Forest**, and **Decision Trees**, the platform provides high-accuracy predictions for optimal crop selection, plant disease diagnosis, and market price forecasting, complete with an accessible voice assistant interface.

---

## 🚀 Key Features

1. **🌱 Crop Recommendation Engine**
   - **Algorithm:** Random Forest Classifier
   - **Inputs:** Soil nutrients (Nitrogen, Phosphorus, Potassium), pH levels, and weather metrics (Temperature, Humidity, Rainfall).
   - **Output:** Recommends the most suitable and profitable crop with high confidence scores.

2. **🔍 Plant Disease Prediction Module**
   - **Algorithm:** Decision Tree Classifier
   - **Inputs:** Natural language descriptions of observed symptoms or leaf conditions.
   - **Output:** Identifies potential plant diseases and provides actionable medical/chemical remedies.

3. **📈 Market Price Forecasting**
   - **Algorithm:** Regression Models
   - **Inputs:** Crop type and target time frame.
   - **Output:** Forecasts expected market prices and pricing trends to help farmers optimize their sales timing.

4. **🎤 Voice Assistance Accessibility**
   - Built-in **Web Speech API** integration enabling hands-free voice input and Text-to-Speech (TTS) output, making the tool accessible for non-technical users in rural regions.

---

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Machine Learning:** Scikit-Learn, Pandas, NumPy, Joblib (Random Forest & Decision Trees)
* **Frontend:** HTML5, CSS3, JavaScript (Web Speech API)

---

## 📂 Project Directory Structure

```text
smart-agro-advisor/
│
├── app.py                   # Flask backend server & API endpoints
├── requirements.txt         # Python package dependencies
├── README.md                # Project documentation
├── models/                  # Serialized machine learning models (.pkl)
├── static/
│   ├── css/
│   │   └── style.css        # Responsive agricultural theme styling
│   └── js/
│       └── voice.js         # Web Speech API voice assistant logic
└── templates/
    ├── index.html           # Main dashboard home page
    ├── crop_rec.html        # Crop recommendation interface
    ├── disease_pred.html    # Plant disease detection interface
    └── price_forecast.html  # Market price forecasting interface
