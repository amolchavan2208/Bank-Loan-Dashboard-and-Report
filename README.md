**Bank Loan Analysis | Power BI + SQL Portfolio Project**


**📊 Bank Loan Analysis Dashboard**
A complete Data Analytics Portfolio Project built using MS SQL Server + Power BI.

This project analyzes bank loan performance, repayment behavior, customer profile distribution, and financial KPIs to support better lending decisions.
________________________________________
**🗂️ Project Files Included**
File Name	Description

Bank_Loan_Dashboard.pbix	Complete Power BI dashboard

Bank Loan PPT Power BI.pptx	Presentation of all dashboards

Query Doc.docx	SQL queries used for all KPIs

Terminologies in Data.docx	Data dictionary for all fields

________________________________________
**🎯 Project Objective**
To analyze bank loan data and create interactive dashboards that display:
✔ Total loan applications

✔ Fund disbursement trends

✔ Repayment performance

✔ Good vs Bad loan classification

✔ Borrower profile insights

✔ Regional trends & loan purpose breakdown

✔ Month-To-Date (MTD) & MoM metrics

✔ Comprehensive detailed loan view

This project demonstrates end-to-end data analytics implementation including SQL, Power Query, Power BI modeling, and visualization.

________________________________________
**🏗️ Tech Stack Used**
• Category	Tools

• Database	MS SQL Server 19.0

• SQL Client	SQL Server Management Studio 19

• BI Tool	Power BI (June 2023 version)

• Data Cleaning	SQL, Power Query

• Visualization	Power BI
________________________________________
**📥 Data Source**
Internal dataset containing bank loan details, including:

•	Borrower demographics

•	Loan amount & financial metrics

•	Loan status (Fully Paid / Current / Charged Off)

•	Dates (Issue Date, Payment Dates, Credit Pull)

•	Employment & home ownership info

A full data dictionary is included in Terminologies in Data.docx.
________________________________________
**🛠️ Project Workflow**

**1️⃣ Data Import & SQL Processing**

•	Created database and tables in MS SQL Server

•	Cleaned data & validated fields

•	Executed SQL queries for:

o	KPIs (Total Apps, Funded Amount, Amount Received)

o	MTD / PMTD / MoM analysis

o	Good vs Bad Loan calculations

o	Borrower segmentation

o	State, Term, Purpose, Employee Length, Home Ownership analysis

SQL Query file included: Query Doc.docx
________________________________________
**2️⃣ Power BI Data Modeling**

•	Connected Power BI to SQL Server

•	Cleaned dataset with Power Query

•	Built Date Table for time intelligence

•	Established relationships for modeling

•	Applied DAX measures:

o	Loan KPIs

o	MoM % Change

o	Good/Bad Loan KPIs

o	Aggregations & financial metrics

________________________________________
**📈 Dashboards Included**
________________________________________
**📌 Dashboard 1: Summary**

KPIs
•	Total Loan Applications
•	Total Funded Amount
•	Total Amount Received
•	Average Interest Rate
•	Average DTI (Debt-to-Income Ratio)
•	MTD and MoM metrics
Good vs Bad Loan Analysis
Good Loan (Fully Paid + Current)
•	Good Loan %
•	Applications
•	Funded Amount
•	Amount Received
Bad Loan (Charged Off)
•	Bad Loan %
•	Applications
•	Funded Amount
•	Amount Received
Loan Status Drilldown
•	Loan Count
•	Total Funded Amount
•	Interest Rate
•	DTI
•	Total Amount Received
________________________________________
**📌 Dashboard 2: Overview**

Visuals Included:
•	Monthly Trends (Line Chart)
•	Regional Analysis by State (Filled Map)
•	Loan Term Distribution (Donut Chart)
•	Employee Length Analysis (Bar Chart)
•	Loan Purpose Breakdown (Bar Chart)
•	Home Ownership Distribution (Tree Map)
________________________________________
**📌 Dashboard 3: Details**

A complete record-level dashboard showing:
•	Borrower profile
•	Loan financials
•	Loan status details
•	Payment behavior
•	All calculated metrics
Designed to act as a one-stop reference for analysts and business users.
________________________________________
**📚 Key Learnings**

**SQL**

•	GROUP BY, ORDER BY
•	CTE
•	Partitioning
•	DatePart, DateName
•	Aggregations (SUM, AVG, COUNT)
•	Month-wise filtering
•	KPI logic development

**Power BI**

•	Connecting to SQL Server
•	Power Query cleaning
•	Data modeling
•	DAX functions (CALCULATE, SUMX, FILTER, DATE functions)
•	Creating KPI Cards
•	Building interactive visuals
•	Formatting & UI design
•	Navigation buttons for dashboard switching
________________________________________
**📦 How to Use This Project**

1.	Download the repo
2.	Open Bank_Loan_Dashboard.pbix in Power BI
3.	Use the SQL query document to rebuild data source if needed
4.	Open the PPT to view dashboard presentation
5.	Explore DAX, visuals & filters
________________________________________
**📝 Future Enhancements**

•	Predictive modeling for loan default probability

•	RLS (Role-Level Security) implementation

•	Paginated Reports for printable loan summary

•	Deployment using Power BI Service & Dataflows

________________________________________
**💡 Author**

**Amol Chavan | 
Power BI Developer | Data Analyst**

Reach out for projects or portfolio help!

