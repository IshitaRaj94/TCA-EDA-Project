# 📉 Telecom Customer Churn Analysis (TCA)

This project analyzes customer churn behavior in a telecom company using Python. It includes data cleaning, transformation, and in-depth visual insights to identify patterns that contribute to churn.

---

## 🧾 Overview

Customer churn refers to when customers stop doing business with a company. By understanding why customers leave, telecom companies can improve retention strategies. This notebook walks through:

- Cleaning and preprocessing of customer churn data
- Exploratory data analysis using visualizations
- Insight generation for decision-making

---

## 📂 Dataset

The dataset used (`Customer Churn.csv`) includes attributes like:

- **Demographics** (gender, senior citizen status)
- **Service Usage** (tenure, contract type, internet services)
- **Payment Details** (payment method, charges)
- **Target Variable**: `Churn`

---

## 🛠 Tools & Libraries

```bash
pip install pandas matplotlib seaborn numpy
```

Used libraries:
- `pandas` – data manipulation
- `matplotlib` & `seaborn` – plotting and visualizations
- `numpy` – numerical operations

---

## 🧼 Data Preprocessing

- Replaced blank values in `TotalCharges` with 0 (where tenure was also 0)
- Converted `SeniorCitizen` from binary (0/1) to categorical (`Yes/No`)
- Verified data integrity: no nulls, no duplicate `customerID`s

---

## 📊 Key Visualizations & Insights

- 📌 **Overall Churn Rate**: 26.54% of customers have churned.
- 👴 **Senior Citizens**: More likely to churn compared to non-seniors.
- ⏳ **Tenure**: Long-term customers tend to stay; early drop-offs are common.
- 📆 **Contract Type**:
  - Customers with **month-to-month** contracts have the highest churn.
  - **1-year** and **2-year** contracts show better retention.
- 💸 **Payment Method**:
  - Customers using **Electronic Check** are more likely to churn.
- 📈 **Stacked Bar Charts**: Displayed churn percentages across categories like gender, contract type, tenure, etc.

---

## 📓 How to Run

1. Clone this repository
2. Ensure you have Jupyter or Colab
3. Launch the notebook `TCA.ipynb`
4. Follow the step-by-step cells for analysis

---

## 📄 License

Open-source under the [MIT License](LICENSE).
