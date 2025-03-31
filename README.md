# Shrimp Farm Survival Rate Prediction

## **Project Overview**
This project is part of a **Data Scientist assessment** for a shrimp farming startup. The objective is to develop a **predictive model** that estimates the **Survival Rate (SR)** of shrimp farming cycles. Predicting SR accurately is crucial for optimizing farm operations, improving yield, and minimizing losses.

## **Dataset**
The dataset contains various features related to shrimp farming, including **stocking density, feed quantity, water quality parameters, and harvest data**. These variables are used to train and evaluate different machine learning models.

### **Key Features:**
- **Total Seed**: Number of shrimp stocked at the beginning of the cycle.
- **Total Harvest Weight**: Final yield in kilograms.
- **Average Harvest Size**: Average weight of harvested shrimp.
- **Feed Per Seed**: Feed consumption per shrimp.
- **Environmental Factors**: Temperature and dissolved oxygen variations.
- **Cultivation Duration**: Number of days in the farming cycle.

## **Tools & Technologies Used**
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn
- **Machine Learning Models**: XGBoost, Random Forest, LightGBM
- **Evaluation Metrics**: RMSE, MAE, MAPE

## **Project Workflow**
### **1. Data Preprocessing & EDA**
- Handling missing values and data inconsistencies.
- Exploratory Data Analysis (EDA) to understand feature relationships.
- Feature selection to improve model performance.

### **2. Model Development**
- Training different regression models (XGBoost, Random Forest, LightGBM) to predict **Survival Rate (SR)**.
- Performing hyperparameter tuning to optimize performance.
- Selecting the best model based on RMSE, MAE, and MAPE.

### **3. Model Evaluation**
- **Best Model**: XGBoost
- **Performance Metrics**:
  - **MAPE**: 17.94% (~82.06% prediction accuracy)
  - **RMSE**: 7.21
  - **MAE**: 4.68

### **4. Key Insights & Recommendations**
- The **most important features** influencing SR include **total harvest weight, average harvest size, and total seed**.
- Further improvements can be made by integrating additional water quality parameters.
- Implementing an ensemble approach or deep learning techniques may enhance predictive accuracy.

## **Conclusion**
This project successfully developed a predictive model for shrimp survival rate, providing actionable insights to optimize farm management. While the current results are promising, continuous monitoring and data updates are essential for improving model reliability.

---
**Author:** [Giovanny Theotista]
