# Flight Delay Prediction using Machine Learning

Flight delays create significant challenges for airlines, passengers, and the broader transportation network. This project focuses on developing a predictive model to forecast flight delays using machine learning techniques.

## 🛫 Project Objective

The main objective of this project is to build a **binary classification model** to predict whether a flight will be **delayed** or **on time**. The model leverages historical flight data and flight-related features such as:

- **Departure time**
- **Airline carrier**
- **Origin and destination airports**
- **Weather conditions**

## 🧠 Methodology

The project pipeline includes the following stages:

1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Feature Engineering**: Extracting and transforming features to improve model performance.
3. **Model Training**: Building a classification model using machine learning algorithms.
4. **Hyperparameter Tuning**: Optimizing model parameters to improve performance.

## 📊 Evaluation Metrics

The model is evaluated using the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **AUC-ROC**

### 🔍 Initial Results

- **AUC-ROC Score (Initial Model)**: `0.7135` — Indicates moderate discrimination ability.

### 🛠️ After Hyperparameter Tuning

- **AUC-ROC Score (Tuned Model)**: `0.7207` — Shows improvement in model performance.

The **ROC Curve** provides a visual representation of how well the model differentiates between delayed and on-time flights.

## 🚀 Conclusion

This project demonstrates that **data preprocessing**, **feature engineering**, and **model optimization** are crucial steps in building accurate and reliable predictive systems for real-world aviation applications.

## 📁 Files

- `notebook.ipynb` – Main notebook containing the entire pipeline
- `model.pkl` – Trained model file
- `README.md` – Project overview

---

✅ Built to forecast flight delays and support better decision-making in air traffic management.
