# 🏦 Transaction - Bank Churn Prediction (EDA Project)

This is an **Exploratory Data Analysis (EDA)** project focusing on **bank customer churn prediction**. The analysis identifies key patterns and customer behaviors that could lead to churn, helping banks develop strategies to retain valuable clients.

---

## 📌 Project Overview

- 🧠 Goal: Analyze customer behavior and churn trends.
- 📊 Dataset: Bank Churn Dataset (Excel) from [Kaggle](https://www.kaggle.com/)
- ⚙️ Environment: Visual Studio Code (VS Code)
- 📁 Language: Python (Pandas, Matplotlib, Seaborn, etc.)

---

## 📂 Folder Structure

Transaction--Bank-Churn/
├── data/
│ └── BankChurnData.xlsx
├── eda/
│ └── churn_analysis.ipynb
├── images/
│ ├── churn-rate.png
│ ├── gender-distribution.png
│ └── correlation-heatmap.png
└── README.md

yaml
Copy
Edit

---

## 🛠️ Tools and Libraries Used

| Tool          | Purpose                          |
|---------------|----------------------------------|
| Python        | Core programming language        |
| Pandas        | Data manipulation & analysis     |
| Matplotlib    | Visualization                    |
| Seaborn       | Advanced statistical plotting    |
| Jupyter / VS Code | Interactive analysis          |
| Excel         | Source data format               |

---

## 🔍 Key Insights Explored

- 📉 Churn Rate and Customer Distribution
- 🔁 Tenure and Activity Trends
- 🧍 Gender-based Churn Patterns
- 💳 Credit Score, Balance, and Exit Correlation
- 🌍 Geography and its Influence on Churn
- 📊 Heatmap of Feature Correlations

---

## 📸 Sample Visualizations

### 🔥 Churn Rate Breakdown
![Churn Rate](./images/churn-rate.png)

### ⚖️ Gender Distribution
![Gender Distribution](./images/gender-distribution.png)

### 🧠 Feature Correlation Heatmap
![Heatmap](./images/correlation-heatmap.png)

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone git@github.com:viniska/Transaction--Bank-Churn.git
cd Transaction--Bank-Churn
Install necessary libraries:

bash
Copy
Edit
pip install pandas matplotlib seaborn openpyxl
Open the notebook or script in VS Code or Jupyter:

bash
Copy
Edit
code eda/churn_analysis.ipynb
📌 Dataset Reference
Kaggle: Bank Churn Dataset

Format: .xlsx Excel sheet

Contains columns like: Customer ID, Geography, Gender, Age, Balance, Tenure, Estimated Salary, and Churn

📈 Future Improvements
Model building for churn prediction (Logistic Regression, Random Forest)

Dashboard creation using Streamlit or Power BI

Deeper feature engineering

👤 Author
Viniska
🔗 GitHub Profile

