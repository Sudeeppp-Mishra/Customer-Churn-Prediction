# Customer Churn Prediction using Machine Learning

An end-to-end machine learning project that predicts whether a customer is likely to churn based on demographic information, subscription details, and billing history. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and model comparison.

---

## Project Objectives

- Understand customer churn behavior through data analysis.
- Perform data preprocessing and feature engineering.
- Train multiple machine learning classification models.
- Compare model performance using standard evaluation metrics.
- Identify the most influential factors contributing to customer churn.
- Build a reusable and reproducible machine learning pipeline.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer demographic information, account details, subscribed services, billing information, and whether the customer has churned.

### Target Variable

- **Churn**
  - Yes
  - No

---

## Machine Learning Pipeline

- Data Collection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Training
- Model Evaluation
- Model Comparison
- Feature Importance Analysis
- Model Serialization

---

## Machine Learning Models

The following classification algorithms will be implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

*Future Enhancements*

- XGBoost
- LightGBM
- CatBoost
- Hyperparameter Tuning
- SHAP Explainability

---

## Evaluation Metrics

Models will be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## Technologies Used

### Programming Language

- Python 3.x

### Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

### Development Environment

- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

---

## Project Structure

```bash
Customer-Churn-Prediction/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── notebooks/
│ └── customer_churn_prediction.ipynb
│
├── src/
│ ├── preprocessing.py
│ ├── feature_engineering.py
│ ├── train.py
│ ├── evaluate.py
│ └── utils.py
│
├── models/
│ └── best_model.pkl
│
├── reports/
│ ├── figures/
│ └── technical_report.pdf
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

## Exploratory Data Analysis

The project includes visualizations such as:

- Customer Churn Distribution
- Gender vs Churn
- Contract Type vs Churn
- Internet Service Analysis
- Monthly Charges Distribution
- Tenure Distribution
- Correlation Heatmap
- Boxplots
- Histograms
- Feature Importance

---

## Installation

Clone the repository

```bash
git clone git@github.com:Sudeeppp-Mishra/Customer-Churn-Prediction.git
```

Navigate into the project

```bash
cd Customer-Churn-Prediction
```

Create a virtual environment

```bash
python3 -m venv .venv
```

Activate the environment

_macOS/Linux_
```bash
source .venv/bin/activate
```

_Windows_
```powershell
.venv\Scripts\activate
```

Install dependencies
```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook
```bash
jupyter notebook
```

## Results

The final project will compare multiple classification models and identify the best-performing model for customer churn prediction using standard machine learning evaluation metrics.

## References

- IBM Telco Customer Churn Dataset
- Scikit-learn Documentation
- Pandas Documentation
- NumPy Documentation

## Links

- [GitHub Repository](https://github.com/Sudeeppp-Mishra/Customer-Churn-Prediction)
- [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- [Scikit-learn Documentation](https://scikit-learn.org/)

## Author

**Sudeep Mishra**

Computer Engineering Student

GitHub: [Sudeep Mishra](https://github.com/Sudeeppp-Mishra)