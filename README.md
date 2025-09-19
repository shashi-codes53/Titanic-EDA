# 🚢 Titanic Survival Analysis – Exploratory Data Analysis (EDA)
## 📌 Project Overview
This project explores the **Titanic dataset**, one of the most famous datasets in data science.  
The goal is to uncover insights about **what factors influenced passenger survival** during the disaster.  

Through data cleaning, visualization, and feature engineering, this analysis highlights how **gender, class, age, cabin location, and family structure** impacted survival.

---

## 🔍 Key Insights
- **Gender** → Women had much higher survival rates than men.  
- **Passenger Class (Pclass)** → 1st class passengers had higher survival chances than 2nd and 3rd class.  
- **Embarked Port** → Passengers from port **C** survived slightly more than from **S** or **Q**.  
- **Cabin Deck** → Known decks (A–F) had higher survival; `"Unknown"` cabins showed lower survival.  
- **Family Size** → Small families (2–4 members) had higher survival, while passengers alone or in large families had lower survival.  
- **Fare** → Higher fares were associated with higher survival rates.  

---

## 📊 Visualizations
Some of the visualizations included:
- Survival distribution (baseline check)  
- Survival by **Sex, Pclass, Embarked, Cabin Deck**  
- Age and Fare distributions (KDE, Boxplot)  
- Heatmaps for **SibSp & Parch survival patterns**  
- Engineered feature: **FamilySize vs Survival**  

*(Plots are saved in the `plots/` folder and showcased in the notebook.)*

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** → data cleaning & manipulation  
- **Matplotlib, Seaborn** → visualizations  
- **Jupyter Notebook** → analysis workflow

## 📂 Repository Structure
