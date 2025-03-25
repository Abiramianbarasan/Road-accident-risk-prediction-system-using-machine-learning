# Road-accident-risk-prediction-system-using-machine-learning
# 🚗 Road Accident Risk Prediction System using Machine Learning

## 📌 Overview  
Road accidents are a major global concern, leading to severe injuries, fatalities, and economic losses. This project aims to predict accident severity using **Machine Learning (ML)** models and deploy a **web-based** system for real-time risk assessment.  

## 📊 Project Goals  
- ✅ Develop an **ML-powered web application** to predict accident severity.  
- ✅ Analyze accident risk factors such as **weather, road conditions, traffic, and driver behavior**.  
- ✅ Identify **high-risk zones** and assist authorities in **preventing accidents**.  
- ✅ Improve emergency response times with **real-time accident notifications**.  

## 🏗️ System Architecture  
1️⃣ **User Input** → Vehicle, driver, road, and weather data.  
2️⃣ **Data Preprocessing** → Handling missing values, scaling, and feature selection.  
3️⃣ **ML Model Training** → Decision Tree, Random Forest, Logistic Regression.  
4️⃣ **Severity Prediction** → Web app shows risk level and sends alerts.  
5️⃣ **Deployment** → Hosted on **Microsoft Azure / Flask Web App**.  

---

## 📌 Technologies Used  
| Component            | Tools/Frameworks |
|----------------------|----------------|
| **Machine Learning** | Scikit-Learn, Imbalanced-learn (SMOTE) |
| **Web Framework**    | Flask, HTML, CSS |
| **Data Processing**  | Pandas, NumPy |
| **Visualization**    | Matplotlib, Seaborn |
| **Deployment**       | Microsoft Azure, Flask |

---

## 🏗️ Machine Learning Models  
🔹 **Random Forest** (Best performing with 86.86% accuracy)  
🔹 **Decision Tree**  
🔹 **Logistic Regression**  

### 🚀 Model Performance Metrics  
- **Accuracy** → Measures correct predictions.  
- **Precision** → Ensures severe accident predictions are accurate.  
- **Recall** → Captures real severe accidents.  
- **F1-Score** → Balances false positives and negatives.  
- **Confusion Matrix** → Identifies model errors.  

---

## ⚙️ How to Use the Web App  
### **1️⃣ Installation**  
Clone this repository:  
```bash
git clone https://github.com/yourusername/Accident-Risk-Prediction.git
cd Accident-Risk-Prediction
