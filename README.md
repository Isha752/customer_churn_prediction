# 📉 Customer Churn Prediction

This project aims to build a machine learning model that predicts whether a customer is likely to churn, based on behavior and demographic data.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Handled missing values and encoded categorical variables.
   - Standardized and scaled features.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed trends between churn and variables like contract type, tenure, and monthly charges.
   - Used visualizations to understand feature relationships.

3. **Model Building**
   - Logistic Regression
   - Evaluated with confusion matrix, accuracy score, and precision-recall metrics.

4. **Results**
   - Achieved ~85% accuracy.
   - Reduced false positives by 10%.
   - Identified top 15% at-risk customers.

---

## 📁 Project Structure

customer_churn_prediction/
├── data/
│ └── churn_data.csv
├── churn_model.ipynb
├── model.pkl
├── visuals/
│ └── churn_heatmap.png
└── README.md


---

## 🔍 Key Insights

- Long-term customers on month-to-month contracts were more likely to churn.
- High monthly charges had a strong positive correlation with churn probability.
- Paperless billing and tech support options influenced retention.

---

## 📌 Note

This project is built for learning and demonstration purposes. Business-focused deployment would include further optimization, A/B testing, and integration with CRM systems.

