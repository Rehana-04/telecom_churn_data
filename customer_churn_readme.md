# Customer Churn Analysis Project

## Project Overview
This project performs a complete analysis of customer churn using a telecom dataset. Customer churn refers to customers leaving a company or service. Predicting churn allows companies to take proactive measures to retain customers, improving customer satisfaction and revenue.

The project uses Python, pandas, scikit-learn, matplotlib, and seaborn for data analysis, preprocessing, machine learning, and visualization.

## Dataset
The dataset used for this project is the **Telco Customer Churn Dataset**. It contains 7,043 customer records and 21 features, including:
- Customer demographic information
- Account details
- Service subscriptions
- Billing and payment information
- Churn status (target variable)

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Project Structure
```
customer_churn_analysis/
│
├── telecom_churn_data.csv        # Dataset file
├── Customer_Churn_Analysis.ipynb # Jupyter Notebook with full analysis
├── customer_churn_model.pkl      # Trained Random Forest model
└── README.md                     # Project documentation
```

## Steps Performed
1. **Import Libraries**: Import essential libraries for data analysis, visualization, and machine learning.
2. **Load Dataset**: Read the CSV file and inspect the first few records.
3. **Data Exploration**: Examine dataset structure, missing values, and target variable distribution.
4. **Data Preprocessing**: Handle missing values, encode categorical variables, and define features and target.
5. **Split and Scale Data**: Split dataset into training and test sets, and standardize features.
6. **Train Random Forest Model**: Train a Random Forest Classifier to predict customer churn.
7. **Model Evaluation**: Evaluate model using accuracy, confusion matrix, classification report, and ROC-AUC score.
8. **Feature Importance**: Visualize the most important features affecting churn prediction.
9. **Save Model**: Save the trained model for future predictions.

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

Install required packages using:
```
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

## Usage
1. Open the Jupyter Notebook `Customer_Churn_Analysis.ipynb`.
2. Run each cell sequentially to perform the analysis.
3. Modify the dataset path if necessary.
4. The trained Random Forest model will be saved as `customer_churn_model.pkl`.

## Insights & Recommendations
- Customers with long tenure but high monthly charges are more likely to churn.
- Service usage patterns significantly affect churn.
- Companies can improve retention by offering personalized promotions, better customer support, and targeted marketing.

## Author
**Yash Raj**

## License
This project is open-source and free to use for educational and non-commercial purposes.

