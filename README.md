# Sonar Rock vs Mine Prediction using Logistic Regression Model
This project demonstrates how to build a binary classification model using Logistic Regression to differentiate between sonar signals bounced off rocks and metal cylinders (mines). The dataset used is the Sonar Dataset from the UCI Machine Learning Repository.

# Problem Statement
Given 60 sonar frequency attributes, predict whether the object is a rock (R) or a mine (M). This has practical applications in undersea object detection using sonar signals.

# Dataset
Source: UCI Machine Learning Repository

Attributes: 60 numerical features (energy levels in various frequency bands)

Target:

R → Rock

M → Mine

# Technologies Used
Python

NumPy, Pandas

Scikit-learn

Logistic Regression

Google Colab

# Project Structure
Copy
Edit
├── Sonar_Rock_vs_Mine_Prediction_using_Logistic_Regression.ipynb
├── README.md

# Model Building Process
Data Loading

Exploratory Data Analysis (EDA)

Preprocessing

Encoding labels (R and M)

Train-test split

Standardization

Model Training

Logistic Regression

Evaluation

Accuracy score

Predictions on new input

# How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/sonar-rock-vs-mine-logistic.git
cd sonar-rock-vs-mine-logistic
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook:

bash
Copy
Edit
jupyter notebook Sonar_Rock_vs_Mine_Prediction_using_Logistic_Regression.ipynb
# Model Accuracy
The Logistic Regression model provides reliable performance for this binary classification task, demonstrating effective generalization on test data.

# Sample Prediction
The notebook includes a section where you can input new sonar values to predict if the object is a rock or mine.

# References
UCI Sonar Dataset

Scikit-learn Logistic Regression Docs

# Author
Hasrat Hussain
Data Scientist & Developer
