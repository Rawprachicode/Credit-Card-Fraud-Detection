# Credit-Card-Fraud-Detection

Credit Card Fraud Detection:

This project aims to develop a machine learning model for the detection of credit card fraud using Python and scikit-learn. Credit card fraud is a significant concern for financial institutions, and the goal is to build a reliable model to identify fraudulent transactions.

**Dataset**
The dataset used for this project is available on Kaggle: Credit Card Fraud Detection. It contains credit card transactions made by European cardholders, with features such as transaction amount, time, and various anonymized features. The target variable is 'Class,' where '0' represents a legitimate transaction, and '1' represents a fraudulent transaction.

**Setup**

**1. Requirements:**

Python 3.x
pandas
scikit-learn
imbalanced-learn (for SMOTE)
Jupyter Notebook (optional for running the code interactively)

**2. Clone the Repository:**
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection


**3. Install Dependencies:**
pip install -r requirements.txt

**Usage**

**1. Data Exploration:**

Explore the dataset, check for missing values, and analyze the distribution of legitimate and fraudulent transactions.

**2. Model Building:**

Two methods are provided for handling class imbalance:
SMOTE (Synthetic Minority Over-sampling Technique):
Use SMOTE to balance the dataset by oversampling the minority class.
Train a logistic regression model on the balanced dataset.

Undersampling (Alternative Method):
Build a sample dataset containing a similar distribution of normal and fraudulent transactions.
Train a logistic regression model on the undersampled dataset.

**3. Model Evaluation:**

Evaluate the model's performance using accuracy metrics on both training and testing data.
Make sure to choose the appropriate method for handling class imbalance.


**Credits**
Dataset: Credit Card Fraud Detection
scikit-learn
imbalanced-learn


**Contributing**
Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.



