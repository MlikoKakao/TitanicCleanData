# Titanic Survival Analysis 🛳

This project contains a cleaned version of the Titanic dataset and a Jupyter notebook with analysis and visualizations of survival rates, age distribution, and fare data.

## 📁 Files Included

- `cleaned_titanic.csv`: Cleaned Titanic dataset (missing values handled, irrelevant columns removed).
- `titanic-1mk.ipynb`: Jupyter notebook with:
  - Data cleaning steps
  - Exploratory Data Analysis (EDA)
  - Basic statistical summaries

## 🧼 Cleaning Steps

- Filled missing `Age` values with the median.
- Filled missing `Embarked` with the mode.
- Removed `Cabin`, `Ticket`, and `Name` columns.
- Converted categorical variables (`Sex`, `Embarked`) into numeric.
- Added new feature: `FamilySize = SibSp + Parch`.

## 📊 Key Insights

- Survival rate differs strongly between genders and age groups.
- Fare prices vary widely, especially among survivors.
- Male passengers had a significantly lower survival rate.

## ▶️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/titanic-analysis.git
   cd titanic-analysis
