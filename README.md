# 🏥 Healthcare Premium Prediction (Predictive Analytics)

### 📋 Project Overview
This project provides a data-driven solution for the insurance industry to automate the estimation of individual health insurance premiums. By leveraging machine learning, the system analyzes demographic and health-related factors to provide instant, accurate cost projections, reducing manual underwriting time.

### 🎯 Business Value
* **Automation:** Streamlines the quote-generation process for insurance providers.
* **Risk Assessment:** Identifies key cost drivers such as BMI and smoking status to assist in portfolio risk management.
* **Transparency:** Offers users immediate insights into how personal health choices affect insurance costs.

---

### ✨ Key Features
* **Multi-Model Approach:** Implements both Linear Regression and XGBoost for optimized accuracy across different age demographics.
* **Interactive UI:** A Streamlit-based web interface for real-time premium calculation.
* **Feature Engineering:** Specialized data processing to handle categorical variables (Region, Smoking Status) and medical history.
* **Production-Ready:** Includes a validation layer to ensure input data (Age, BMI) falls within realistic logical boundaries.

---

### 🛠️ Tech Stack & Methodology
* **Language:** Python 3.x
* **Data Science Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost
* **Deployment:** Streamlit (Web Framework)
* **Design Pattern:** Modular code structure for easy maintenance and scalability.

---

### 📊 Model Performance
The models were evaluated using R² (Coefficient of Determination) and Mean Absolute Error (MAE) to ensure high reliability:
* **XGBoost Performance:** ~98.5% Accuracy
* **Linear Regression:** Highly effective for linear trends in specific age segments.

---

### ⚙️ Installation & Usage

**1. Clone the repository**
```bash
git clone [https://github.com/syeda-tabassum-rahaman/healthcare-premium-prediction-ml](https://github.com/syeda-tabassum-rahaman/healthcare-premium-prediction-ml)

