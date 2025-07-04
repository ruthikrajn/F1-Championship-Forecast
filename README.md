# Formula One Drivers’ Performance  



**Author:** Ruthik Raj Nataraja  

---

## 📑 Table of Contents

1. [Problem Setting](#problem-setting)  
2. [Project Objective](#project-objective)  
3. [Data Source](#data-source)  
4. [Data Description](#data-description)  
5. [Exploratory Data Analysis](#exploratory-data-analysis)  
6. [Data Transformation](#data-transformation)  
7. [Model Selection](#model-selection)  
8. [Evaluation Metrics](#evaluation-metrics)  
9. [Results & Insights](#results--insights)  
10. [Limitations](#limitations)  
11. [Conclusion](#conclusion)  
12. [Future Work](#future-work)  

---

## 🏁 Problem Setting

The performance of Formula One drivers is influenced by various factors such as experience, team quality, car specifications, and race conditions. The aim of this project is to quantify and model driver performance using historical race data.

---

## 🎯 Project Objective

To analyze Formula One racing data and build a predictive model that evaluates and compares driver performances based on various measurable metrics.

---

## 🔗 Data Source

The dataset was obtained from public F1 archives, including:

- [Ergast Developer API](https://ergast.com/mrd/)
- [Kaggle Formula 1 Datasets](https://www.kaggle.com/rohanrao/formula-1-world-championship-1950-2020)

---

## 📊 Data Description

The dataset includes information such as:

- Driver Name  
- Team  
- Position  
- Race Name and Year  
- Laps Completed  
- Qualifying Time  
- Fastest Lap  
- Constructor Standings  
- Pit Stops  

The data spans from 1950 to 2022, covering more than 1,000 races.

---

## 🔍 Exploratory Data Analysis

- Frequency of wins by drivers and teams  
- Correlation between qualifying position and final position  
- Heatmaps showing team dominance by season  
- Trends in driver consistency over years  

---

## 🧹 Data Transformation

- Handled missing values (e.g., disqualifications, retirements)  
- Encoded categorical features  
- Normalized continuous variables  
- Created new features (e.g., average speed per race, podium rate)

---

## 🤖 Model Selection

Tested multiple models for prediction and classification:

- Random Forest  
- Logistic Regression  
- XGBoost  
- Decision Trees  

Used cross-validation and hyperparameter tuning to select the best model.

---

## 📈 Evaluation Metrics

- Accuracy  
- F1 Score  
- Precision & Recall  
- Confusion Matrix  

---

## 💡 Results & Insights

- Qualifying position is a strong predictor of final result.  
- Certain teams consistently outperform others across decades.  
- Driver consistency and adaptability significantly impact race outcomes.

---

## ⚠️ Limitations

- Data inconsistency in earlier decades  
- Lack of sensor data (e.g., weather, tire wear, engine status)  
- Driver "skill" cannot be completely quantified due to external factors

---

## 🔮 Future Work

- Integrate telemetry and car sensor data  
- Model team strategies and pit stop optimization  
- Predict outcomes of upcoming races using real-time inputs

