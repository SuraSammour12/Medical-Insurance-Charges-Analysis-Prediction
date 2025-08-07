# 🏥💰 Medical Insurance Charges Analysis & Prediction
This project focuses on performing data analytics and predictive modeling on a medical insurance cost dataset. The main objective is to analyze how personal attributes like age, BMI, smoking habits, and region influence insurance charges, and to develop regression models to predict these charges.

# Project Objectives
Load the data as a Pandas DataFrame.

Clean the dataset and handle any missing or blank entries.

Perform Exploratory Data Analysis (EDA) to identify key factors affecting charges.

Develop:

Single Variable Linear Regression Model.

Multiple Variable Linear Regression Model.

Apply Ridge Regression to refine model performance and reduce overfitting.



# Dataset Description

| **Parameter**      | **Description**                                 | **Content Type**                       |
|--------------------|-------------------------------------------------|----------------------------------------|
| `age`               | Age in years                                    | Integer                                |
| `gender`            | Male or Female                                  | Integer (1 for Female, 2 for Male)     |
| `bmi`               | Body Mass Index                                 | Float                                  |
| `no_of_children`    | Number of children                              | Integer                                |
| `smoker`            | Whether smoker or not                           | Integer (0 for Non-Smoker, 1 for Smoker) |
| `region`            | US Region (NW, NE, SW, SE)                      | Integer (1: NW, 2: NE, 3: SW, 4: SE)   |
| `charges`           | Annual Insurance Charges in USD (Target Column) | Float                                  |

# Technologies Used
Python

Pandas & NumPy → Data Manipulation

Matplotlib & Seaborn → Data Visualization

Scikit-learn → Machine Learning Models (Linear & Ridge Regression)

Jupyter Notebook


# Project Structure
├── data/

│   └── medical_insurance_dataset.csv

├── notebooks/

│   └── Insurance_Cost_Analysis.ipynb

├── README.md

└── requirements.txt


#  Expected Outcomes
Identify key factors such as smoking habits and BMI that strongly influence insurance costs.

Build predictive regression models for estimating charges based on user attributes.

Demonstrate how Ridge Regression helps mitigate overfitting and enhances model generalization.

#  License
This project is for educational purposes only and uses a dataset under the CC0 1.0 Universal (Public Domain Dedication) License.

#  Summary
This project provides a practical understanding of how health-related factors influence medical insurance charges. It walks through real-world data cleaning, visualization, model building, and regularization techniques to build robust predictive models.

#  Useful Links
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Dataset Source](https://www.kaggle.com/)



