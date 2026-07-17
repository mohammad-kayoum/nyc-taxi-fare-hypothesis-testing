# 🚖 NYC Yellow Taxi Fare Analysis Using Hypothesis Testing

An end-to-end data analysis project that investigates whether passengers paying by **credit card** spend significantly more on taxi fares than those paying by **cash** using statistical hypothesis testing.

---

## 📌 Project Overview

This project analyzes the **NYC Yellow Taxi Trip Records** dataset to determine whether there is a statistically significant difference in the average fare amount between different payment methods.

The analysis follows a complete data analytics workflow, including:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Outlier Detection & Removal
- Normality Assessment
- Hypothesis Testing
- Business Insight Generation

The project demonstrates how statistical analysis can support data-driven business decisions.

---

## 🎯 Business Problem

Taxi companies and transportation businesses often seek to understand customer payment behavior.

This project aims to answer the following question:

> **Do passengers who pay by credit card spend more on taxi fares than passengers who pay by cash?**

Answering this question can help businesses:

- Promote digital payment methods
- Improve customer segmentation
- Design targeted promotional campaigns
- Increase revenue through strategic incentives

---

## 📊 Dataset

**Dataset:** NYC Yellow Taxi Trip Records (2015)

The dataset includes information such as:

- Pickup & Drop-off Time
- Passenger Count
- Trip Distance
- Payment Type
- Fare Amount
- Total Amount
- Vendor Information

---

## 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Statistical Analysis | SciPy, Statsmodels |
| Development Environment | Jupyter Notebook |

---

## 🔄 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Understanding
4. Data Cleaning
5. Feature Engineering
6. Exploratory Data Analysis
7. Outlier Detection & Removal
8. Normality Assessment
9. Hypothesis Formulation
10. Welch's Two-Sample t-Test
11. Result Interpretation
12. Business Insights

---

## 📈 Exploratory Data Analysis

The exploratory analysis included:

- Passenger Count Distribution
- Payment Method Distribution
- Fare Amount Distribution
- Descriptive Statistics
- Comparison of Card vs Cash Payments
- Boxplots
- Histograms
- Q-Q Plot

---

## 📐 Statistical Method

### Null Hypothesis (H₀)

There is **no statistically significant difference** in the average fare amount between passengers paying by credit card and those paying by cash.

### Alternative Hypothesis (H₁)

There **is a statistically significant difference** in the average fare amount between passengers paying by credit card and those paying by cash.

### Statistical Test

- Welch's Two-Sample t-Test
- Significance Level (α): **0.05**

---

## 📊 Key Findings

- The dataset was successfully cleaned by handling missing values, duplicates, invalid observations, and outliers.
- Exploratory Data Analysis revealed noticeable differences in fare distributions across payment methods.
- Statistical testing produced a **p-value below 0.05**, leading to the rejection of the null hypothesis.
- The analysis indicates that passengers paying by **credit card** tend to have **higher average fare amounts** than those paying by **cash**.

---

## 💼 Business Insights

The findings suggest that payment method is associated with customer spending behavior.

Potential business applications include:

- Encouraging digital payments through rewards or loyalty programs.
- Designing targeted marketing campaigns for high-value customers.
- Improving customer segmentation based on payment preferences.
- Supporting strategic business decisions using statistical evidence.

---

## 📁 Repository Structure

```
nyc-taxi-fare-hypothesis-testing/

│── data/
│── notebooks/
│── images/
│── README.md
│── requirements.txt
│── LICENSE
│── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/nyc-taxi-fare-hypothesis-testing.git
```

2. Install the required libraries

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open the notebook and run all cells.

---

## 📸 Project Screenshots

> Add screenshots of your visualizations here.

Example:

- Payment Distribution
- Fare Distribution
- Boxplot
- Q-Q Plot
- Statistical Test Output

---

## 🎯 Skills Demonstrated

- Python Programming
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Hypothesis Testing
- Outlier Detection
- Business Insight Generation
- Data Storytelling

---

## 📚 Future Improvements

- Build regression models to predict taxi fares.
- Analyze additional features such as trip distance and trip duration.
- Develop an interactive dashboard using Power BI or Tableau.
- Compare multiple statistical testing techniques.
- Explore machine learning approaches for fare prediction.

---

## 👨‍💻 Author

**Kayoum Biswas**

- LinkedIn: *(Add your LinkedIn URL)*
- GitHub: *(Add your GitHub URL)*

---

## ⭐ If you found this project useful, consider giving it a star!
