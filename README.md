# Project 4: Data Cleaning and Advanced Forecasting Methods for Complaint Data

## **Project Overview**
This project showcases two key components:
1. **Data Cleaning and Preparation**: Cleaning and transforming real-world JSON complaint data to make it suitable for analysis.
2. **Advanced Forecasting**: Using modern forecasting techniques like Prophet and Ridge/Lasso Regression to predict complaint trends.

The goal is to demonstrate expertise in handling complex datasets and applying predictive modeling techniques effectively.

---

## **Project Files**

### **File 1: Data Cleaning and Preparation**
- **Objective**: Prepare raw JSON complaint data for analysis and modeling.
- **Key Steps**:
  - Parsed and flattened a nested JSON structure into a tabular format.
  - Addressed missing values and inconsistencies.
  - Converted date fields to datetime format for time-series analysis.
  - Saved the cleaned data as a JSON file for further analysis.
- **Output**: A clean, structured dataset.

---

### **File 2: Advanced Forecasting Methods**
- **Objective**: Predict complaint trends using advanced forecasting methods.
- **Techniques Used**:
  - **Prophet**:
    - Captures seasonality and trends in time-series data.
    - Provides smooth and interpretable forecasts.
  - **Ridge and Lasso Regression**:
    - Predicts complaint counts using lagged features.
    - Handles multicollinearity with regularization techniques.
- **Results**:
  - Prophet effectively captured seasonal trends in complaint volumes.
  - Ridge regression outperformed Lasso, with lower Mean Squared Error (MSE).

---

## **Key Results**

### **Prophet Model**
- **Strength**: Effective for long-term trends and seasonal patterns.
- **Output**: Accurate forecasts with smooth predictions.

### **Ridge Regression**
- **MSE**: `0.5214`  
- Outperformed Lasso regression, showcasing its robustness in handling multicollinearity.

### **Lasso Regression**
- **MSE**: `0.5688`  
- Performed well but was slightly less accurate than Ridge in this context.

---

## **Technologies Used**
- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` (Data Cleaning and Manipulation)
  - `matplotlib`, `seaborn` (Visualization)
  - `prophet` (Time Series Forecasting)
  - `scikit-learn` (Regression Modeling)
- **File Format**: JSON (Input and Output)

---

## **How to Run**
1. **Prerequisites**:
   - Install required libraries:
     ```bash
     pip install pandas numpy matplotlib seaborn prophet scikit-learn
     ```

2. **Steps**:
   - **Run File 1**: Clean the raw JSON file and generate a cleaned dataset.
   - **Run File 2**: Use the cleaned dataset for forecasting and analyze the results.

---

## **Lessons Learned**
1. **Data Cleaning**:
   - Mastery in handling nested JSON structures and preparing data for analysis.
2. **Forecasting Techniques**:
   - Prophet is highly effective for time-series data with seasonality.
   - Ridge regression performs well in cases of multicollinearity, making it suitable for lagged feature datasets.

---

## **Next Steps**
1. **Advanced Modeling**:
   - Incorporate other models like XGBoost or Neural Networks for further exploration.
2. **Interactive Visualization**:
   - Create a dashboard to visualize trends and forecasts.
3. **Classification Models**:
   - Explore models to predict complaint outcomes or resolutions.

---

## **Author** 
Zana Simanel | Portfolio Builder  

