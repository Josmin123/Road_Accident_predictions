# 🚗 Road Accident Severity Analysis & Prediction

![Road Safety](road accident.jpg)
## 📌 Overview
This project analyzes **road accident severity** using a dataset containing **132,000 records and 30 features**.  
The goal is to **understand accident patterns, identify key factors affecting severity, and build a machine learning model** to predict accident severity.

## 🚦 Problem Statement
Road accidents cause **thousands of injuries and fatalities every year**. Understanding **which factors influence accident severity** can help:
- Improve road safety measures 🚧
- Reduce accident impact 🚑
- Assist policymakers in implementing better regulations 📜

However, predicting accident severity is **challenging** due to the involvement of multiple factors like **weather conditions, road type, driver behavior, and vehicle condition**.

---

## 📊 Dataset Information
- **Total Records:** 132,000  
- **Total Features:** 30  
- **Features Include:**  
  - `Accident Severity` (Target Variable: Minor, Moderate, Severe)  
  - `Speed Limit`, `Weather Conditions`, `Number of Vehicles Involved`, `Road Type`  
  - `Driver Alcohol Level`, `Traffic Volume`, `Emergency Response Time`  

The dataset was cleaned, preprocessed, and analyzed to extract valuable insights.

---

## 🔎 Exploratory Data Analysis (EDA) & Key Insights
- **Higher Speed Limits → More Severe Accidents 🚀**  
  - High-speed roads had a **greater proportion of severe accidents**.  

- **Number of Vehicles Involved → Higher Severity 🚗🚙🚛**  
  - Multi-vehicle collisions **tended to be more severe** compared to single-vehicle crashes.  

- **Weather & Road Conditions Had Little Impact 🌧️**  
  - Surprisingly, accident severity **wasn't significantly higher in bad weather conditions**.  
  - Drivers may be adjusting their behavior in adverse conditions.  

- **Economic Loss is Higher for Severe Accidents 💰**  
  - Financial damages **correlated strongly with accident severity**.

---

## 🧠 Machine Learning Approach & Challenges
A **Random Forest Classifier** and **XGBoost Classifier** were trained to predict accident severity.

### **🔬 Models Tried:**
| Model                  | Accuracy |
|------------------------|----------|
| Random Forest (Default) | **34%** |
| Random Forest (Tuned) | **33%** |
| XGBoost | **34%** |

Despite **feature selection & hyperparameter tuning**, the model struggled to achieve high accuracy.  
**Key Challenge:** Accident severity **depends on many external, untracked factors**, making prediction difficult.

---

## 🚀 Key Findings & Conclusion
✅ **Machine Learning Struggled to Predict Severity (33-34% Accuracy)**  
✅ **Speed Limit, Number of Vehicles, and Economic Loss were the strongest predictors**  
✅ **Weather, Driver Fatigue, and Road Type had minimal impact**  
❌ **The dataset lacked key real-world factors like driver reaction time, impact speed, and emergency response quality**  

**🔎 Conclusion:** While predicting accident severity is difficult, the analysis provided valuable insights into accident trends.

---

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/road-accident-analysis.git
cd road-accident-analysis
