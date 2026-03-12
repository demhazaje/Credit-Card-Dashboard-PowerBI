# 💳 Credit Card Financial Weekly Report: Power BI Analytics

## 📌 Project Explanation
This project focuses on building interactive Power BI dashboards to analyze credit card customer demographics and transaction patterns. The goal was to provide a weekly status report that allows stakeholders to explore actionable insights regarding spending behaviors, revenue generation, and customer profiles, with deep-dive filtering capabilities.

## 📋 Requirements
* Develop two distinct interactive dashboards: a Customer Report and a Transaction Report.
* Implement dynamic filters for Gender (Male/Female), Age Group, Income Group, Week Number, and Spending Category.
* Utilize DAX calculations to create custom columns and measures (e.g., Age Groups, Income bins, Total Revenue, Current Week Revenue, Previous Week Revenue).
* Ensure visuals are clean, easy to interpret, and highly interactive using slicers and drill-throughs.

## 🛠️ Tools & Technologies
* **Business Intelligence:** Microsoft Power BI (`.pbix`)
* **Data Manipulation:** DAX (Data Analysis Expressions), Power Query
* **Data Sources:** CSV Datasets (`customer.csv`, `CreditCard.csv`)

## 🚧 Challenges Faced
* **Complex DAX Time Intelligence:** Calculating the week-over-week revenue metrics (`cur_week_revenue` vs `previous_week_revenue`) required careful DAX formulation to ensure the filters interacted correctly with the transaction dates.
* **Data Segmentation:** Converting raw numerical age and income data into clean, categorical bins (Low, Med, High) required building custom conditional columns in Power Query to make the slicers user-friendly.

## 💡 Key Insights
* **Demographic Spending:** Certain age and income groups drive a disproportionately high amount of the total transaction volume and revolving balances.
* **Revenue Tracking:** The week-over-week DAX measures successfully highlighted periods of revenue growth and contraction, allowing for precise tracking of transaction frequency across different spending categories.
* **Customer Profiling:** The demographic dashboard revealed strong correlations between customer education level, job type, and their ultimate customer satisfaction score.

## 🚀 Recommendations for Improvement
* **Targeted Card Offers:** Marketing teams should use the demographic insights to offer premium credit card upgrades specifically to the "High" income and specific age bins that show the highest utilization ratios.
* **Retention Campaigns:** Monitor the week-over-week revenue drops in specific spending categories to identify when customers might be switching to a competitor's card, and trigger automated cashback offers to retain their spending.

## 👨‍💻 About Me
I am Ejaz Ahmed, a student at IMI Kolkata passionate about transforming raw financial data into meaningful, interactive visual stories using tools like Power BI, DAX, and SQL.
