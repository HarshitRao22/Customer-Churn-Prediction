# Customer Churn Prediction and Customer Segmentation
<p align="center">
  <img src="Images/banner.png" width="900">
</p>

<p align="center">
Machine Learning • Customer Churn Prediction • Customer Segmentation • Random Forest • Scikit-learn
</p>
 Overview

This project predicts whether a customer is likely to churn using Machine Learning and also segments customers into different groups based on their behavior. The project covers the complete ML workflow from data preprocessing and visualization to model training, evaluation, and customer segmentation.

---

## Objectives

- Predict customer churn using Machine Learning.
- Identify customers who are likely to leave.
- Segment customers into different groups for better business understanding.
- Compare different models and improve performance using hyperparameter tuning.

---

## Dataset

The dataset contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Label

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Handled missing values
- Encoded categorical features
- Feature scaling
- Train-Test Split

---

## Exploratory Data Analysis (EDA)

Some of the visualizations used in this project include:

- Customer Churn Distribution
- Contract Type vs Churn
- Monthly Charges Distribution
- Tenure Distribution
- Churn vs Tenure Box Plot

These graphs helped in understanding customer behavior before training the models.

---

## Machine Learning Models

The following classification models were trained and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Random Forest was further improved using **GridSearchCV** for hyperparameter tuning.

---

## Model Performance

### Final Model
**Random Forest (GridSearchCV)**

| Metric | Score |
|--------|-------|
| Accuracy | **72.89%** |
| Recall | **84%** |
| Precision | **51%** |
| F1-Score | **64%** |
| Precision-Recall AUC | **0.66** |

The final model was optimized to improve recall so that more customers who are likely to churn can be identified.

---

## Customer Segmentation

K-Means Clustering was used for customer segmentation.

The Elbow Method was used to determine the optimal number of clusters.

The final customer segments include:

- Budget Loyal Customers
- High Value Customers
- High Risk New Customers

These segments can help businesses create targeted marketing and customer retention strategies.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Results

- Built a complete customer churn prediction pipeline.
- Compared multiple Machine Learning models.
- Improved Random Forest using GridSearchCV.
- Achieved **84% recall**, making the model effective for identifying customers who are likely to churn.
- Performed customer segmentation using K-Means clustering.

---

## Future Improvements

- Try XGBoost and LightGBM.
- Deploy the model using Streamlit or Flask.
- Use more advanced feature engineering techniques.
- Improve model performance using ensemble methods.
