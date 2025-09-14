# 🌲 Forest Fire Prediction using Flask 🔥

This project is a **Flask web application** that predicts the risk of forest fires using a trained Ridge Regression model.  
It takes weather and environmental parameters as input and outputs a prediction.

---

## 🚀 Features
- Web interface built with **Flask**
- Input parameters:
  - Temperature 🌡️
  - Relative Humidity 💧
  - Wind Speed 🌬️
  - Rain 🌧️
  - FFMC, DMC, ISI (fire danger indices)
  - Classes, Region
- Data scaled using **Standard Scaler**
- Predicts fire risk using a **Ridge Regression model**

---

## 🛠️ Tech Stack
- Python
- Flask
- Scikit-learn
- NumPy, Pandas
- HTML/CSS (templates)

---

## 📂 Project Structure

WORKSPACE/
│
├── application.py # Main Python application
├── models/ # Trained ML model + scaler
├── templates/ # HTML templates
├── static/ # CSS/JS files
├── requirements.txt # Python dependencies
└── README.md # Project documentation (this file)




---

## ⚡ How to Run Locally
1. **Clone this repo:**
```bash
git clone https://github.com/BORAPALLAVI/testforestfires.git
cd testforestfires


2.Create a virtual environment and activate it:
python3 -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3.Install dependencies:
pip install -r requirements.txt

4.Run the Flask app:
python application.py

5.Open in browser:
Home page → http://127.0.0.1:5000
Prediction page → http://127.0.0.1:5000/predictdata


Future Improvements
Add more ML models and compare accuracy
Visualize prediction results on the web page
Deploy the app online (Render, Railway, Heroku)