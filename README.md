# House Price Prediction System

An end-to-end Machine Learning web application that predicts California house prices based on various demographic and geographic features.

##  Student Information
* **Name:** Edidiongabasi Inyangudoh
* **Course:** Computer Science
* **Metric No:** 22CG031868

---

##  Live Demo
**Deployment Link:** https://house-price-prediction-n1ri.onrender.com

---

##  Project Overview
This project is part of a series of AI systems developed to demonstrate predictive modeling. It uses a **Neural Network** trained on the California Housing dataset to estimate house values. The system consists of:
1. **Model:** A Deep Learning model (`model.h5`) built using TensorFlow/Keras.
2. **Backend:** A Flask application (`app.py`) that handles the logic and serves predictions.
3. **Frontend:** A responsive web interface (`index.html`) for user input.

### Features Predicted:
* Median Income
* House Age
* Average Rooms & Bedrooms
* Population & Occupancy
* Latitude & Longitude

---

## 📂 Project Structure
```text
├── app.py              # Flask Backend Logic
├── model.h5            # Trained Neural Network Model
├── requirements.txt    # Library Dependencies
└── templates/
    └── index.html      # Frontend Webpage
