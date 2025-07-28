# 💳 Credit Card Fraud Detection System

A Machine Learning-based web application that detects fraudulent credit card transactions in real time. Built with Flask, scikit-learn, and React.js, the system uses **Isolation Forest** and **Logistic Regression** to identify anomalies and potential fraud with high accuracy.



## 🚀 Key Features

- 🔍 **Real-time Fraud Detection** using trained ML models
- 📈 **High Accuracy** with 42% improvement over baseline
- 📊 **Live Dashboard** to visualize predictions and risk levels
- 🔐 **Secure and Scalable Architecture**
- 🎯 **Interactive Frontend** with fraud alerts and prediction insights



## 🛠️ Tech Stack

| Layer        | Technologies Used                          |
|--------------|--------------------------------------------|
| 💻 Frontend  | React.js, Chart.js, Bootstrap              |
| 🔙 Backend   | Flask (Python), REST API                   |
| 🧠 ML Models | Isolation Forest, Logistic Regression      |
| 🗃️ Database  | MongoDB (for storing transaction logs)     |
| 📡 API Comm. | Axios, Flask-RESTful                       |



## 📂 Folder Structure

├── client/ # React frontend
│ ├── components/ # UI components
│ └── App.js # Main React app
├── server/ # Flask backend
│ ├── model/ # ML model files
│ ├── app.py # API and routing
│ └── utils.py # Preprocessing and helper functions
├── data/ # Sample dataset for fraud detection
└── README.md


## 🧠 ML Models

- **Isolation Forest**: Detects anomalies by isolating observations in a tree structure — well-suited for imbalanced datasets like fraud detection.
- **Logistic Regression**: Used for binary classification to enhance prediction robustness.
- The combination of both models increases detection reliability and reduces false positives.



## 📊 Live Dashboard Features

- 🧾 Input form to test new transactions
- 🟡 Real-time prediction: **Safe** ✅ or **Fraud** ❌
- 📈 Fraud Probability Chart using **Chart.js**
- 🧠 Confidence score based on both models
