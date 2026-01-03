# Sleep Apnea Detection using Machine Learning and IoT

## 📌 Project Overview
Sleep Apnea Detection using Machine Learning and IoT is a final year BE (AIML) project designed to identify and predict sleep apnea conditions using physiological data collected through IoT devices. The system leverages machine learning techniques to classify sleep apnea and provides real-time predictions and visualizations through a Streamlit web application.

---

## 🎯 Objectives
- To detect sleep apnea using machine learning algorithms
- To integrate IoT-based physiological data for analysis
- To provide real-time prediction and visualization using a web dashboard
- To assist in early screening and monitoring of sleep apnea

---

## 🧠 Technologies Used
- **Programming Language:** Python (3.10)
- **Machine Learning:** Random Forest Classifier
- **ML & Data Libraries:** Pandas, NumPy, Scikit-learn, Joblib
- **Web Framework:** Streamlit (v1.32.2)
- **Data Visualization:** Matplotlib, Plotly
- **Cloud & Backend:** Firebase (Pyrebase4)
- **Configuration Management:** python-dotenv
- **HTTP Requests:** Requests
- **Deployment Platform:** Streamlit Cloud 

---

## ⚙️ System Architecture
1. IoT devices collect physiological parameters (HR, SpO₂, etc.)
2. Data is preprocessed and fed into the ML model
3. Trained ML model predicts sleep apnea condition
4. Results are displayed via Streamlit dashboard
5. Firebase handles authentication and data storage

---

## 📊 Machine Learning Model
- **Algorithm:** Random Forest Classifier  
- **Accuracy:** ~97%  
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report  

---

## 🚀 Features
- Secure user authentication.
- Real-time sleep apnea prediction using machine learning.
- Interactive data visualization.
- Automated email alerts.
- Downloadable medical reports.
- Cloud deployment.

---

## 🖥️ Installation (Local Setup)

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
streamlit run app.py
