 ANN-based customer churn prediction system using TensorFlow/Keras with an interactive Streamlit web application.


 # ANN Classification – Customer Churn Prediction

## 📌 Project Overview

This project uses an **Artificial Neural Network (ANN)** to predict whether a customer is likely to **churn** (leave a service/company) based on their demographic and account-related information.

The model is trained on customer data and learns patterns associated with customer churn. A **Streamlit web application** is included to provide an interactive interface for making churn predictions.

## 🚀 Features

* Customer churn prediction using an Artificial Neural Network
* Data preprocessing and feature scaling
* Neural network built using TensorFlow/Keras
* Binary classification
* Interactive Streamlit web interface
* User-friendly prediction interface
* Model and preprocessing components can be saved and reused for inference

## 🧠 Technologies Used

* **Python**
* **TensorFlow / Keras**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **TensorBoard**
* **Streamlit**

## 🏗️ Model Architecture

The ANN consists of multiple fully connected (`Dense`) layers:

```text
Input Features
      ↓
Dense Layer (64 neurons, ReLU)
      ↓
Dense Layer (32 neurons, ReLU)
      ↓
Output Layer
      ↓
Churn Prediction
```

The neural network learns from the training data and produces a prediction indicating whether a customer is likely to churn.

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Selection
   ↓
Data Preprocessing
   ↓
Feature Scaling
   ↓
Train/Test Split
   ↓
ANN Model
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Streamlit Application
   ↓
Churn Prediction
```

## 📊 What is Customer Churn?

**Customer churn** refers to a customer stopping or discontinuing their relationship with a company or service.

For example:

* `0` → Customer is predicted **not to churn**
* `1` → Customer is predicted **to churn**

Churn prediction can help businesses identify customers who may leave and understand factors associated with customer retention.

## 💻 Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/sharique2006/ann-classification-churn.git
cd ann-classification-churn
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the environment

Windows:

```bash
.venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser.
 
## 🌐 Deployment

The application can be deployed using **Streamlit Community Cloud** by connecting the GitHub repository and selecting `app.py` as the main application file.

## 🎯 Future Improvements

* Improve model accuracy through hyperparameter tuning
* Experiment with different ANN architectures
* Add more evaluation metrics
* Add feature importance/explainability
* Improve the Streamlit UI
* Add probability-based churn predictions
* Deploy the application for public access

## 👨‍💻 Author

**Sharique Sabeeh**

B.Tech – Computer Science & Engineering

GitHub: `https://github.com/sharique2006`
