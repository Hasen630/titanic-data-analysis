# 🚢 Titanic Data Analysis

## 📌 Overview
This project performs data analysis on the Titanic dataset using Python and pandas.

It includes:
- Data exploration
- Data cleaning
- Data analysis using groupby
- Filtering specific groups
- Insights from the data

---

## 📁 Project Structure
titanic-data-analysis/
│
├── notebook/
│ └── titanic_analysis_kaggle.ipynb
│
├── src/
│ └── titanic_analysis.py
│
├── README.md
└── requirements.txt

---

## ⚙️ Technologies Used
- Python
- pandas

---

## 📊 Analysis Performed

### Data Cleaning
- Filled missing values:
  - Age → median
  - Embarked → mode
- Dropped Cabin column
- Removed duplicates

### Data Analysis
- Survival rate by gender
- Survival rate by class
- Average age per class
- Survival rate by age group

### Filtering
- Female survivors
- Child survivors
- First-class survivors

---

## 🔥 Key Insights

- Females had higher survival rates than males
- First-class passengers were more likely to survive
- Children had higher survival rates
- Highest survival group: Female passengers in 1st class

---

## 📂 Dataset
The dataset is sourced from Kaggle Titanic competition.

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python src/titanic_analysis.py
👤 Author

[Hasen Ahmed]

