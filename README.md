# Bank Loan Data Analysis Project

This project involves an in-depth analysis of a bank loan dataset containing 38,000 rows. The analysis was performed using SQL for data querying, Python for Exploratory Data Analysis (EDA), and Power BI for data visualization. 

## Project Overview

### Data Analysis Using SQL
The dataset was initially explored and queried using SQL to extract meaningful insights and to prepare the data for further analysis. Key operations included filtering, grouping, and aggregating data to understand loan distributions, repayment statuses, and borrower characteristics.

### Exploratory Data Analysis (EDA) with Python
EDA was conducted using Python to uncover patterns, spot anomalies, and test hypotheses. The primary tools and libraries used include:
- **Pandas** for data manipulation and cleaning.
- **Matplotlib** for visualizations.
- **NumPy** for numerical operations.

### Power BI Dashboard
A comprehensive Power BI dashboard was created to visualize the analysis results. This is a multi-page dashboard with navigation buttons for easy transition between pages. The dashboard includes the following key metrics and insights:

#### Dashboard Pages and Metrics
1. **Summary Page**
   - **Total Loan Applications:** 38.6K
   - **Monthly Total Loan Applications (MTD):** 4.3K (MoM: 6.9%)
   - **Total Funded Amount:** $435.8M
   - **Monthly Total Funded Amount (MTD):** $54.0M (MoM: 13.0%)
   - **Total Amount Received:** $473.1M
   - **Monthly Total Amount Received (MTD):** $58.1M (MoM: 15.8%)
   - **Average Interest Rate:** 12.0% (MTD: 12.4%, MoM: 3.5%)
   - **Average Debt-to-Income (DTI) Ratio:** 13.3% (MTD: 13.7%, MoM: 2.7%)

2. **Good vs. Bad Loans Page**
   - **Good Loan Applications:** 33K
   - **Good Loan Funded Amount:** $370.2M
   - **Good Loan Amount Received:** $435.8M
   - **Bad Loan Applications:** 5.333K
   - **Bad Loan Funded Amount:** $65.5M
   - **Bad Loan Amount Received:** $37.3M

3. **Loan Status Overview**
   - **Fully Paid Loans:** 32,145 applications, $3.51B funded, $4.12B received
   - **Current Loans:** 1,098 applications, $188.66M funded, $241.99M received
   - **Charged Off Loans:** 5,333 applications, $655.32M funded, $372.84M received

4. **Total Amount Received Analysis**
   - By Month
   - By State
   - By Term (36 months vs. 60 months)
   - By Employee Length
   - By Purpose (e.g., debt consolidation, credit card, home improvement)
   - By Home Ownership (e.g., mortgage, rent)

5. **Detailed Loan Information**
   - Loan details including ID, purpose, home ownership, grade, sub-grade, issue date, funded amount, interest rate, installment, and amount received.

The Power BI dashboard provides a dynamic and interactive way to navigate through different aspects of the loan data, making it easier to draw insights and make data-driven decisions.

### Files Included
- **SQL Scripts:** Containing the queries used for initial data analysis.
- **Python Notebooks:** Used for EDA and visualizations.
- **Power BI Dashboard:** Multi page Power BI Dashobard

### Conclusion
This project demonstrates a comprehensive approach to data analysis by combining SQL, Python, and Power BI to extract, analyze, and visualize data, providing clear and actionable insights.
