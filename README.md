# Task 5 — Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to identify patterns, trends, and relationships that may have influenced passenger survival.  
The analysis includes:
- Data inspection
- Cleaning and handling missing values
- Feature engineering
- Visual exploration
- Statistical testing
- A quick predictive model

---

## 📂 Files in This Repository
- **Task5_EDA_Titanic.ipynb** — Jupyter/Colab notebook with all steps and outputs
- **titanic_cleaned.csv** — Cleaned dataset after preprocessing
- **fig_*.png** — Visualizations generated during analysis
- **Task5_EDA_Report.pdf** — PDF report with figures, analysis, and insights
- **README.md** — This file

---

## 📊 Dataset
Dataset: Titanic (`train.csv`)  
Source: [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)  

**Columns:**
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

---

## 🛠 How to Run in Google Colab
1. Open the notebook in Google Colab:  
   [Open in Colab](https://colab.research.google.com/)
2. Upload your `train.csv` file using the file upload cell:
   ```python
   from google.colab import files
   uploaded = files.upload()
