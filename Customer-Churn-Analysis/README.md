# 📊 Customer Churn Analysis using Python & SQLite

## 📌 Project Overview

This project demonstrates an end-to-end Customer Churn Analysis workflow using Python, SQLite, Pandas, and data visualization libraries.

The analysis starts with a raw Excel dataset, stores the data in a SQLite database, loads three relational tables into Pandas DataFrames, cleans and merges the data, performs exploratory data analysis (EDA), and generates business insights to understand customer churn behavior.

---

## 🎯 Objectives

- Import raw customer data from Excel.
- Store and access data using SQLite.
- Load relational tables into Pandas DataFrames.
- Clean and preprocess the data.
- Merge multiple datasets into a single analytical dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify customer churn patterns.
- Generate business recommendations.

---

# 📂 Dataset

This project uses two data sources.

### Raw Dataset

**customer_churn_data_raw.xlsx**

The original dataset containing customer, subscription, and support information.

### SQLite Database

**customer_churn.db**

The raw dataset was organized into three relational tables.

- db_customer
- db_subscription
- db_support

These tables were imported into Pandas and merged using the **customerid** column.

---

# 🔄 Project Workflow

```text
customer_churn_data_raw.xlsx
            │
            ▼
     SQLite Database
   (customer_churn.db)
            │
            ▼
      Load 3 Tables
            │
            ▼
 Create Pandas DataFrames
            │
            ▼
      Data Cleaning
            │
            ▼
 Merge Customer, Subscription
     and Support Data
            │
            ▼
   Feature Engineering
 (churn_flag, churn_risk)
            │
            ▼
 Exploratory Data Analysis
            │
            ▼
 Business Insights
```

---

# 🧹 Data Preparation

The following preprocessing steps were performed.

- Connected SQLite database using sqlite3
- Loaded all three database tables
- Converted tables into Pandas DataFrames
- Checked missing values
- Removed duplicate records
- Converted date columns into datetime format
- Merged all datasets using customerid
- Created churn_flag
- Created churn_risk categories

---

# 📈 Exploratory Data Analysis

The following analyses were performed.

- Monthly Churn Trend
- Churn Rate by Plan Type
- Churn Rate by State
- Correlation Heatmap
- Pairplot Analysis

---

# 📊 Visualizations

### Database Tables

![Database](images/creat_dataframes.png)

---

### Merge Three DataFrames

![Merge](images/merge_dataframe.png)

---

### Monthly Churn Trend

![Trend](images/monthly_churn.png)

---

### Churn by Plan Type

![Plan Type](images/plan_type.png)

---

### Churn by State

![State](images/state_churn.png)

---

### Correlation Heatmap

![Heatmap](images/heatmap.png)

---

### Pairplot

![Pairplot](images/pairplot.png)

---

# 💡 Key Insights

- Customers with higher churn scores are more likely to cancel.
- Customer support escalations are associated with increased churn risk.
- Contract type influences customer retention.
- Monthly churn trends help identify periods with higher customer loss.
- Correlation analysis highlights relationships among important customer attributes.

---

# 💼 Business Recommendations

- Improve customer support response time.
- Focus retention efforts on high-risk customers.
- Review subscription plans with higher churn.
- Monitor churn trends regularly.
- Improve customer satisfaction to reduce churn.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SQLite
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Project Structure

```text
Customer-Churn-Analysis/
│
├── customer_churn_data_raw.xlsx
├── customer_churn.db
├── Churn_Data_analysis.ipynb
├── report.pdf
├── README.md
├── requirements.txt
│
└── images/
    ├── creat_dataframes.png
    ├── merge_dataframe.png
    ├── monthly_churn.png
    ├── plan_type.png
    ├── state_churn.png
    ├── heatmap.png
    └── pairplot.png
```

---

# 🚀 Future Enhancements

- Build a Power BI dashboard
- Develop a Machine Learning churn prediction model
- Deploy the project using Streamlit
- Automate reporting with Python

---

# 👨‍💻 Author

Krishna Omprakash Yadav

Aspiring Data Analyst

📧 Email: krishnayadav5035@gmail.com

🔗 LinkedIn: www.linkedin.com/in/krishna-yadav-612445392

💻 GitHub: *https://github.com/your-username*

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!