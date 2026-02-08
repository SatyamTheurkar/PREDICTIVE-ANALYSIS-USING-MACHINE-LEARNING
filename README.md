# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SATYAM THEURKAR

*INTERN ID* : CT06DF2424

*DOMAIN* : DATA ANALYTICS

*DURATION* : 6 WEEKS

*MENTOR* : NEELA SANTOSH

# Predictive Analysis using Machine Learning

## Overview

Predictive analysis applies machine learning techniques to analyze past data, identify relationships, and build models that anticipate future results. These predictions can relate to student performance, business needs, market trends, or other important variables impacting decision-making.
---

## Dataset

The dataset used in this project was sourced from **Kaggle** and represents various attributes such as:
- Gender
- Branch
- Clubs participation
- Internship status
- Attendance
- Backlogs
- CTC offered
- And more…

The dataset was uploaded to Google Drive and loaded directly into Google Colab using `pandas`.

---

## Objective

To build a machine learning model that can **predict the Average GPA** of students using a supervised learning approach, specifically:
- Data preprocessing
- Feature encoding and scaling
- Model training with Random Forest
- Evaluation using RMSE and R² score

---

## Key Steps

### 1. Data Preprocessing
- Dropped irrelevant or unneeded columns like `Student ID`, `Name`, `Placement Status`, etc.
- Removed rows with null values in critical fields.
- Used `LabelEncoder` to convert categorical variables into numeric values.
- Applied `StandardScaler` to normalize feature values.

### 2. Splitting the Data
- Used `train_test_split` to divide the dataset into training and testing sets with an 80-20 ratio.

### 3. Model Building
- Used `RandomForestRegressor` from `sklearn.ensemble` to fit the training data and make predictions on the test set.

### 4. Evaluation
- Evaluated model performance using:
  - **RMSE (Root Mean Squared Error)**
  - **R² Score (Coefficient of Determination)**

These metrics help determine the accuracy and reliability of the model for GPA prediction.

---

## Libraries Used

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

---

## How to Run

1. Clone this repository:
```bash
git clone https://github.com/yourusername/walmart-gpa-prediction.git
cd walmart-gpa-prediction
```

2. Upload the dataset (`students.csv`) to your Google Drive or local directory.

3. Open the Python script (`satyam_theurkar_task_2_predictive_analysis_using_machine_learning_.py`) in **Google Colab**.

4. Run the notebook cell-by-cell to see preprocessing, model training, and evaluation in action.

---

## Results

The model demonstrated predictive capabilities with metrics such as:
- **RMSE**: Lower RMSE indicates fewer errors in prediction.
- **R² Score**: Indicates how well features explain the variability in GPA.

You can tweak hyperparameters or try different algorithms (e.g., Gradient Boosting, XGBoost) for better performance.

---

## Author

**Satyam Theurkar**  
Project  
Predictive Analysis Using Machine Learning

---

## License

This project is licensed under the MIT License.
