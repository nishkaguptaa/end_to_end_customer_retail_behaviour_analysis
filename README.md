# End-To-End Customer Retail Behaviour Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases**. The objective is to uncover insights into spending patterns, customer segments, and product preferences to guide strategic business decisions. By integrating **Python**, **SQL**, and **Power BI**, the analysis provides a comprehensive view of revenue drivers and consumer demographics.

## 📂 Dataset
* **Source:** Transactional shopping data.
* **Size:** 3,900 rows and 18 columns.
* **Key Features:** Customer demographics (Age, Gender, Location, Subscription Status), purchase details (Item, Category, Amount, Season), and behavioral metrics (Discounts, Previous Purchases, Review Ratings).

## 🛠️ Tools & Technologies
* **Data Cleaning & EDA:** Python (Pandas).
* **Database Management:** PostgreSQL.
* **Data Visualization:** Power BI.
* **Presentation:** Gamma AI.

## 🛤️ Project Steps
1.  **Data Preparation (Python):** Loaded the dataset and handled missing values in the `Review Rating` column using category-specific medians.
2.  **Feature Engineering:** Created `age_group` bins and standardized column names to snake_case.
3.  **Database Integration:** Migrated the cleaned DataFrame into **PostgreSQL** for structured querying.
4.  **SQL Analysis:** Executed queries to calculate revenue by gender, identify high-spending discount users, and segment customers into Loyal, Returning, and New categories.
5.  **Visualization:** Built an interactive **Power BI Dashboard** to track KPIs such as average purchase amount ($59.76) and revenue by category.

## 📊 Dashboard Highlights
The Power BI dashboard provides a visual breakdown of:
* **Subscription Impact:** 27% of customers are subscribers.
* **Category Performance:** High-revenue categories including Clothing and Accessories.
* **Demographics:** Revenue and sales volume categorized by age group and gender.

## 📈 Results & Key Findings
* **Revenue Drivers:** Male customers generated significantly higher revenue ($157,890) than Female customers ($75,191).
* **Top Demographic:** The **Young Adult** age group is the leading revenue contributor at **$62,143**.
* **Loyalty Segments:** Identified **3,116 Loyal customers**, providing a clear target for retention programs.
* **Shipping Preference:** Express shipping users show a slightly higher average spend ($60.48) compared to Standard shipping.

## 🚀 How to Run
1.  **Python:** Run the `data_cleaning.py` script to process the raw CSV and generate the cleaned dataset.
2.  **SQL:** Import the cleaned CSV into your PostgreSQL environment and execute the provided `.sql` scripts to generate business metrics.
3.  **Power BI:** Open the `.pbit` file to explore the interactive dashboard.
4.  **Report:** View the final presentation link generated via Gamma for a high-level executive summary.
