# Maintenance Status Prediction

This project implements a **machine learning model** to predict maintenance status (failure modes) of marine engines using historical sensor data. The goal is to build a predictive system that helps anticipate failures before they occur.

---

## 🚀 Project Overview
- **Problem:** Predict equipment failure modes to enable proactive maintenance.  
- **Dataset:** Marine engine sensor data (`marine_engine_data.csv`).  
- **Approach:** Data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.  
- **Models Used:** Logistic Regression, Random Forest, XGBoost (comparisons done to select the best performing model).  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, and Confusion Matrix.  

---

## 📂 Repository Structure
maintenance-prediction/
│── data/ # dataset (sample or synthetic if licensing restricts original)
│── notebooks/ # Jupyter notebooks for EDA & model training
│── src/ # Python scripts (preprocessing, training, prediction)
│── model/ # saved model files (.pkl/.joblib)
│── requirements.txt # dependencies
│── README.md # project overview (this file)

yaml
Copy code

---

## 🔧 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/maintenance-prediction.git
   cd maintenance-prediction
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the notebook:

bash
Copy code
jupyter notebook notebooks/maintenance.ipynb
Example prediction:

python
Copy code
from src.predict import predict_status
status = predict_status(new_sensor_data)
print(status)  # "Needs Maintenance" or "Normal"

👤 Author
Youssef Hassan
