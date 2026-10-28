# 🚗 Car Sales Analysis Using Python, SQL, and Power BI

This repository contains a **comprehensive analysis of car sales data** using **Python**, **SQL**, and **Power BI**. The goal is to uncover **actionable insights** into sales trends, dealer performance, and customer demographics, enabling **strategic, data-driven decisions**.

---

## 📊 Project Overview

This end-to-end data analytics project involves:

1. **🔍 Data Cleaning & Analysis** (Python)
   - Preprocessed and cleaned raw sales data using Pandas and NumPy.
   - Handled missing values, duplicates, and performed data type conversions.
   - Conducted exploratory data analysis (EDA) to identify trends and patterns.

2. **📄 SQL Data Querying**
   - Ran SQL queries for KPIs like total sales, average car price, and top-performing dealers.
   - Used joins, aggregations, and filters to derive key business metrics.
   - Segmented customers by region, gender, and income.

3. **📈 Power BI Dashboarding**
   - Built **interactive dashboards** to visualize:
     - Revenue by region
     - Sales by brand/model
     - Dealer performance
     - Customer demographics
   - Designed dynamic reports for business decision-makers.

---

## 📦 Dataset Description

The dataset contains rich information about car sales. Key fields include:

| Field            | Description                                   |
|------------------|-----------------------------------------------|
| `car_id`         | Unique identifier for each car                |
| `Date`           | Date of sale                                  |
| `Customer Name`  | Name of the customer                          |
| `Gender`         | Gender of the customer                        |
| `Annual Income`  | Annual income of the customer                 |
| `Dealer_Name`    | Name of the dealer                            |
| `Company`        | Car manufacturer                              |
| `Model`          | Car model                                     |
| `Engine`         | Type of engine                                |
| `Transmission`   | Automatic / Manual                            |
| `Color`          | Car color                                     |
| `Price ($)`      | Sale price of the car                         |
| `Dealer_No`      | Unique dealer number                          |
| `Body Style`     | Sedan, SUV, etc.                              |
| `Phone`          | Dealer contact number                         |
| `Dealer_Region`  | Region where the dealer is located            |

---

## 🛠️ Tools & Technologies

| Tool/Tech   | Role                                               |
|-------------|----------------------------------------------------|
| **Python**  | Data cleaning, transformation, and EDA             |
| **Pandas**  | Data manipulation and preprocessing                |
| **SQL**     | KPI extraction, joins, filtering, data aggregation |
| **Power BI**| Visualization and dashboard design                 |
| **Git & GitHub** | Version control and publishing                |

---

## 📁 Files

```text
car-sales-analytics/
├── Car_Sales_Using_Python.ipynb   # Cleaning, feature prep and EDA (pandas, NumPy, scikit-learn)
├── Car_Sales_Using_SQL.sql        # KPI queries: revenue, dealers, demographics
├── DASHBOARD.pbix                 # Main Power BI dashboard
├── car_sales_visuals.pbix         # Additional Power BI visuals
└── README.md
```

The dataset is not stored in this repo. Download the car sales CSV (columns listed above) and save it as
`data/car_sales.csv` before running the notebook.

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/Lingesh-S/car-sales-analytics.git
   cd car-sales-analytics
   mkdir data   # put car_sales.csv here
   ```

2. **Run the Python analysis:** open `Car_Sales_Using_Python.ipynb` in Jupyter, VS Code or Colab
   (`pip install pandas numpy scikit-learn`).

3. **Explore the SQL queries:** load the CSV into a table named `car_sales` (PostgreSQL or MySQL) and run
   `Car_Sales_Using_SQL.sql`.

4. **Open the dashboard:** open `DASHBOARD.pbix` in Power BI Desktop.

---

## 🖼️ Dashboard Preview
![CAR_SALES](https://github.com/user-attachments/assets/a60efe2f-ed62-4f9c-9612-643b61b1e63c)

---
## 👤 Author
**Lingesh S**  
Aspiring Data Analyst | Python • SQL • Power BI
🔗 GitHub
🔗 LinkedIn

---

## ⭐️ Support
If this project helped you or inspired your own learning, consider giving it a star ⭐ and sharing!

---

## Thank You

Feel free to explore the project and reach out if you have any questions or feedback.



