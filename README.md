# Loan Default Prediction System

## 📌 Project Overview

The **Loan Default Prediction System** is a data analysis and machine learning project developed using Python.
This project helps analyze borrower information and identify patterns that may lead to loan default.

Financial institutions face risks when borrowers fail to repay loans.
This system performs:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Risk Analysis
* Linear Regression Modeling
* Interactive Dashboard Visualization

using the **Lending Club Loan Dataset** from Kaggle.

---

# 📂 Dataset Information

* **Dataset Source:** Kaggle
* **Dataset Name:** Lending Club Loan Data

[Lending Club Dataset on Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club?utm_source=chatgpt.com)

---

# 📌 Features Used

The following columns were selected for analysis:

| Column Name    | Description          |
| -------------- | -------------------- |
| loan_amnt      | Loan amount          |
| term           | Loan duration        |
| int_rate       | Interest rate        |
| annual_inc     | Annual income        |
| emp_length     | Employment length    |
| home_ownership | Ownership status     |
| purpose        | Loan purpose         |
| grade          | Loan risk grade      |
| loan_status    | Fully Paid / Default |

---

# 🎯 Objectives

The main objectives of this project are:

* Analyze borrower financial behavior
* Identify high-risk borrowers
* Perform data visualization
* Build a Linear Regression model
* Predict loan-related patterns
* Create an interactive dashboard
* Support better loan approval decisions

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly
* Google Colab

---

# 📊 Project Workflow

## 1. Data Collection

* Load dataset from Kaggle
* Understand dataset structure

## 2. Data Cleaning

* Handle missing values
* Convert data types
* Remove unnecessary columns

## 3. Exploratory Data Analysis (EDA)

* Loan distribution analysis
* Income analysis
* Interest rate analysis
* Correlation analysis

## 4. Risk Analysis

Borrowers are classified into:

* Low Risk
* Medium Risk
* High Risk

## 5. Machine Learning Model

* Linear Regression model
* Train-test split
* Prediction and evaluation

## 6. Dashboard Visualization

Interactive charts using Plotly:

* Income vs Loan Amount
* Loan Distribution
* Risk Comparison
* Interest Rate Trends

---

# 📈 Visualizations Used

* Count Plots
* Histograms
* Scatter Plots
* Heatmaps
* Dashboard Charts

---

# 🤖 Machine Learning

## Model Used

* Linear Regression

## Independent Variables

* annual_inc
* int_rate
* term

## Dependent Variable

* loan_amnt

---

# 📌 Model Evaluation

The model performance is evaluated using:

* R² Score
* Prediction Visualization
* Residual Analysis

---

# 💡 Key Insights

* Higher interest rates indicate higher borrower risk.
* Lower income borrowers show higher default possibility.
* Loan term and interest rate influence loan behavior.
* Risk categorization helps identify potential defaulters.

---

# ▶️ How to Run the Project

## Step 1 — Install Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly
```

## Step 2 — Download Dataset

Download the dataset from Kaggle.

## Step 3 — Upload Dataset to Google Colab

Upload:

```text
accepted_2007_to_2018Q4.csv
```

## Step 4 — Run Python Program

Run the complete Python script in Google Colab.

---

# 📌 Future Improvements

* Use advanced ML models like:

  * Random Forest
  * XGBoost
  * Logistic Regression

* Improve dashboard interactivity

* Deploy using Streamlit or Flask

* Add real-time prediction system

---

# 👨‍💻 Author

Developed as a Data Analysis and Machine Learning Project using Python and Google Colab.
