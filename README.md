# Customer-Churn-Prediction

Churn Prediction Project (Deep Learning & Streamlit Integration)
Objective: Predict customer churn using bank customer data.
Dataset: Churn_Modelling.csv.
Preprocessing:
Feature Engineering: Label encoding for 'Gender' and one-hot encoding for 'Geography'.
Scaling: Standardized features with StandardScaler.
Model:
ANN Architecture:
Three layers: Dense(64), Dense(32), Dense(1 with sigmoid).
Trained using Adam optimizer and binary cross-entropy loss.
Callbacks: Early stopping and TensorBoard for monitoring.
Performance:
Achieved strong predictive performance with appropriate callbacks for optimization.
Deployment:
Created an interactive Streamlit web app for real-time predictions.
Integrated with ngrok for remote accessibility.
Key Technologies: Python, TensorFlow/Keras, Pandas, Scikit-learn, Streamlit, ngrok.
