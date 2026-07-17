# Credit Card Financial Dashboard 📊

## Project Objective
To develop a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations efficiently and effectively.

## 🛠️ Tools & Technologies Used
* **SQL (PostgreSQL / MySQL):** For database creation, managing tables, and storing raw data.
* **Power BI:** For data connection, data processing, DAX calculations, and interactive data visualization.
* **CSV Files:** Used as the primary data source before importing into the SQL database.

## 🚀 Steps Followed in this Project
1. **Data Extraction & Preparation:**
   * Gathered raw data containing credit card transactions and customer details via CSV files.
   * Created tables and imported the data into a SQL database.
   * Established a live database connection between SQL and Power BI.
2. **Data Processing & DAX Calculations:**
   * Created calculated columns for deeper analysis (e.g., categorized customers into **Age Groups** and **Income Groups**).
   * Engineered dynamic measures using **DAX functions** (`CALCULATE`, `FILTER`, `DIVIDE`) to calculate week-over-week (WoW) revenue trends, current week revenue, and previous week revenue.
3. **Dashboard Design & Development:**
   * Developed two primary interactive dashboards:
     * **Credit Card Transaction Report:** Highlights revenue generated across different card categories, expenditure types, and quarters.
     * **Credit Card Customer Report:** Analyzes customer demographics, breaking down revenue by age, income group, education, job, and geographic states.
   * Implemented custom interactive filters (Tree Maps & Slicers) by gender, card type, income level, and week.
4. **Real-time Data Update Integration:**
   * Simulated a real-world environment by importing a new week's data (Week 53) into the SQL database and live-refreshing the Power BI dashboard to dynamically update all metrics and charts.

## 💡 Key Project Insights (Week 53)
* **Revenue Growth:** Overall revenue grew significantly, recording a Week-on-Week (WoW) increase of **28.8%**.
* **Card Performance:** **Blue and Silver** credit cards accounted for approximately **93%** of all total transactions.
* **Demographics:** 
  * Male customers contributed more to the overall revenue compared to female customers.
  * The **40-60 age group** and **Businessmen/White-collar workers** generated the most revenue.
* **Geographic Impact:** Just three states—**Texas, New York, and California**—contributed to **68%** of the total operations.
* **Operational Metrics:** 
  * Achieved a solid **30-day card activation rate of 57%**.
  * Maintained a **delinquency rate of 6.06%**.

## 📂 Repository Contents
* `Data/`: Contains the raw `.csv` files used for the project (Credit Card data, Customer data, and additional weekly data).
* `SQL_Scripts/`: Contains the SQL queries used to create tables and import data.
* `Dashboard/`: Contains the final `.pbix` Power BI file and exported PDF reports.

## ⚙️ How to Use This Repository
1. Set up a local SQL server (PostgreSQL or MySQL).
2. Run the provided SQL scripts to create the tables and import the CSV data.
3. Open the `.pbix` file in Power BI Desktop.
4. Update the SQL database connection parameters in Power BI to match your local server credentials.
5. Click **Refresh** to load the data and interact with the dashboards.

---
