# 🛳 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Overview
This project is part of **Task 5 - Data Analyst Internship**.  
The objective is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to find trends, patterns, and anomalies.

Dataset Source: [Titanic Dataset (GitHub link)](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 📂 Files in this Repository
- `Titanic_EDA.ipynb` → Jupyter/Colab notebook with full EDA code.
- `Titanic_EDA.pdf` → PDF version of the notebook for submission.
- `train.csv` → Titanic dataset used for analysis.
- `README.md` → This file.

---

## 🛠 Tools & Libraries Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Steps Performed
1. **Data Loading & Inspection**
   - Loaded dataset and checked dimensions, data types, and missing values.
   
2. **Data Cleaning**
   - Filled missing `Age` with median value.
   - Filled missing `Embarked` with most frequent value.
   - Dropped `Cabin` column due to too many missing values.

3. **Univariate Analysis**
   - Plotted distributions of Age, Passenger Class, Gender, and Survival.

4. **Bivariate Analysis**
   - Survival rate by gender.
   - Survival rate by passenger class.
   - Age distribution for survivors vs non-survivors.

5. **Correlation Analysis**
   - Correlation heatmap.
   - Pairplots for selected numerical variables.

6. **Observations & Insights**
   - Women had a higher survival rate than men.
   - Passengers in **Pclass 1** had better survival chances.
   - Younger passengers tended to survive more.
   - Higher ticket fares were associated with higher survival rates.

---

 📈 Example Visuals
- **Survival Count Plot
- **Age Distribution Histogram
- **Class vs Survival Rate Bar Chart
- **Correlation Heatmap
- **Pairplot for Numerical Variables





