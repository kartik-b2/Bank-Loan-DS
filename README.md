# Bank-Loan-DS

A complete end-to-end data analytics project designed to analyze bank loan performance, borrower behavior, and risk segmentation. This project integrates SQL, Power BI, and data storytelling to transform raw loan data into actionable insights.

🚀 Project Overview
This project simulates a real-world business scenario for a lending institution. The aim is to evaluate the overall loan portfolio, understand the patterns of good and bad loans, and identify high-risk areas through data-driven dashboards.

🧠 Objectives
Analyze trends in loan applications, funding, and repayments.

Classify Good vs Bad Loans using loan_status.

Explore borrower profiles using metrics like DTI, Interest Rate, and Employment Length.

Visualize regional and temporal loan trends.

Create a clean, interactive Power BI dashboard for stakeholder presentation.

📊 Tools & Technologies
Tool	Purpose
MS SQL Server	Data storage, querying, transformation
Power BI	Data modeling, DAX measures, visualization
Excel	Exploratory Data Analysis (EDA)

🔧 Features & Functionalities
🔹 Part 1: Data Preparation (SQL)
Created database and tables in MS SQL Server

Cleaned and transformed data using SQL queries

Wrote performance-optimized queries to calculate:

Total Loan Applications

Funded & Received Amounts (MTD/PMTD)

Average Interest Rate & DTI

Good vs Bad Loan ratios

<details> <summary>Sample Query</summary>
sql
Copy
Edit
SELECT
  COUNT(id) AS Total_Applications,
  AVG(int_rate) * 100 AS Avg_Interest_Rate,
  AVG(dti) * 100 AS Avg_DTI
FROM bank_loan_data;
</details>
🔹 Part 2: Visualization (Power BI)
Built 3 fully interactive dashboards:

📌 Dashboard 1: Summary
Key KPIs: Applications, Funding, Amount Received

Month-over-Month comparisons

Good vs Bad Loan segmentation

📌 Dashboard 2: Overview
Monthly Trends (Line Chart)

Regional Distribution (Filled Map)

Loan Term, Purpose, Home Ownership Analysis

Employment Length impact

📌 Dashboard 3: Details
Tabular grid for detailed drill-down

Loan status overview with Interest Rate & DTI

📁 File Structure
graphql
Copy
Edit
📦 Bank-Loan-Analysis
├── Query Doc.docx             # Contains all SQL queries used
├── Bank Loan PPT Power BI.pptx # Slide deck of the report and visuals
├── bank_loan_dashboard.pbix   # Final Power BI dashboard file
├── README.md                  # Project documentation (this file)
📈 Key Insights
Over 70% of the loan volume came from Good Loans (Fully Paid or Current).

Certain states and job tenures are associated with higher default risk.

Average DTI and Interest Rates help assess borrower repayment capacity.

Strong seasonal trends are visible in application spikes.

📬 Contact
If you'd like to collaborate, provide feedback, or are hiring for Data Analyst roles, feel free to connect:

Kartik Kashyap
📧 Email: kartikkash03@gmail.com
🔗 LinkedIn : https://www.linkedin.com/in/kartik-kashyap/

📌 License
This project is for educational and portfolio purposes only. Data is fictional or anonymized.

