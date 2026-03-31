# End-To-End Customer Retail Behaviour Analysis

This project provides a data-driven analysis of consumer purchasing patterns using a dataset of **3,900 transactions** across 18 distinct features. By integrating **Python**, **SQL**, and **Power BI**, the study uncovers key insights into demographics, subscription impact, and product performance to guide strategic business decisions.

## 🚀 Key Insights
* **Revenue Leaders:** Male customers contributed **$157,890** in total revenue, significantly outperforming the female segment ($75,191).
* **High-Value Demographics:** The **Young Adult** age group is the most profitable, generating **$62,143** in revenue.
* **Customer Loyalty:** The analysis identified **3,116 Loyal customers**, compared to 701 Returning and 83 New customers.
* **Subscription Trends:** 27% of customers are subscribers, maintaining an average spend of **$59.49** per purchase.
* **Product Performance:** **Handbags** and **Jewelry** are among the top-purchased items, while **Gloves** hold the highest average review rating (3.86).

## 🛠️ Tech Stack
* **Data Cleaning & Engineering:** Python (Pandas).
* **Database Management:** PostgreSQL.
* **Data Visualization:** Power BI.

## 📂 Project Workflow
1.  **Data Preparation:** Handled missing values in the `Review Rating` column using category medians and performed feature engineering to create `age_group` bins.
2.  **SQL Analysis:** Migrated cleaned data to PostgreSQL to query complex business metrics, such as revenue by gender and high-spending discount users.
3.  **Visualization:** Developed an interactive **Power BI Dashboard** to track KPIs including Average Purchase Amount ($59.76) and Average Review Rating (3.75).

## 💡 Recommendations
* **Retention:** Implement reward programs to transition "Returning" buyers into the "Loyal" segment.
* **Subscription Growth:** Promote exclusive benefits to the 73% of customers who are not yet subscribers.
* **Targeted Marketing:** Focus campaigns on high-revenue categories (Clothing and Accessories) and the Young Adult demographic.
