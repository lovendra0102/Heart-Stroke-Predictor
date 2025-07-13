to run this code in terminal use this command
streamlit run app.py



command i have used step by step to install all libraries
  python -m pip install streamlit pandas scikit-learn joblib

command i used to run this code 
   streamlit run app.py


🫀 Heart Stroke Prediction Web App
A simple and interactive machine learning web app built using Streamlit to predict the risk of heart disease based on user inputs.

🚀 Features
Predicts heart disease risk using a trained K-Nearest Neighbors (KNN) classifier.

Interactive user interface with sliders and dropdowns.

Real-time prediction with input standardization.

Displays user-friendly risk messages.

Footer: "Made with ❤️ by Lovendra Kumar"

📊 Input Parameters
The app asks for the following medical and lifestyle information:

Age

Sex (Male/Female)

Chest Pain Type

Resting Blood Pressure

Cholesterol Level

Fasting Blood Sugar

Resting ECG

Max Heart Rate

Exercise-Induced Angina

Oldpeak (ST Depression)

ST Slope

🧠 Model Details
Algorithm: K-Nearest Neighbors (KNN)

Preprocessing: Scaled inputs with StandardScaler, one-hot encoding for categorical features

Files Used:

knn_heart_model.pkl – Trained KNN model

heart_scaler.pkl – Scaler used during training

heart_columns.pkl – Expected input columns

🛠️ Tech Stack
Python

Streamlit

scikit-learn

pandas

joblib



