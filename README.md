# hybrid_phishing_url_detection-_system-

# 🛡️ SEC Project 2025  
## Hybrid URL & Email Phishing Detection System  
### Using CNN, BiLSTM, XGBoost, LightGBM & Hybrid Models

This project implements a complete **phishing detection system** using **Machine Learning**, **Deep Learning**, and **Hybrid Models**, as developed inside the notebook **sec_project_2025.ipynb**.

The system detects phishing URLs and phishing emails using advanced techniques such as **CNN**, **BiLSTM**, **XGBoost**, **LightGBM**, and a **Hybrid Ensemble Model**.

---

## 📌 Project Highlights

- ✔ Data preprocessing for URLs & email text  
- ✔ Feature extraction  
- ✔ Deep learning models (CNN, BiLSTM, Hybrid CNN-LSTM)  
- ✔ Machine learning models (XGBoost, LightGBM)  
- ✔ Final hybrid ensemble model  
- ✔ Performance metrics: Accuracy, Precision, Recall, F1  
- ✔ Visualizations included  
- ✔ ROC curve, Confusion Matrix, Accuracy Comparison  

---
# 🚀 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- XGBoost  
- LightGBM  
- Matplotlib  
- Seaborn


# 🧠 Models Implemented (as in Notebook)

### 🔹 **1. CNN Model**
- Extracts spatial patterns from URLs  
- Useful for character-level phishing patterns  

### 🔹 **2. BiLSTM Model**
- Captures long-term dependencies in text  
- Works well for email body detection  

### 🔹 **3. CNN + BiLSTM Hybrid**
- CNN → Feature Extraction  
- BiLSTM → Sequence Learning  
- Strong deep learning model  

### 🔹 **4. XGBoost Model**
- Gradient boosting  
- Great for structured phishing URL features  

### 🔹 **5. LightGBM Model**
- Fast boosting algorithm  
- Leaf-wise tree growth  
- Good for large-scale phishing datasets  

### 🔹 **6. Hybrid LightGBM + XGBoost (Final Model)**
- Takes average/weighted prediction from both models  
- Produces highest accuracy in the notebook


## Install dependencies
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
xgboost
lightgbm

