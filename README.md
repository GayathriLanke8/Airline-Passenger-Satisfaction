# Airline Passenger Satisfaction Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project focuses on predicting airline passenger satisfaction using an Artificial Neural Network (ANN). The model analyzes customer demographics, travel details, service ratings, and flight-related information to determine whether a passenger is satisfied or dissatisfied with their overall airline experience.

The objective is to build a highly accurate classification model that can help airlines identify key factors influencing customer satisfaction and improve service quality.

---

## 📊 Dataset Information

* **Dataset:** Airline Passenger Satisfaction Dataset
* **Total Records:** 103,904
* **Features:** 25 Columns
* **Target Variable:** Satisfaction
* **Problem Type:** Binary Classification

### Features Included

* Gender
* Customer Type
* Age
* Type of Travel
* Class
* Flight Distance
* Inflight WiFi Service
* Departure/Arrival Time Convenient
* Ease of Online Booking
* Gate Location
* Food and Drink
* Online Boarding
* Seat Comfort
* Inflight Entertainment
* On-board Service
* Leg Room Service
* Baggage Handling
* Check-in Service
* Inflight Service
* Cleanliness
* Departure Delay in Minutes
* Arrival Delay in Minutes
* and other service-related attributes

---

## 🎯 Project Objectives

* Predict passenger satisfaction accurately.
* Analyze the impact of airline services on customer satisfaction.
* Build a deep learning model using TensorFlow/Keras.
* Compare performance through training and validation metrics.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* TensorFlow
* Keras
* Jupyter Notebook

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

1. Removed unnecessary columns.
2. Handled missing values.
3. Encoded categorical variables.
4. Scaled numerical features using feature scaling.
5. Split dataset into:

   * Training Set
   * Validation Set
   * Test Set

---

## 🧠 ANN Architecture

### Neural Network Structure

* Input Layer
* Hidden Dense Layers
* ReLU Activation Function
* Dropout Layers (for regularization)
* Output Layer with Sigmoid Activation

### Training Configuration

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Metric: Accuracy
* Epochs: 50
* Batch Size: 32

---

## 📈 Model Performance

### Training Results

| Metric              | Value  |
| ------------------- | ------ |
| Training Accuracy   | 96.16% |
| Training Loss       | 0.0926 |
| Validation Accuracy | 95.78% |
| Validation Loss     | 0.1076 |

### Test Results

| Metric        | Value  |
| ------------- | ------ |
| Test Accuracy | 95.45% |
| Test Loss     | 0.1120 |

---

## 📋 Results

The ANN model achieved excellent performance in predicting passenger satisfaction:

✅ Training Accuracy: **96.16%**

✅ Validation Accuracy: **95.78%**

✅ Test Accuracy: **95.45%**

The small gap between training and validation accuracy indicates that the model generalizes well and shows minimal overfitting.

---

## 🚀 Key Learnings

* Data preprocessing significantly impacts ANN performance.
* Feature scaling improves neural network convergence.
* Dropout helps reduce overfitting.
* Customer service-related features strongly influence passenger satisfaction.
* Deep learning models can achieve high accuracy on structured tabular datasets when properly tuned.

---

## 📂 Project Structure

```text
Airline-Passenger-Satisfaction-ANN/
│
├── dataset/
│   └── airline_passenger_satisfaction.csv
│
├── notebooks/
│   └── Airline_ANN.ipynb
│
├── models/
│   └── ann_model.h5
│
├── images/
│   └── training_curves.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🔮 Future Improvements

* Hyperparameter tuning using Optuna.
* Model explainability using SHAP.
* Ensemble Deep Learning Models.
* Deployment using Streamlit.
* Real-time prediction API using FastAPI.

---

## 👨‍💻 Author

**Gayathri**

Aspiring Data Scientist passionate about Machine Learning, Deep Learning, Data Analytics, and Artificial Intelligence.

---

### ⭐ If you found this project useful, don't forget to star the repository!
