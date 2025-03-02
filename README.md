Titanic Survival Prediction

Overview

This project predicts the survival chances of passengers on the Titanic using machine learning. The dataset includes details such as age, gender, ticket class, and fare amount.

Dataset

Source: Kaggle Titanic Dataset

Features Used:

Pclass (Passenger class)

Age

SibSp (Number of siblings/spouses aboard)

Parch (Number of parents/children aboard)

Fare

Sex (Encoded as Male/Female)

Embarked (Port of Embarkation: C, Q, S)

Preprocessing

Handled missing values (imputation)

Encoded categorical variables

Scaled numerical features using MinMaxScaler

Split data into training and testing sets

Model Used

Algorithm: k-Nearest Neighbors (k-NN)

Hyperparameter Tuning: Used GridSearchCV to find the best value of 'k'

Evaluation Metrics: Accuracy, Confusion Matrix

Results

Kaggle Score: 0.7775

Files Included

Titanic_Survival_Prediction.ipynb: Jupyter notebook with full implementation

submission.csv: Final predictions for test data

README.md: Project documentation

How to Run

Clone the repository:

git clone https://github.com/saibalaharini20/Titanic-Survival-Prediction.git

Open Titanic_Survival_Prediction.ipynb in Jupyter Notebook or Google Colab

Run all the cells to preprocess data, train the model, and generate predictions

Contribution

Feel free to fork this repository and contribute by improving the model or adding new insights!

Author

Sai Bala HariniGitHub ProfileKaggle Profile

