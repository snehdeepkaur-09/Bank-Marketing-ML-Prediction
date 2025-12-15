# 📊 Bank Marketing Campaign Prediction using Machine Learning

## 🚀 Project Overview

This project focuses on predicting whether a customer will subscribe to a **term deposit** following a bank marketing campaign. Using a **real-world dataset with 45,000+ records**, the project demonstrates a complete **end-to-end data science workflow**, including data preprocessing, exploratory data analysis (EDA), machine learning model development, evaluation, and insight generation.

The project was completed as a **group project**, with individual contributions clearly highlighted.

---

## 🧠 Problem Statement

Banks conduct large-scale marketing campaigns, but contacting every customer is inefficient and costly.  
The objective of this project is to:

- Predict customer subscription behaviour (`yes` / `no`)
- Identify key factors influencing subscription decisions
- Support **data-driven optimisation** of future marketing campaigns

---

## 📂 Dataset

- **Source:** UC Irvine Machine Learning Repository  
- **Dataset:** Bank Marketing Dataset (`zip.bank`)  
- **Link:** https://archive.ics.uci.edu/dataset/222/bank+marketing  
- **Size:** 45,000+ records  
- **Type:** Structured, tabular data  
- **Target Variable:** Term deposit subscription (`yes` / `no`)

### Why this dataset is reliable
The UC Irvine Machine Learning Repository is a trusted academic platform widely used for research, teaching, and benchmarking machine learning models. The dataset is well-documented, peer-reviewed, and derived from **real-world banking campaigns**.

### Data Collection Method
Data was collected through **direct phone marketing campaigns** conducted by a Portuguese bank to promote term deposit subscriptions.

### Licensing
The dataset is **open-source** and freely available for academic and research purposes.

---

## 🛠️ Tools & Technologies

- **Programming Language:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Data Visualisation:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  
- **Model Evaluation:** Accuracy, Precision, Recall, F1-score, Confusion Matrix  
- **Environment:** Google Colab / Jupyter Notebook  
- **Version Control:** Git & GitHub  

---

## 🔄 Methodology

### 1️⃣ Data Preprocessing
- Handled missing values and outliers  
- Encoded categorical variables  
- Scaled numerical features where required  
- Addressed class imbalance  
- Performed train-test split for unbiased evaluation  

### 2️⃣ Exploratory Data Analysis (EDA)
- Analysed customer demographics and campaign behaviour  
- Visualised distributions and feature relationships  
- Identified key predictors influencing subscription decisions  

### 3️⃣ Model Development
The following machine learning models were trained and evaluated:

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  

### 4️⃣ Model Evaluation
Models were evaluated using accuracy, precision, recall, and F1-score, with a strong focus on performance for the positive class (`yes`).

---

## 📈 Model Performance

| Model                | Stage  | Accuracy | Precision (Yes) | Recall (Yes) | F1-score (Yes) |
|---------------------|--------|----------|-----------------|--------------|----------------|
| Logistic Regression | Raw    | 0.89     | 0.59            | 0.21         | 0.31           |
| Logistic Regression | Tuned  | 0.88     | 0.51            | 0.40         | 0.44           |
| Random Forest       | Raw    | 0.90     | 0.60            | 0.35         | 0.44           |
| Random Forest       | Tuned  | 0.87     | 0.46            | 0.72         | 0.56           |
| SVM                 | Final  | 0.82     | -               | -            | -              |

✅ **Random Forest (tuned)** achieved the best overall balance between precision and recall for predicting subscriptions.

---

## 📊 Key Insights

- **Call duration**, **previous contacts**, and **client demographics** were among the strongest predictors of subscription.
- Addressing class imbalance significantly improved recall for positive subscriptions.
- Random Forest outperformed other models in capturing non-linear relationships in customer behaviour.

---

## 👩‍💻 My Individual Contribution

Although this was a **group project**, my key responsibilities included:

- Data cleaning and preprocessing using Pandas  
- Encoding categorical features and preparing data for ML models  
- Training and evaluating multiple machine learning models  
- Comparing model performance using appropriate evaluation metrics  
- Interpreting results and translating them into actionable business insights  

---

## 🌍 Real-World Relevance

This project mirrors real industry data science tasks involving:

- Large-scale datasets (45k+ records)  
- Predictive modelling  
- Business-focused decision support  

The skills demonstrated are directly applicable to **data science, analytics, finance, and marketing roles**, particularly **data and AI internships**.

---

## 🔮 Future Improvements

- Advanced hyperparameter tuning  
- Improved handling of class imbalance (SMOTE, class weighting)  
- Feature importance and model explainability (SHAP)  
- Deployment as an interactive dashboard or web application  

---

## 📫 Contact

**Snehdeep Kaur**  
BSc Computer Science with Artificial Intelligence  

- LinkedIn: https://www.linkedin.com/in/snehdeepkaur09  
- Portfolio: https://snehdeepkaur-portfolio.vercel.app  

---

⭐ *If you found this project interesting, feel free to star the repository!*
