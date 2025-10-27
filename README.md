# Titanic-EDA-project
Comprehensive Titanic dataset analysis with data cleaning, visualization, and correlation studies using Pandas, Matplotlib, and Seaborn.


# 🚢 Titanic Survival Analysis (EDA Project)

## 📘 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover key patterns influencing passenger survival during the tragedy.  
It involves **data cleaning, visualization, and statistical insights** using Python libraries such as Pandas, Matplotlib, and Seaborn.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib & Seaborn** – Data visualization  

---

## 📂 Dataset Information
- **Source:** Kaggle – Titanic: Machine Learning from Disaster  
- **Rows:** 891  
- **Columns:** 12  
- **Target Variable:** `Survived` (0 = No, 1 = Yes)

---

## 🔍 Key Steps
1. Data loading and structure inspection  
2. Handling missing values (`Age`, `Embarked`, `Cabin`)  
3. Statistical summary and value counts  
4. Data visualization:
   - Pair Plot
   - Correlation Heatmap
   - Boxplots
   - Scatterplots (Age vs Pclass, Fare vs Pclass)
5. Insights and summary of findings

---

## 📊 Key Insights
- **Higher class (1st class)** passengers had much higher survival rates.  
- **Females and younger passengers** were more likely to survive.  
- **Higher fare** correlated positively with survival.  
- **Cabin information** missing for most passengers, suggesting data recording bias.

---

## 📈 Visuals
- Pair Plot of numeric relationships  
- Correlation Heatmap  
- Boxplots (Age, Fare, SibSp, Parch)  
- Scatterplots by survival status  

---

## 🧠 Summary
The analysis highlights that **social class, gender, and fare price** were strong indicators of survival likelihood on the Titanic.  
This dataset demonstrates how demographic and socioeconomic factors can influence survival outcomes during disasters.
