# 🩺 PrediCure

**PrediCure** is a fast, intelligent, and user-friendly predictive tool designed to help users detect **chronic diseases** at an early stage using minimal input and machine learning intelligence.

It combines predictive health insights with actionable guidance — including a **diet recommender system** to help users improve their health outcomes proactively.

---

## 🚀 Project Overview

**PrediCure** bridges the gap between machine learning and healthcare accessibility. Built as a full-stack web application, it allows users to:

* Select a disease for prediction
* Enter a few relevant health parameters
* Instantly receive prediction results
* Get personalized dietary recommendations based on the outcome

Whether it's diabetes, heart disease, or liver disease — **PrediCure** aims to empower early detection with just a few clicks.

---

## 🧱️ Tech Stack

| Layer       | Technology                                                                                   |
| ----------- | -------------------------------------------------------------------------------------------- |
| Front-End   | HTML5, CSS3, JavaScript, Bootstrap                                                           |
| Back-End    | Python (Flask / FastAPI), Scikit-learn, Pandas                                               |
| ML Models   | Pre-trained models for chronic disease prediction (e.g., Logistic Regression, Random Forest) |
| Diet System | Rule-based or ML-based recommendation system                                                 |
| Deployment  | (Optional) Heroku / Render / Localhost                                                       |

---

## ⚙️ Core Features

✅ Predict multiple chronic diseases (diabetes, heart disease, etc.)
✅ Simple UI with dropdowns, forms, and guided input fields
✅ Fast predictions powered by trained ML models
✅ Personalized **diet plan recommendations** based on prediction result
✅ REST API for front-end ↔ back-end communication
✅ Modular and scalable design for adding more diseases in the future

---

## 📊 How It Works

### 1. User Interface (Front-End)

* User selects the disease type
* Inputs health parameters (e.g., glucose, BMI, blood pressure)
* Clicks “Predict” button

### 2. Prediction Engine (Back-End)

* The front-end sends data to a Flask/FastAPI endpoint
* The selected ML model processes the inputs
* The model returns a prediction (e.g., "High Risk", "Low Risk")

### 3. Result Display

* Prediction result is shown on screen
* A recommended **diet plan** is displayed below the prediction

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/predicure.git
cd predicure
```

### 2. Set up the Python environment

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

### 3. Run the application

```bash
python app.py
```

Visit: `http://127.0.0.1:5000` in your browser.

---

## 🥗 Diet Recommendation System

After a prediction is made, the system displays a curated **diet plan** based on the diagnosis. These plans are either:

* **Static rule-based plans** for early prototypes
* **ML-enhanced plans** (coming soon) that adapt based on user profile and disease severity

### Examples:

* **Diabetes:** low sugar, high fiber meals
* **Heart Disease:** low-sodium, omega-3 rich diets
* **Liver Disease:** high-protein, low-fat food items

---

## 🌐 Roadmap

* ↺ Add more disease models (e.g., kidney, thyroid, cancer)
* 📊 Dashboard for tracking predictions over time
* 🧠 Upgrade diet recommendation with AI personalization
* 🌍 Deploy the app online (Heroku, Netlify + Render API)
* 📱 Mobile-responsive UI or Android PWA

---

## 🧪 What We Learned

* Integrating ML with real-time web apps
* Structuring modular Flask/FastAPI APIs
* Designing clean UIs for health tech tools
* Building beginner-friendly health diagnostics
* Creating value beyond prediction with practical diet plans

---

## 👍 Contributing

Pull requests are welcome! If you'd like to contribute:

* Fork the repo
* Create a new branch
* Make your changes
* Submit a PR 🚀

---

> Made with ❤️ to empower early diagnosis and preventive care — **PrediCure: Predict. Prevent. Personalize.**
