# Bank Marketing ML Prediction

## Project Overview
This project predicts whether a client will subscribe to a term deposit based on a real-world **bank marketing dataset**. The dataset contains **45,000+ records** and demonstrates a full **end-to-end data science workflow**, including preprocessing, exploratory data analysis (EDA), machine learning model training, and evaluation.

## Dataset

- **Source:** UC Irvine Machine Learning Repository  
  [Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
- **Dataset used:** `zip.bank`  
- **Why this source is reliable:** UC Irvine Machine Learning Repository is a well-established academic platform widely used for research, teaching, and benchmarking machine learning models. The dataset is well-documented, peer-reviewed, and derived from real-world banking campaigns.  
- **Data collection method:** Data was collected through direct phone marketing campaigns conducted by a Portuguese bank, where clients were contacted to promote term deposit subscriptions.  
- **Licensing/availability:** Open-source and freely available for academic and research purposes.  

## Objective
Predict whether a client will subscribe to a term deposit (`yes` or `no`) using machine learning models.  

## My Contribution
- Conducted **data preprocessing**, including handling missing values, outliers, categorical encoding, and class imbalance.  
- Performed **Exploratory Data Analysis (EDA)** to identify patterns and key predictors such as call duration, previous contacts, and client demographics.  
- Trained and evaluated **three machine learning models**: Logistic Regression, Random Forest, and SVM.  
- Provided insights and **recommendations for marketing strategies** based on model findings.  

## Tools & Technologies
- Python, Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn
- Google Colab / Jupyter Notebook  

## Workflow
1. Data loading & preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering  
4. Model training & evaluation  
5. Results & insights  

## Model Evaluation Results

| Model              | Stage | Accuracy | Precision (Yes) | Recall (Yes) | F1-score (Yes) |
|-------------------|-------|---------|----------------|--------------|----------------|
| Logistic Regression | Raw   | 0.89    | 0.59           | 0.21         | 0.31           |
| Logistic Regression | Tuned | 0.88    | 0.51           | 0.40         | 0.44           |
| Random Forest       | Raw   | 0.90    | 0.60           | 0.35         | 0.44           |
| Random Forest       | Tuned | 0.87    | 0.46           | 0.72         | 0.56           |
| SVM                 | Final | 0.82    | -              | -            | -              |

> **Note:** Random Forest performed best overall for predicting positive subscriptions.  

## Summary of Findings
- Key predictors: **call duration**, **previous contacts**, and **client demographics**.  
- Data preprocessing improved model performance and addressed class imbalance.  
- Random Forest emerged as the most effective model for predicting term deposit subscriptions.  

## How to Run
1. Clone this repository  
2. Open the notebook in Google Colab or Jupyter Notebook  

