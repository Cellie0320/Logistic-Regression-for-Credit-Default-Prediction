# Credit Card Default Prediction

This project aims to predict whether a credit card holder will default on their payment next month using various features related to their credit history and personal information.

## Features:  

- `LIMIT`: Amount of credit (in dollars)
- `SEX`: Gender of the credit card holder (1 = male, 2 = female)
- `EDUCATION`: Educational level (1 = graduate school, 2 = university, 3 = high school, 4 = other)
- `MARRIAGE`: Marital status (1 = married, 2 = single, 3 = others)
- `AGE`: Age of the credit card holder (in years)
- `PAY_0` to `PAY_6`: History of past payment (range: -1 to 9)
- `BILL_AMT1` to `BILL_AMT6`: Bill statement amount for the past 6 months
- `PAY_AMT1` to `PAY_AMT6`: Amount of previous payments for the past 6 months
- `default_payment_next_month`: Target variable (1 = default, 0 = no default)

## Requirements

- **Python Version:** 3.x
- **Libraries:**
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

## Setup Instructions

1. **Clone the Repository:**

    ```bash
    git clone <repository_url>
    ```

2. **Navigate to the Project Directory:**

    ```bash
    cd <project_directory>
    ```

3. **Install the Required Libraries:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

## Usage

Open the Jupyter Notebook and follow the instructions to load the data, preprocess it, and train the model. The notebook includes sections for exploratory data analysis, feature engineering, model training, and evaluation.

## Contributing

Feel free to submit issues or pull requests if you have any suggestions or improvements.

## License

This project is licensed under the Apache License 2.0