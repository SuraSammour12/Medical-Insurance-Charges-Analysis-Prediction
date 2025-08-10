# 🏥💰 Medical Insurance Charges Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Regression-green)
![License: CC0](https://img.shields.io/badge/license-CC0-lightgrey)

---

**This project focuses on performing data analytics and predictive modeling on a medical insurance cost dataset.**  
The main objective is to analyze how personal attributes like age, BMI, smoking habits, and region influence insurance charges, and to develop regression models to predict these charges.

---

##  Project Objectives

- Load the dataset using Pandas.
- Clean and preprocess data (handle missing or blank entries).
- Perform Exploratory Data Analysis (EDA) to identify key influencing factors.
- Develop regression models:
  - Single Variable Linear Regression  
  - Multiple Variable Linear Regression  
  - Ridge Regression to address overfitting

---

##  Dataset Description

| Parameter        | Description                                       | Data Type     |
|------------------|---------------------------------------------------|---------------|
| `age`            | Age in years                                      | Integer       |
| `gender`         | Male or Female *(1: Female, 2: Male)*             | Integer       |
| `bmi`            | Body Mass Index                                   | Float         |
| `no_of_children` | Number of children                                | Integer       |
| `smoker`         | Smoking status *(0: Non-Smoker, 1: Smoker)*       | Integer       |
| `region`         | US Region *(1: NW, 2: NE, 3: SW, 4: SE)*          | Integer       |
| `charges`        | Annual Insurance Charges in USD *(Target)*        | Float         |

---

##  Technologies Used

- **Python**
- **Pandas & NumPy** → Data Manipulation
- **Matplotlib & Seaborn** → Data Visualization
- **Scikit-learn** → Regression Models (Linear & Ridge)
- **Jupyter Notebook** → Interactive Analysis

---

##  Project Structure

├── data/

│   └── medical_insurance_dataset.csv

├── notebooks/

│   └── Insurance_Cost_Analysis.ipynb

├── README.md

└── requirements.txt



---

## Expected Outcomes

- Understand how lifestyle and health metrics affect insurance charges.
- Identify high-impact features (e.g., BMI, smoking).
- Build accurate regression models for prediction.
- Apply Ridge Regression to improve generalization and mitigate overfitting.

---

## Insurance Charge Prediction for New Individuals

Using the trained **Polynomial Ridge Regression model**, the system can estimate insurance charges for unseen individuals based on their personal attributes.

| Person | Age | Gender | BMI  | Children | Smoker | Region     | Predicted Charge |
|--------|-----|--------|------|----------|--------|------------|------------------|
| 1      | 25  | Male   | 28.0 | 0        | No     | Southwest  | $3,758.35         |
| 2      | 52  | Female | 32.5 | 2        | Yes    | Northwest  | $39,728.76        |
| 3      | 43  | Male   | 30.1 | 1        | No     | Northeast  | $9,180.83         |

---

📒 [View the notebook](https://github.com/SuraSammour12/Medical-Insurance-Charges-Analysis-Prediction/blob/main/Insurance_Cost_Analysis.ipynb)

---

##  Useful Links

- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Dataset Source (Kaggle)](https://www.kaggle.com/)
- [Ridge Regression (scikit-learn)](https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression)
- [PolynomialFeatures (scikit-learn)](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.PolynomialFeatures.html)

---

##  License

This project is for educational purposes only and uses the dataset under public domain (CC0 1.0 Universal).
