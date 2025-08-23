# 🛒 E-Commerce Data Analysis Project

This project is a complete data analytics pipeline built to analyze a Brazilian E-commerce dataset. It demonstrates a full workflow from data ingestion and cleaning to analysis and interactive visualization, using **MySQL**, **Python (Pandas, SQLAlchemy)**, and **Power BI**.

---
##  briefcase Key Business Questions
This project was designed to answer critical, industry-level questions that drive business strategy:
* Who are our most valuable customers?
* What are our key seasonal sales trends?
* What are the preferred payment methods of our customers?
* Where are the key inefficiencies in our delivery process?

---
## 🎯 At a Glance: Key Results
The analysis uncovered several key performance indicators:

| KPI | Result |
| :-------------------------------------- | :-----------------: |
| Revenue from Top 10% of Customers | **47.17%** |
| Highest Sales Quarter | **Q2** |
| Transactions via Credit Card | **73.81%** |

---
## 🔄 Project Workflow
The project follows a standard data analytics workflow, moving from raw data to actionable insights.

1.  **Database Creation:** A relational schema was designed and created in **MySQL** to structure the raw data from multiple CSV files.
2.  **Data Cleaning & ETL:** A **Python** script using **Pandas** and **SQLAlchemy** was developed to connect to the database, clean inconsistencies, handle missing values, and merge the tables into a final, analysis-ready dataset.
3.  **Dashboard Visualization:** The cleaned data was connected to **Power BI** to build a multi-page, interactive dashboard for visual analysis and insight generation.

---
## 📊 Power BI Dashboard Preview
The final dashboard provides a comprehensive overview of sales, customer behavior, and delivery performance.

### Page 1: Sales Overview
![Sales Overview](Page1.png)

### Page 2: Customer Analysis
![Customer Analysis](Page2.png)

### Page 3: Product & Delivery Insights
![Product & Delivery Insights](Page3.png)

---
## 💡 Key Insights Uncovered

* **Loyal Customers:** The top 10% of customers contribute to nearly half (47.17%) of total revenue, highlighting the importance of customer retention and loyalty programs.
* **Sales Peaks:** Sales show a significant peak in the second quarter (Q2), suggesting opportunities for mid-year marketing campaigns.
* **Payment Methods:** Credit cards are the dominant payment method, used in almost three-quarters of all purchases.
* **Delivery Delays:** Analysis shows that delivery delays are most commonly linked to specific geographic regions, pointing to logistical bottlenecks.

---
## 🛠️ Tools & Technologies
* **Database:** MySQL ``
* **Data Processing:** Python `

[Image of Python logo]
` (with Pandas `` & SQLAlchemy)
* **Visualization:** Power BI ``
* **Environment:** Jupyter Notebook ``

---
## 🚀 How to Run This Project

1.  **Setup MySQL Database:**
    * Create the database and tables using the `Table Creation.sql` script.
    * Import the raw CSV data using the `Table Import.sql` script.

2.  **Run Python ETL Script:**
    * Install necessary libraries: `pip install pandas sqlalchemy pymysql`
    * Run the `E_commerce_project_sqlalchemy.ipynb` notebook to clean the data and save it to a new table.

3.  **View Dashboard:**
    * Open the `E_commerce_project.pbix` file in Power BI Desktop.
    * Connect the dashboard to your local MySQL database and refresh the data source.

---
## 📜 License
This project is licensed under the MIT License.
