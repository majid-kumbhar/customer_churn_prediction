# Customer Churn Analysis and Prediction

This project focuses on **Customer Churn Analysis and Prediction** in the telecommunications industry. The goal is to help businesses identify high-risk customers likely to churn and take preemptive actions to retain them.

## 📊 Project Breakdown

### 1. Data Preparation
- Loaded and preprocessed the dataset.
- Handled missing values.
- Split the data into training and testing sets for model building.

### 2. Exploratory Data Analysis (EDA)
- Analyzed customer churn rates.
- Visualized customer demographics and key metrics to uncover trends.
  
### 3. Customer Segmentation
- Segmented customers based on:
  - Tenure
  - Monthly charges
  - Contract type
- Identified high-value customers who are at a higher risk of churning.

### 4. Churn Prediction Model
- Developed machine learning models using:
  - Logistic Regression
  - Decision Trees
- Predicted customer churn based on various customer attributes.

### 5. Model Evaluation and Interpretation
- Evaluated model performance with:
  - ROC Curves
  - Area Under the Curve (AUC)
- Interpreted important factors that influence customer churn.

## 🚀 Technologies Used
- Python
- Pandas, NumPy for data manipulation
- Matplotlib, Seaborn for EDA and visualization
- Scikit-learn for machine learning models

## 💻 How to Run the Project
1. Clone the repository:  
   ```bash
   git clone https://github.com/majid-kumbhar/customer_churn_prediction
   ```
2. Install the necessary libraries:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python scripts to see the analysis and results.

## 📂 Project Structure
```
├── data/               # Dataset used for the project
├── notebooks/          # Jupyter notebooks with code and analysis
├── models/             # Saved machine learning models
├── README.md           # Project documentation
└── requirements.txt    # Required Python packages
```
