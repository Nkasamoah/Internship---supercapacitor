# Internship---supercapacitor

# Supercapacitor Performance Prediction Using Machine Learning

This project explores the use of machine learning to predict the performance of supercapacitor electrode materials. Developed as my internship project at the Materials Engineering Departrment at KNUST, it demonstrates how AI and data-driven modeling can assist in materials discovery and characterization.

## 📌 Project Overview

Supercapacitors are gaining traction due to their fast charge-discharge capability and long cycle life. However, experimental testing of new electrode materials is time-consuming. This project proposes a predictive model that estimates specific capacitance based on material properties and fabrication conditions using machine learning techniques.

## ⚙️ Tools & Technologies

- Python (NumPy, Pandas, Scikit-learn, XGBoost)
- Jupyter Notebook
- Matplotlib & Seaborn (for visualization)
- Git & GitHub

### 🔍 Role of XGBoost

XGBoost (Extreme Gradient Boosting) is a robust and efficient ensemble learning algorithm based on decision trees. It was used to train a regression model that predicts the specific capacitance of supercapacitor materials based on features like surface area, pore volume, current density, and synthesis conditions. The model works by sequentially improving weak learners to minimize prediction error, making it ideal for capturing non-linear relationships in material performance data.

## 📚 Research Basis

This project was inspired and guided by the paper: "Data-driven design of carbon-based materials for high-performance flexible energy storage devices"  
This paper provided the foundational dataset and methodology for feature selection and performance evaluation. Its approach to integrating materials informatics in energy storage guided the development of this project's machine learning framework.

## 🧠 Methodology

1. Data Collection: Gathered experimental data on electrode materials and their electrochemical performance.
2. Preprocessing: Cleaned the data, handled missing values, and normalized features.
3. Model Development:
   - XGBoost Regressor
   
4. Evaluation: Measured performance using metrics such as R² Score, MAE, and RMSE.

## 📊 Results

- **XGBoost Model**:  
Model Performance Metrics:
Training MSE: 1062.23
Testing MSE: 1776.43
Training R² Score: 0.86
Testing R² Score: 0.77




