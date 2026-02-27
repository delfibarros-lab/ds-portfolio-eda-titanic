# 🚢 Exploratory Data Analysis (EDA) - Titanic Dataset

## 📋 Context & Objective
This project is part of my Data Science portfolio. It consists of a comprehensive Exploratory Data Analysis (EDA) on the classic Titanic dataset. 
The main objective is not to create a predictive model just yet, but to demonstrate proficiency in data manipulation: understanding distributions, handling missing values, detecting survival patterns, and generating clear visual insights.

## 🛠️ Tools Used
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Seaborn, Matplotlib
- **Environment:** Google Colab / Jupyter Notebook

## 🚀 Methodology Applied
1. **Data Wrangling:** Identification and treatment of missing values (e.g., imputing missing `Age` values using the median).
2. **Univariate Analysis:** Understanding the distribution of individual features (fares, ages, passenger classes).
3. **Bivariate Analysis:** Exploring the relationship between independent variables and the target variable (`Survived`).
4. **Correlation Analysis:** Evaluating numerical variables to prevent multicollinearity in future modeling phases.

## 💡 Executive Conclusions
- **Gender:** Women had a significantly higher survival rate (approx. 74% vs. 19% for men).
- **Socioeconomic Status:** First-class passengers (Pclass 1) were given higher priority during the rescue operations.
- **Age:** Children (under 10 years old) show a distinct spike in survival rates, indicating that the "women and children first" maritime protocol was largely observed.
