
# 📊 Telco Customer Churn Analysis

This project focuses on analyzing and preparing the Telco Customer dataset for churn prediction. The notebook includes data cleaning, transformation, and preparation steps needed before model training.

---

## 🚀 Project Overview

Customer churn is a major challenge for telecom companies. This notebook walks through a data cleaning pipeline to get the Telco dataset ready for churn prediction.

Churn is when customers leave a service provider. Reducing churn improves business performance.

---

## ❓ Problem Statement

The main goal is to preprocess and explore the Telco customer dataset in order to enable future prediction of customer churn using machine learning.

---

## 🧾 Dataset Information

- **Filename**: `Telco_customer.csv`
- **Records**: ~7043 rows
- **Features**: Demographics, service subscriptions, contract details, payment info, and churn status.

### Key Columns:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `MultipleLines`, `InternetService`
- `OnlineSecurity`, `TechSupport`, `StreamingTV`
- `Contract`, `PaperlessBilling`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`, `Churn`

---

## 🧹 Data Preprocessing Highlights

## \*\*No Missing Values\*\*

### Replace "No internet service" with "No" for the simplicity

## total charges is the object I need to convert that to float

## \*\*Independent and Dependent*\*

## \*\*Converting The Data\*\*

# Simple Neural Network model

- Handled missing `TotalCharges` values by converting them to float.
- Dropped or corrected invalid/empty entries.
- Confirmed that no missing values remain post-cleaning.

---

## 🧰 Libraries Used

```python
import pandas as pd
import numpy as np
```

Other libraries may be added in the modeling phase.

---

## 💻 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/telco-churn-analysis.git
   cd telco-churn-analysis
   ```

2. Place `Telco_customer.csv` in the same folder.

3. Run the notebook:
   ```bash
   jupyter notebook Telco_Customer_Churn.ipynb
   ```

---

## 📈 Sample Output

- Dataset shape: `(7043, 21)`
- Missing values removed
- Cleaned and ready-to-model DataFrame

---

## 📌 Future Scope

- Data visualization (churn vs. features)
- Feature encoding (LabelEncoder, OneHotEncoder)
- Model building (Logistic Regression, Random Forest, XGBoost)
- Model evaluation (accuracy, precision, recall)

---