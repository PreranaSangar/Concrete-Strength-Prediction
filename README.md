# Concrete Strength Prediction using Machine Learning

## 📌 Project Overview  
Concrete is a fundamental material in construction, and its strength plays a crucial role in the durability and safety of structures. This project leverages **machine learning algorithms** to predict **concrete strength** based on various material compositions. The goal is to provide an efficient and accurate model to assess concrete strength before its use in real-world construction.

## 📊 Dataset  
The dataset consists of **1030 rows** and **9 attributes**:  
- **Inputs**:  
  - Cement (kg)  
  - Blast Furnace Slag (kg)  
  - Fly Ash (kg)  
  - Water (kg)  
  - Superplasticizer (kg)  
  - Coarse Aggregate (kg)  
  - Fine Aggregate (kg)  
  - Age (days)  
- **Target Variable**: Concrete Strength  

Source: *Published in Cement and Concrete Research (Vol. 28, No. 12, 1998).*

## 🚀 Machine Learning Models Used  
The following machine learning models were implemented to predict concrete strength:  
- **Linear Regression**  
- **Lasso Regression**  
- **Ridge Regression**  
- **Decision Tree Regressor**  
- **XGBRF Regressor**  

## 📈 Model Performance  
The accuracy of each model is as follows:  

| Algorithm                   | Accuracy Score |
|-----------------------------|---------------|
| Linear Regression           | 0.81          |
| Lasso Regression            | 0.78          |
| Ridge Regression            | 0.81          |
| Decision Tree Regressor     | 0.82          |
| XGBRF Regressor             | 0.82          |

The **Decision Tree Regressor** and **XGBRF Regressor** achieved the highest accuracy of **82%**.

## 🛠 Installation & Setup  
To run this project on your local system, follow these steps:
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/PreranaSangar/concrete-strength-prediction.git
   cd concrete-strength-prediction
2.Install Dependencies
   pip install -r requirements.txt

3.python main.py

##📌 Features
Predicts concrete compressive strength based on material mix.
Utilizes multiple machine learning models for comparative analysis.
Provides insights into material composition for optimized construction quality.

##📜 Conclusion
The study concludes that Decision Tree Regressor and XGBRF Regressor perform best for predicting concrete strength. These models allow for a more accurate and reliable assessment of concrete strength before application, reducing potential structural failures and improving construction safety.
