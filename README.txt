1. Project Overview

Title: Logistic Regression for Credit Default Prediction
Author: Marcel De Lange
Student ID: 577610
Date: 26-July-2024 - 28 July 2024

Description:
This project uses Logistic Regression to predict whether a credit card holder is likely to default on their payments. 
The analysis involves data preprocessing, exploratory data analysis (EDA), feature scaling, 
model training, and evaluation.

2. Dataset

Source:
The dataset is obtained from the UCI Machine Learning Repository: Credit Card Default Dataset

Features:

LIMIT: Amount of credit (in dollars)
SEX: Gender of the credit card holder (1 = male, 2 = female)
EDUCATION: Educational level (1 = graduate school, 2 = university, 3 = high school, 4 = other)
MARRIAGE: Marital status (1 = married, 2 = single, 3 = others)
AGE: Age of the credit card holder (in years)
PAY_0 to PAY_6: History of past payment (range: -1 to 9)
BILL_AMT1 to BILL_AMT6: Bill statement amount for the past 6 months
PAY_AMT1 to PAY_AMT6: Amount of previous payments for the past 6 months
default_payment_next_month: Target variable (1 = default, 0 = no default)
3. Requirements

Python Version: 3.x
Libraries:
pandas
matplotlib
seaborn
scikit-learn
4. Setup Instructions( only follow setup instructions if needed)

Clone the Repository :

bash
Copy code
git clone <repository_url>
Navigate to the Project Directory:

bash
Copy code
cd <project_directory>
Install Required Libraries:

bash
Copy code
pip install pandas matplotlib seaborn scikit-learn

5. How to Run the Code
Download the Dataset:

Place the dataset file (creditcard.ipynb (df).csv) in the project directory.
Execute the Script ( notebook in this case):

Run the Python script(notebook in this case) to perform the analysis:
bash
Copy code
python <script_name>.py

6. Analysis Details
Exploratory Data Analysis (EDA):

Box plots to visualize feature distributions.
Histograms to show the distribution of features.
Correlation heatmap to identify feature relationships.
Feature Scaling:

The AGE feature is scaled using StandardScaler.
Model Training and Evaluation:

Logistic Regression is used to predict default status.
Evaluation metrics include accuracy scores and ROC curves.
Prediction:

Example of predicting default status for a specific case.

7. Visuals
The following visuals are included in the project:

Box Plots
Scaled AGE Box Plot
Histograms
Correlation Matrix Heatmap
Training and Testing Data Evaluation Scatter Plots
ROC Curves
Note: Visuals are saved as PNG files in the project directory.

8. Results

Training Accuracy: [0.778125]

Testing Accuracy: [0.7811666666666667]

Example Prediction:

For a specific customer, the prediction is: [Predicted Default Status]
9. Contact
For questions or further information, please contact:

Email: [marceldelange20@gmail.com]

10. License
This project is licensed under the [Marcel De Lange] License - see the LICENSE file for details.