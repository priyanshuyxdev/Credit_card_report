# Credit_card_report
🔄 Data Workflow & Methodology

This project follows a structured end-to-end data analytics workflow, starting from raw data ingestion to final dashboard insights.

1️⃣ Data Source (Excel)

Raw credit card transaction and customer data was initially available in Excel format.

The dataset included transaction details, customer demographics, card categories, and payment modes.

Basic data validation was performed in Excel before ingestion.

2️⃣ Database Layer (PostgreSQL)

Excel data was imported into PostgreSQL to simulate a real-world analytics environment.

SQL was used to:

Create structured tables

Validate data types and constraints

Perform basic aggregations and sanity checks

This step ensured data consistency and scalability before visualization.

3️⃣ Data Import into Power BI

Power BI was connected to PostgreSQL using database authentication.

Data was imported using Import mode for optimized performance.

Multiple related tables were loaded and modeled inside Power BI.

4️⃣ Data Transformation (Power Query)

Power Query was used to:

Clean null and inconsistent values

Create derived columns (e.g., Age Groups)

Standardize categorical fields

These transformations were applied at refresh time to improve model efficiency.

5️⃣ Data Modeling

Proper relationships were established between transaction and customer tables.

Star-schema principles were followed where applicable.

Columns and tables were renamed for business readability.

6️⃣ DAX Calculations

Custom DAX measures and calculated columns were created, including:

Total Revenue

Total Transaction Amount

Interest Earned

Transaction Count

Age Group segmentation using SWITCH(TRUE())

Percentage contribution measures for comparative analysis

These DAX calculations enabled dynamic and interactive reporting.

7️⃣ Visualization & Reporting

Interactive dashboards were built using:

Bar charts

Line charts

Tables and KPIs

Consistent formatting, color themes, and clear titles were applied for a professional presentation.

Insights were translated into actionable business recommendations.

🧠 Why This Approach Matters

Demonstrates real-world data flow (Excel → PostgreSQL → Power BI)

Separates data storage, transformation, and visualization

Reflects industry-standard analytics practices

Shows proficiency beyond basic Power BI usage
