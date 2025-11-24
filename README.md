# 📊 Data Analytics Project – End-to-End Analysis

## ⭐ Overview
This project demonstrates a complete Data Analytics workflow using Python, MySQL, and Power BI. It includes loading a dataset, performing Exploratory Data Analysis (EDA), cleaning and preparing the data, running SQL queries, and building an interactive Power BI dashboard. The aim is to analyze business patterns and present clear and actionable insights.


## 📂 Dataset
- **Name:** customer_shopping_behavior.csv
- **Description:** Contains customer demographic details, purchase information, product categories, payment methods, and transaction data.
- **Purpose:** To analyze customer shopping patterns and understand revenue trends.


## 🛠️ Tools & Technologies
| Tool | Usage |
|------|-------|
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data loading, cleaning, EDA |
| **MySQL** | SQL queries and insights extraction |
| **Power BI** | Dashboard creation |
| **Jupyter Notebook** | Analysis environment |
| **GitHub** | Version control and project hosting |


## 🧾 Project Steps

### **1️⃣ Load Dataset in Python**
- Imported dataset using Pandas  
- Checked data types and missing values  
- Viewed summary statistics  

### **2️⃣ Exploratory Data Analysis (EDA)**
- Univariate and bivariate analysis  
- Visualizations using Matplotlib & Seaborn  
- Identified trends in categories, demographics, and revenue  

### **3️⃣ Data Cleaning**
- Removed duplicates  
- Filled/handled missing values  
- Standardized column names  
- Converted date columns properly  
- Exported cleaned dataset  

### **4️⃣ SQL Analysis (MySQL)**
Insights generated using SQL:  
- Total sales  
- Best-selling categories  
- High-value customers  
- Payment method usage  
- Monthly and regional trends  

### **5️⃣ Power BI Dashboard**
Dashboard includes:  
- Total Revenue  
- Category-wise Sales  
- Customer Demographics  
- Payment Method Distribution  
- Monthly Sales Trend  
- Top Performing Cities  

### **6️⃣ Final Insights / Results**
- Electronics & Clothing were top revenue-generating categories  
- Ages 25–40 formed the most active customer segment  
- Digital payments showed increasing trend  
- Certain cities contributed the highest revenue  
- Clear seasonality patterns observed in purchases  


## ▶️ How to Run This Project

### **1. Clone the Repository**
bash
git clone https://github.com/your-username/your-repo-name.git


### **2. Run Python Notebook**
- Open Jupyter Notebook  
- Run EDA and cleaning cells  
- Export cleaned CSV  

### **3. Use MySQL**
- Create a database  
- Load cleaned CSV  
- Run the SQL queries  

### **4. Open Power BI File**
- Load the cleaned dataset  
- Refresh visuals  
- Explore dashboard  


## 📁 Folder Structure

project-folder/
│── data/
│   └── customer_shopping_behavior.csv
│── notebooks/
│   └── EDA.ipynb
│── sql/
│   └── queries.sql
│── dashboard/
│   └── shopping_dashboard.pbix
│── README.md
