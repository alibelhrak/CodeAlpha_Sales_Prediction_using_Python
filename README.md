# 📈 Sales Forecasting and Marketing Insight Tool

## 🧠 Objective
This project aims to **predict future sales** based on advertising spend, target segment, and marketing platform. It also provides **actionable insights** to optimize business marketing strategies using regression models and data analysis.

---

## 📊 Problem Statement

Businesses often invest heavily in advertising across different platforms and target various consumer segments. However, understanding which factors actually drive sales — and by how much — is crucial for **maximizing return on investment (ROI)**.

### Goals:
- Predict sales using advertising and demographic data.
- Identify which factors (spend, platform, segment) impact sales the most.
- Provide strategic marketing recommendations based on data.

---

## 🧰 Technologies Used

- **Python 3**
- **Pandas** (Data manipulation)
- **Seaborn & Matplotlib** (Visualization)
- **Scikit-learn** (Regression models, preprocessing)
- **XGBoost** (Gradient Boosting)
- **NumPy** (Math operations)

---

## 🗃️ Dataset
You can download the dataset from [https://www.kaggle.com/datasets/bumba5341/advertisingcsv].

---

## 🔧 Workflow
### 1. Model Training
Tested multiple regression models:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor ✅
- XGBoost Regressor

### 2. Evaluation Metrics
Used for comparing models:
- **RMSE** (Root Mean Squared Error)
- **R² Score** (Explained Variance)

### 4. Model Results

| Model               | RMSE   | R² Score |
|--------------------|--------|----------|
| Linear Regression  | 1.7816 | 0.8994   |
| Ridge Regression   | 1.7816 | 0.8994   |
| Lasso Regression   | 1.7806 | 0.8996   |
| **Random Forest**  | **0.7302** | **0.9831** ✅ |
| XGBoost            | 0.9322 | 0.9725   |

---

## ✅ Key Insights

- **Advertising Spend** has the highest impact on sales.
- **Social Media and Online Platforms** outperform TV and Print in terms of ROI.
- **Target Segment A** responded more positively to ads than Segment C.
- **Random Forest** provided the best performance and was used for final predictions.

---


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/alibelhrak/CodeAlpha_Sales_Prediction_using_Python.git

   ```
Install dependencies:
   ```bash
bashpip install -r requirements.txt
   ```

