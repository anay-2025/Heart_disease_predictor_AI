#  Heart Disease Predictor AI

An AI-powered web application that predicts the likelihood of heart disease based on a patient's medical information. The project uses a Machine Learning model trained on a heart disease dataset and provides instant predictions through an interactive Flask web interface.

##  Features

* Predicts the likelihood of heart disease using Machine Learning.
* Clean and responsive user interface.
* Instant prediction without page reload (AJAX).
* User-friendly input form.
* Flask backend with a trained ML model.
* Deployed online using Render.

---

##  Tech Stack

### Frontend

* HTML5
* CSS
* JavaScript
* AJAX (XMLHttpRequest)

### Backend

* Python
* Flask

### Machine Learning

* Scikit-learn
* Pandas
* NumPy
* Pickle

### Deployment

* Render

---

##  Project Structure

```text
heart-disease-predictor/
│
├── app.py
├── model.pkl
├── requirements.txt
├── templates/
│   └── index.html
├── static/
├── dataset/
├── README.md
└── .gitignore
```

## Machine Learning Workflow

* Data Collection
* Data Cleaning & Preprocessing
* Feature Selection
* Model Training
* Model Evaluation
* Model Serialization
* Flask API Integration
* Deployment on Render

---

## Model Input Features

The prediction is based on various medical parameters such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Slope of ST Segment
* Number of Major Vessels
* Thalassemia

---

## Future Improvements

* Support multiple ML models for comparison.
* Improve UI with charts and visualizations.
* Add user authentication.
* Store prediction history.

---

## Author

**Anay Bhattacharya**
