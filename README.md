# Credit-Card-Dashboard-PowerBI

# 💳 Credit Card Financial Weekly Report: Power BI Analytics

## 📌 Project Overview
This repository contains the datasets and my Power BI solutions for the **Credit Card Financial Weekly Report** project. The objective of this project was to build interactive and well-organized Power BI dashboards to provide actionable insights into credit card customer demographics and their transaction patterns. 

## 🛠️ Tools & Technologies Used
* **Business Intelligence:** Microsoft Power BI (`.pbix`)
* **Data Manipulation & Modeling:** Power Query, DAX (Data Analysis Expressions)
* **Data Sources:** CSV Datasets (`customer.csv`, `CreditCard.csv`)

## 📂 Repository Contents
* **`customer.csv`**: Contains customer demographic data including age, gender, income, education level, and satisfaction scores.
* **`CreditCard.csv`**: Contains detailed financial and transaction data, including credit limits, transaction volumes, revolving balances, and utilization ratios.
* **`1. Customer Data Visualisation.pbix`**: Power BI dashboard focusing on customer demographics and profiles.
* **`2. Credit Card Data Visualization.pbix`**: Power BI dashboard focusing on transaction patterns, revenue, and spending behaviors.
* **`Credit Card Financial weekly report OVERVIEW.pdf`**: The original project instruction document.

## 📊 Dashboards & Key Features

### Dashboard 1: Credit Card Customer Report (`1. Customer Data Visualisation.pbix`)
This interactive dashboard visualizes key metrics related to the customer base. 
* **Focus:** Customer demographics, income levels, and overall customer profiles.
* **Interactive Filters / Slicers:** * **Gender Filter:** Male / Female
  * **Age Group Filter:** Custom age bins (e.g., 18-25, 26-35, etc.)
  * **Income Group Filter:** Categorized into Low, Medium, and High.

### Dashboard 2: Credit Card Transaction Report (`2. Credit Card Data Visualization.pbix`)
This dashboard is designed to analyze credit card transactions, spending patterns, and revenue generation.
* **Focus:** Transaction frequencies, spending patterns, and revenue tracking.
* **Interactive Filters / Slicers:** * **Gender Filter:** Male / Female
  * **Transaction Date Filter:** Tracked by week number.
  * **Spending Category Filter:** Analysis based on different expenditure types.

## 🧮 DAX Calculations & Data Transformations
To meet the project requirements, several custom DAX measures and calculated columns were created to enhance the analytical capabilities of the dashboards:
* **Customer Segmentation:** Formulated `Age Group` and `Income Group` (Low, Med, High) columns to properly segment the user base.
* **Revenue Metrics:** Calculated `Total Revenue`.
* **Time Intelligence:** Created measures for `week_num`, `cur_week_revenue` (Current Week Revenue), and `previous_week_revenue` to allow for week-over-week performance tracking.

## 🚀 How to Use
1. Clone or download this repository to your local machine.
2. Ensure you have **Microsoft Power BI Desktop** installed.
3. Open `1. Customer Data Visualisation.pbix` or `2. Credit Card Data Visualization.pbix` to interact with the dashboards.
4. Use the slicers on the canvas to drill through the data by gender, age, income, and week!

## 👨‍💻 About Me
I am a data enthusiast focused on transforming raw data into meaningful, interactive visual stories. I leverage tools like Power BI, DAX, and SQL to uncover hidden business insights and support data-driven decision-making.
