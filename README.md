
Donor and Donation Data Analysis Using SQL

Project Overview

This project analyzes donor and donation data using SQL to uncover patterns in donor behavior, donation trends, and fundraising opportunities. The analysis was performed using PostgreSQL and pgAdmin.

The objective was to explore donor data, assess data quality, answer key business questions, and generate actionable recommendations that can improve fundraising performance and donor engagement.

---

Business Problem Statement

Organizations depend on donor contributions to support their operations and achieve their objectives. Understanding donor behavior is critical for developing effective fundraising strategies.

This project aims to identify donation patterns, donor demographics, geographic trends, and donor preferences that can support data-driven fundraising decisions.

---

Tools & Technologies Used

- PostgreSQL
- pgAdmin 4
- SQL
- Microsoft Word
- Microsoft PowerPoint
- GitHub

---

Dataset Description

The project uses two datasets containing donor and donation information.

Donor_Data

Contains donor profile information including:

- Donor ID
- Donation Frequency
- University
- Car Brand
- Movie Genre

Donation_Data

Contains donor demographic and donation information including:

- Donor ID
- First Name
- Last Name
- Gender
- State
- Job Field
- Donation Amount

The two tables are linked using the Donor ID field.

Dataset Size

- Donor_Data: 1,000 records
- Donation_Data: 1,000 records

---

Methodology

The analysis followed a structured approach:

1. Data Import into PostgreSQL.
2. Data Exploration and Profiling.
3. Data Quality Assessment.
4. Missing Value and Duplicate Checks.
5. Data Cleaning and Validation.
6. Business Analysis using SQL Queries.
7. Advanced Analysis using Joins and Aggregations.
8. Generation of Insights and Recommendations.

---

SQL Techniques Used

- SELECT Statements
- WHERE Clauses
- GROUP BY
- ORDER BY
- Aggregate Functions (COUNT, SUM, AVG, MIN, MAX)
- INNER JOIN
- HAVING
- LIMIT
- Data Quality Assessment
- Missing Value Analysis
- Duplicate Detection
- Business Analysis Queries

---

Key Business Questions

1. How are donors distributed by gender?
2. Who are the top donors?
3. Which job fields generate the highest donations?
4. Which states generate the highest donations?
5. What are the most common donation frequencies?
6. How does donation frequency differ by gender?
7. What are the most common car brands among donors?
8. What are the most popular movie genres among donors?

---

Key Findings

- Total Donations: 249,085
- Average Donation: 249.09
- Female Donors: 508
- Male Donors: 492
- Male donors contributed more overall than female donors.
- California generated the highest total donations.
- Texas ranked second in total donations.
- Florida ranked third in total donations.
- Research & Development recorded the highest average donation amount.
- Human Resources generated the highest overall donations.
- Yearly donors represented the largest donation frequency category.
- Ford was the most common car brand among donors.
- Drama was the most popular movie genre among donors.

---

Key Insights

- Donation activity was relatively balanced across genders, although male donors contributed a higher overall donation value.
- Geographic location appears to influence fundraising performance, with California, Texas, and Florida generating the highest donation totals.
- Professional background influences donation behavior, as Research & Development professionals recorded the highest average donation values.
- Donor engagement varies significantly by donation frequency, suggesting opportunities for targeted engagement campaigns.
- Donor preferences such as car brands and movie genres can support audience segmentation and personalized fundraising strategies.

---

Recommendations

- Focus fundraising efforts on high-performing states such as California, Texas, and Florida.
- Target high-value donor segments including Research & Development, Legal, and Human Resources professionals.
- Develop re-engagement campaigns for inactive and infrequent donors.
- Improve data collection processes to reduce missing university information.
- Use donor demographic and preference data to improve campaign targeting.

---

Repository Structure

sql-capstone-project/

├── README.md

├── Faith_Ishicheli_SQL_Capstone.sql

├── Faith_Ishicheli_SQL_Portfolio.pdf

├── Faith_Ishicheli_SQL_Presentation.pdf

---

How to Reproduce the Analysis

1. Install PostgreSQL and pgAdmin.
2. Create a database for the project.
3. Import the Donor_Data and Donation_Data SQL files.
4. Execute the SQL queries contained in the SQL Capstone file.
5. Review outputs and compare findings with the portfolio report.

---

Project Files

- Faith_Ishicheli_SQL_Capstone.sql
- Faith_Ishicheli_SQL_Portfolio.pdf
- Faith_Ishicheli_SQL_Presentation.pdf

---

License

MIT License

---

Author

Ishicheli Faith 
