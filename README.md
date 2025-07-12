# Week-3-Project-COVID-19-Data-Analysis
# 🦠 COVID-19 Global Data Analysis using Python

This project performs **Exploratory Data Analysis (EDA)** on real-world COVID-19 data using **Pandas**, **Matplotlib**, and **Seaborn**. It helps visualize the global spread, trends, and impact of COVID-19 across different countries.

## 📁 Dataset

Dataset Used: `covid_19_clean_complete.csv`  
Source: Kaggle 

Typical Columns:
- `Province/State`
- `Country/Region`
- `Lat`, `Long`
- `Date`
- `Confirmed`, `Deaths`, `Recovered`, `Active`
- `WHO Region`

## 🎯 Objective

- Understand the spread of COVID-19 over time and across countries.
- Identify top affected countries.
- Visualize trends in confirmed cases, deaths, and recoveries.
- Calculate and visualize the **death rate**.
- Focus on **India’s case growth**.

## 🧰 Tools & Libraries

- Python
- Google Colab / Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

## ✅ Steps Performed

### 1. Data Loading
- Loaded the dataset using `pandas.read_csv()`.

### 2. Data Cleaning
- Renamed columns for easier handling.
- Converted `Date` column to datetime format.
- Handled missing values (`NaN`) by dropping or filling.

### 3. Visualizations
- 📊 **Top 10 Countries by Confirmed Cases**
- 📈 **New Cases Over Time** (for India, US, Brazil, etc.)
- ⚰️ **Deaths vs. Recoveries** comparison
- 🇮🇳 **India’s COVID-19 Growth Curve**
- 📉 **Death Rate Calculation and Visualization**

## 📈 Sample Visualizations

- Horizontal bar charts for top countries
- Line charts for daily trends
- Death rate bar comparison


## 👩‍💻 Author

- **Name:** AFRIN SULTHANA M
- **Internship:** NSP NEXUS – Week 3
- **Project Title:** COVID-19 Data Analysis using Pandas and Matplotlib

