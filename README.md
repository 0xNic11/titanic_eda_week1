# Titanic Exploratory Data Analysis (Week 1 Mini Project)

This repository contains my Week 1 Data Science & Machine Learning roadmap project: an Exploratory Data Analysis (EDA) of the Titanic dataset.  
The goal of this project is to understand demographic patterns, visualize key features, and explore survival differences across sex, class, and age groups.

---

## 📘 Project Overview

This project analyzes the classic Titanic dataset using Pandas and Matplotlib.  
It focuses on:

- Understanding passenger demographics  
- Visualizing distributions (Age, Fare, Class, Sex)  
- Exploring the relationship between features and survival outcomes  
- Creating engineered features such as **AgeGroup**  
- Summarizing key findings that will guide machine learning work in future weeks  

This EDA serves as the foundation for more advanced modeling tasks later in the roadmap.

---

## 📂 Repository Structure

titanic_eda_week1/
│
├── data/
│ └── train.csv
│
├── week1_titanic_eda
│
├── README.md
└── requirements.txt

**Notes:**
- The `data/` folder contains the Titanic dataset.
- The `notebooks/` folder contains all Jupyter notebooks used during Week 1.
- `titanic_week1_EDA_project.ipynb` is the final polished notebook ready for viewing.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**
- (Optional) Seaborn for visualization enhancements

---

## 📊 Key Insights

Some major findings from the analysis include:

- Adults make up most of the passenger population; children form a much smaller group.
- Fare values are highly right-skewed, indicating strong outliers.
- Females and first-class passengers had significantly higher survival rates.
- Children under 18 have distinct survival patterns compared to adults.
- Age and Cabin contain the most missing values, which must be handled for modeling.

A full summary is available inside the final notebook.

---

## 🚀 Next Steps

This project sets up future work in the ML roadmap, including:

- Feature engineering (Family size, Titles, Cabin sections)
- Handling missing values through imputation
- Model training (Logistic Regression, Random Forest, Gradient Boosting)
- Building a reproducible ML pipeline with Scikit-Learn

---

## 📝 Author

**Nicolas**  
Data Science & Machine Learning Engineer in training  
(Week 1 of 12)

---

## 📁 Instructions to View the Project

1. Clone or download this repository.
2. Open the `notebooks/` folder.
3. Launch Jupyter Notebook or Jupyter Lab.
4. Open `titanic_week1_EDA_project.ipynb`.

---

Thank you for viewing this project!