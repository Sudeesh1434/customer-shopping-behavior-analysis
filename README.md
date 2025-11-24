# 📊 Data Analytics Project – End-to-End Analysis

## ⭐ Overview
This project demonstrates a complete Data Analytics workflow using **Python**, **MySQL**, and **Power BI**.  
The goal is to analyze customer shopping behavior, understand spending patterns, and derive insights to support business decisions.

The project covers:
- Loading and exploring the dataset  
- Cleaning and preparing the data  
- Performing EDA  
- Running SQL queries for deeper insights  
- Building an interactive Power BI dashboard  
- Summarizing results and conclusions  


## 📂 Dataset
**Name:** customer_shopping_behavior.csv  
**Description:**  
Includes customer demographics, product category, purchase amount, payment method, review ratings, and transaction details.  
Used to study buying behavior and revenue trends.


## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data loading, cleaning, and EDA |
| **MySQL** | SQL queries for analysis |
| **Power BI** | Dashboard creation |
| **Jupyter Notebook** | Python development |
| **GitHub** | Project hosting |


## 🧾 Project Steps

### **1️⃣ Load Dataset in Python**
- Imported CSV using Pandas  
- Checked data types, missing values, and basic structure  

### **2️⃣ Data Cleaning**
- Removed duplicates  
- Handled missing values  
- Normalized column names  
- Converted date formats  
- Exported cleaned dataset for MySQL and Power BI  

### **3️⃣ Exploratory Data Analysis (EDA)**
Performed:
- Univariate analysis  
- Category-wise and gender-wise trends  
- Revenue trends  
- Visualizations using Matplotlib & Seaborn  

### **4️⃣ SQL Analysis (MySQL)**
Key queries performed:
- Total sales  
- Best performing categories  
- Top revenue-generating locations  
- Most frequently used payment methods  
- High-value customers  
- Monthly purchasing trends  

### **5️⃣ Power BI Dashboard**
Dashboard includes:
- Total Revenue  
- Category Sales  
- Payment Method Share  
- Customer Demographics  
- Monthly Revenue Trend  
- Top Cities by Sales  


## 📊 Final Results (Insights)
- **Electronics & Clothing** generated the highest revenue.  
- Customers aged **25–40** purchased the most.  
- **Digital Wallet** was the most preferred payment method.  
- Sales saw a significant increase during **festive months**.  
- **Metro cities** contributed the majority of revenue.  


## 🧠 Conclusion
The analysis shows that the business should:
- Focus marketing on the **25–40 age group**  
- Increase inventory in top-performing categories  
- Promote **digital payments** through offers  
- Strengthen presence in high-revenue cities  
- Plan campaigns around seasonal spikes  

These insights can help improve sales strategy and customer engagement.


## ▶️ How to Run This Project

### **1. Clone the Repository**
bash
git clone https://github.com/your-username/your-repo-name.git


### **2. Run Python Notebook**
- Open Jupyter Notebook  
- Run the EDA notebook (EDA.ipynb)  
- Output will generate a cleaned CSV  

### **3. Import Data into MySQL**
- Create a database  
- Load the cleaned CSV  
- Run the SQL queries from queries.sql 

### **4. Open Power BI Dashboard**
- Open .pbix file  
- Load cleaned dataset  
- Refresh visuals  


## 📁 Folder Structure
project/
│── data/
│   └── customer_shopping_behavior.csv
│   └── cleaned_data.csv
│── notebooks/
│   └── EDA.ipynb
│── sql/
│   └── queries.sql
│── dashboard/
│   └── report.pbix
│── README.md
