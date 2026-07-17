# Customer Churn Prediction using Machine Learning

## Overview

Customer Churn Prediction is a machine learning project that predicts whether a customer is likely to discontinue a company's service based on customer information and usage patterns.

This project uses a **Random Forest Classifier** to analyze customer data and classify customers into two categories:

- **Churn = Yes** (Customer is likely to leave)
- **Churn = No** (Customer is likely to stay)

The project includes data preprocessing, feature engineering, model training, evaluation, and prediction on new customer data.

---

## Project Objective

The primary objective of this project is to build a machine learning model that can identify customers who are at risk of leaving the company. Early prediction enables businesses to improve customer retention through targeted marketing and customer support strategies.

---

## Features

- Customer data preprocessing
- Missing value handling
- Label Encoding for categorical variables
- Feature Scaling using StandardScaler
- Train-Test Split
- Random Forest Classification
- Model Evaluation
- Accuracy Score
- Classification Report
- Confusion Matrix
- Predict new customer churn
- Save trained model for future use

---

## Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Structure

```
Customer_Churn_Project/
│
├── customer_churn_dataset.csv
├── train_model.ipynb
├── train_model.py
├── prediction.py
├── saved_model.pkl
├── scaler.pkl
├── label_encoder.pkl
├── requirements.txt
├── README.md
└── images/
```

---

## Dataset Information

The dataset contains customer-related information used for churn prediction.

### Features

| Feature | Description |
|----------|-------------|
| Age | Customer age |
| MonthlyIncome | Monthly income |
| Tenure | Number of years as a customer |
| SupportCalls | Number of customer support calls |
| Churn | Target variable (Yes/No) |

---

## Machine Learning Workflow

```
Customer Dataset
        │
        ▼
Load Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Handle Missing Values
        │
        ▼
Encode Categorical Features
        │
        ▼
Split Training & Testing Data
        │
        ▼
Feature Scaling
        │
        ▼
Train Random Forest Model
        │
        ▼
Model Evaluation
        │
        ▼
Predict Customer Churn
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Move into the project directory

```bash
cd customer-churn-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Train the machine learning model

```bash
python train_model.py
```

Run prediction

```bash
python prediction.py
```

Or open

```
train_model.ipynb
```

inside Jupyter Notebook or Google Colab.

---

## Model Used

**Random Forest Classifier**

Reasons for choosing Random Forest:

- High accuracy
- Handles both numerical and categorical data
- Reduces overfitting
- Robust and reliable
- Works well on structured datasets

---

## Model Performance

Example Results

```
Accuracy : 0.86
```

Classification Report

```
Precision : 0.87
Recall    : 0.85
F1 Score  : 0.86
```

> **Note:** The exact accuracy may vary depending on the dataset and train-test split.

---

## Example Prediction

Input

```
Age = 34
MonthlyIncome = 55000
Tenure = 6
SupportCalls = 1
```

Output

```
Customer will Stay
```

Another Example

```
Age = 25
MonthlyIncome = 22000
Tenure = 1
SupportCalls = 5
```

Output

```
Customer will Churn
```

---

## Applications

This project can be applied in:

- Banking
- Telecommunications
- Insurance
- E-commerce
- Subscription Services
- Online Streaming Platforms
- Retail Business

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Model deployment using Flask or FastAPI
- Web application integration
- Real-time prediction API
- Google Cloud Vertex AI deployment
- Docker containerization

---

## Requirements

```
Python 3.10+

pandas
numpy
scikit-learn
joblib
matplotlib
seaborn
jupyter
```

Install all packages

```bash
pip install -r requirements.txt
```

---

## Learning Outcomes

Through this project, you will learn:

- Data preprocessing
- Feature engineering
- Label encoding
- Feature scaling
- Model training
- Classification algorithms
- Model evaluation
- Machine learning workflow
- Customer churn analysis
- Prediction using trained models

---

## License

This project is developed for educational and learning purposes.

---

## Author

**Sangeetha**

Bachelor of Computer Applications (BCA)

Machine Learning | Artificial Intelligence | Full Stack Development

GitHub: https://github.com/SangeethaSundararajan

---

## Acknowledgements

- Scikit-learn
- Pandas
- NumPy
- Python Community
- Jupyter Notebook
