# Titanic Survival Prediction

This is a simple machine learning project predicting passenger survival on the Titanic using Python and scikit-learn.

## Dataset

The dataset comes from the [Kaggle Titanic competition](https://www.kaggle.com/c/titanic/data), containing passenger information such as:

- `Pclass` – Passenger class
- `Sex` – Gender
- `Age` – Age in years
- `SibSp` – Number of siblings/spouses aboard
- `Parch` – Number of parents/children aboard
- `Fare` – Ticket fare
- `Embarked` – Port of embarkation
- `Survived` – Target variable (0 = No, 1 = Yes)

---

## Project Workflow

- **Data Preprocessing:** Handled missing values using statistical imputation, encoded categorical features with one-hot and label encoding, normalized numerical data, and engineered new features from raw data, including family size and title extraction.
- **Model Implementation:** Implemented multiple machine learning algorithms, including Logistic Regression and Random Forest to compare prediction performance and identify the most effective model.  
- **Hyperparameter Tuning:** Enhance model accuracy and prevent overfitting.  
- **Model Evaluation:** Evaluated models using various metrics, including accuracy and recall to provide a comprehensive assessment of performance.  



