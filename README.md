# 🏥 Hospital Resource Optimization & Disease Prediction System 🤖

---

## 🚀 Project Overview

Managing a hospital effectively is a huge challenge, especially when patient inflow fluctuates and diseases vary widely. This project combines **Disease Prediction**, **Patient Inflow Forecasting**, and **Resource Optimization** to help hospitals make **smart, data-driven decisions** for better patient care and resource management.

---

## 🌟 Key Features

### 1️⃣ Disease Prediction  
- 🔍 Predict diseases based on user-reported symptoms using a trained **Decision Tree Classifier**.  
- 🧠 Symptom normalization: Handles variations in symptom names (e.g., “fever”, “high temperature”) for better accuracy.  
- 💬 Interactive user input: Enter symptoms separated by commas and get a predicted disease instantly.

### 2️⃣ Patient Inflow Prediction  
- 📈 Forecast daily or weekly patient arrivals based on historical data and disease trends.  
- 🔮 Predicts how many patients are expected in different severity categories (mild, moderate, severe).

### 3️⃣ Hospital Resource Optimization  
- 🛏️ Uses patient inflow forecasts and predicted disease severity to estimate resource demand.  
- ⚙️ Optimizes allocation of critical hospital resources such as:  
  - ICU Beds 🏥  
  - Oxygen Cylinders 🧪  
  - Ventilators 💨  
  - Medical Staff 👩‍⚕️👨‍⚕️  
- 📊 Minimizes shortages and overstocking by smart resource planning.

---

## 🎯 Why This Project?

- Enhance **patient care quality** by early diagnosis and better preparation.  
- Increase **hospital efficiency** and reduce operational costs.  
- Provide **actionable insights** for hospital management teams.  
- Support **scalable healthcare solutions** adaptable to emergencies or pandemics.

---

## 🛠️ Technologies Used

| Technology      | Purpose                          |
|-----------------|---------------------------------|
| Python 3        | Core programming language        |
| scikit-learn    | ML model building & predictions  |
| NumPy           | Data processing & numeric ops   |
| pandas          | Data handling (optional)         |
| Matplotlib/Seaborn | Visualization (optional)        |
| Jupyter Notebook | Experimentation & prototyping    |
| Git & GitHub    | Version control & hosting        |

---

## 📁 Project Structure

Hospital-Resource-Optimization/
│
├── data/ # Dataset files (patient records, symptoms, etc.)
├── models/ # Trained ML models (Decision Tree, forecasting models)
├── notebooks/ # Jupyter notebooks for analysis and model training
├── src/ # Source code modules
│ ├── disease_prediction.py
│ ├── inflow_forecasting.py
│ ├── resource_optimization.py
│ └── utils.py
├── requirements.txt # Required Python packages
├── README.md # This documentation file
└── main.py # Main executable script to run predictions & optimization


