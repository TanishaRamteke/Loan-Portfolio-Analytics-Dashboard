# Loan Portfolio Analytics Dashboard

## Project Overview
This project presents an interactive Power BI dashboard designed to analyze loan portfolio performance, lending distribution, and default risk.  
The dashboard provides insights into loan issuance, repayment trends, customer risk segmentation, and lending distribution across cities.

---

## Key Metrics
• Total Loans Issued  
• Total Lending Amount  
• Interest Revenue  
• Loan Default Rate  
• Average Loans per Customer  

---

## Dashboard Features
• Interactive slicers for Year, City, Loan Type, and Risk Category  
• Monthly repayment and default rate trend analysis  
• Lending distribution across cities  
• Loan default monitoring against target rate  
• Customer risk segmentation visualization  

---

## Tools & Technologies
• Power BI  
• DAX (Data Analysis Expressions)  
• Power Query  
• Data Modeling  

---

## Dataset

The dashboard is built using three datasets:

• Customers – Contains customer details and risk category information  
• Loans – Contains loan amount, loan type, interest rate, and tenure details  
• Repayments – Contains EMI payments, payment dates, and repayment tracking

---

## Data Model

The dashboard uses a relational data model connecting:

Customers → Loans → Repayments

A Date Table was created in Power BI and linked with the payment date to enable monthly trend analysis and time-based filtering.

---

## Dashboard Preview
![Dashboard](dashboard_screenshot.png)

