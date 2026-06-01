# Bank Loan Portfolio & Risk Analysis – Power BI

This project analyzes a bank’s loan portfolio to understand loan performance, risk levels, and default patterns using an interactive Power BI dashboard.

## Dataset

- Source: Open-source financial loan dataset (`financial_loan.csv`)
- Key columns: LoanStatus, LoanAmount, InterestRate, Grade, Purpose, IssueDate, LoanCategory (Good/Bad Loan)

## Power BI Highlights

- Cleaned and transformed loan data using Power Query (data types, new LoanCategory, date formatting).
- Created DAX measures for:
  - Total Loans, Good Loans, Bad Loans
  - Bad Loan %, Total Loan Amount, Avg Interest Rate
- Designed a single-page dashboard with:
  - KPI cards for portfolio overview
  - Bar charts by Loan Status, Grade (risk level), and Purpose
  - Monthly loan amount trend by status
  - Matrix for Grade vs Charged-off loans with color-coded conditional formatting

## How to View

1. Download the `.pbix` file from this repository.
2. Open it in Power BI Desktop.

## Key Insights

- Identified higher bad-loan percentages in specific risk grades and loan purposes.
- Highlighted segments that may require stricter credit policies or closer monitoring.
