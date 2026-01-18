# 🏥 Healthcare Premium Prediction (Predictive Analytics)

### 📋 Project Overview
This project builds an end-to-end machine learning system to **predict annual health insurance premiums** based on demographic, lifestyle, and medical risk factors.  
The goal is to demonstrate how insurers can **automate premium estimation** using structured data while maintaining interpretability and deployment readiness.

The solution includes:
- Feature engineering from raw medical and demographic data
- Separate modeling strategies for different age groups
- A deployed **Streamlit web application** for real-time predictions

### 🎯 Business Value
Health insurance pricing depends on multiple risk factors that are often manually evaluated. This project shows how machine learning can:

- **Automate premium estimation** for faster quote generation
- **Standardize risk assessment** across customers
- **Surface key cost drivers** such as age, smoking behavior, BMI category, and medical history
- **Support business decisions** with explainable, data-backed predictions

---

### ✨ Key Features
- **Age-Segmented Modeling**
  - Linear Regression for younger customers
  - XGBoost Regression for older customers with more complex risk patterns
- **Feature Engineering**
  - Encoded categorical variables (Region, Smoking Status, Employment)
  - Medical history risk scoring and normalization
  - Optional genetic risk feature for younger age groups
- **Interactive Web App**
  - Streamlit UI for instant premium estimation
  - Input validation to ensure realistic values
- **Production-Oriented Design**
  - Model artifacts saved and reused for inference
  - Clear separation between training, preprocessing, and prediction logic

---

### 🛠️ Tech Stack & Methodology
* **Language:** Python 3.x
* **Data Science Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost
* **Deployment:** Streamlit (Web Framework)
* **Design Pattern:** Modular code structure for easy maintenance and scalability.

---

## 📊 Modeling Approach
1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Outlier detection
   - Feature relationships with premium amount

2. **Feature Engineering**
   - One-hot encoding for categorical variables
   - Medical risk score derivation
   - Min-Max scaling for numerical features

3. **Modeling Strategy**
   - **Young group (≤ 25 years):** Linear Regression  
   - **Rest group (> 25 years):** XGBoost Regressor (CPU-safe configuration)

---

### 📊 Model Performance
The models were evaluated using R² (Coefficient of Determination) and Mean Absolute Error (MAE) to ensure high reliability:
* **XGBoost Performance:** ~98.5% Accuracy
* **Linear Regression:** Highly effective for linear trends in specific age segments.

---

The deployed app allows users to:
- Input personal and medical details
- Receive an estimated annual insurance premium
- Understand how different risk factors influence pricing

---

### ⚙️ Installation & Usage

**1. Clone the repository**
```bash
git clone [https://github.com/syeda-tabassum-rahaman/healthcare-premium-prediction-ml](https://github.com/syeda-tabassum-rahaman/healthcare-premium-prediction-ml)


