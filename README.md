# LOAN-PERFORMANCE-ANALYSIS
## Project Scope:
## Objective
### This project focuses on analysing a loan dataset to identify patterns, optimize loan approval criteria, and evaluate loan performance based on borrower demographics, risk levels, and other key factors. Additionally, the goal is to visualize insights through an Excel dashboard.
# Key Deliverables
•	Detailed analysis of loan performance by interest rates, loan status, and risk categories.
•	Recommendations for loan approval optimization and risk mitigation.
•	An Excel dashboard summarizing key metrics and KPIs.


Problem Statement:
Business Problem
TDI Financial needs to optimize its loan approval process to minimize default risks and maximize profitability. High default rates from risky borrowers, unclear patterns in approvals, and inefficient risk assessment criteria require targeted solutions.
Key Questions
•	Which borrower demographics and loan conditions are associated with higher default rates?
•	How do interest rates impact loan performance?
•	What patterns can be identified in loan approvals and rejections?
•	What KPIs should TDI monitor to optimize performance?

Data Cleaning and Transformation
1.	Import the Dataset:
o	Load the dataset into Excel.
2.	Handle Missing Values:
o	Identify and address missing values by either filling them with appropriate values or removing incomplete records.
3.	Remove Duplicates:
o	Identify and remove duplicate entries to ensure data accuracy.
4.	Correct Data Entry Errors:
o	Review the dataset for any data entry errors and correct them.
5.	Standardize Data Formats:
o	Ensure that all data is in a consistent format (e.g., dates, currency, percentages)

Additional Data Cleaning Steps:
•	Standardized Dates: Ensured all dates are in a consistent format.
•	Removed Blanks: Addressed blank cells in the dataset.
•	Proper Case: Converted employment titles to proper case.
•	Converted abbreviations to full names: Home Ownership (e.g., "O" to "Own", "R" to "Rent", "MO" to "Mortgage").
•	Verification Source Column: Standardized verification sources (e.g., "V" to "Verified", "SV" to "Source Verified", "Not V" to "Not Verified").
•	Used XLOOKUP and TRIM functions to convert state codes to full names.
•	Interest Rate and DTI to Percentage: Converted interest rates and debt-to-income ratios to percentage format.
•	Default Indicator: Created a default indicator using the formula:
excel
=IF(K2="Charged Off", 1, 0)
•	Income Segmentation: Segmented income using the formula:
excel
=IF(R3 >= 1000000, "High Income", IF(R3 >= 100000, "Medium Income", "Low Income"))
•	Interest Rate Segmentation: Segmented interest rates using the formula:
excel
=IF(U2 >= 20%, "High", IF(U2 >= 10%, "Medium", "Low"))


Dashboard Features:
KPI Section
1.	Total Loan Borrowers: Displays the total number of borrowers.
              38,574 borrowers.
2.	Total Loan Repayment: Shows the cumulative amount repaid.
             $473.0 million.
3.	Average Loan Amount: Displays the average loan amount issued.
             $435.7 thousand.
4.	Average Loan Defaulter Rate: Shows the average percentage of loans defaulted.
             14%.
5.	Average Interest Rate: Displays the overall average interest rate.
             12%.
________________________________________
Charts and Visualizations
1.	Loan Defaulters by Employment Length:
o	Bar chart showing the number of defaulters based on employment length.
o	Insight: Borrowers with employment lengths of 10+ years had the highest defaulters (45 cases).
2.	Loan Purpose by Income Level:
o	Horizontal bar chart categorizing loan purposes by income levels (High, Medium, Low).
o	Insight: Common purposes include debt consolidation, credit cards, and small business loans.
3.	Interest Rate by Loan Status:
o	Line chart comparing the number of loans across interest rate levels (High, Low, Medium).
o	Insight: Medium interest rate loans had the highest numbers 84%.
4.	Loan Distribution by State:
o	Two visualizations:
	Map: Displays loans distributed across states using colour intensity.
	Bar Chart: Shows loan counts by state.
o	Insight: Some states like California and Texas had significantly higher loan distributions.
________________________________________
Filters
1.	Loan Status: Filter to view data for loans categorized as Charged Off, Current, or Fully Paid.
2.	Grade: Filter to Analyse loans by borrower grade (A–G).

Insights
1. Total Loan Borrowers & Loan Repayment:
•	Insight: There are 38,574 total loan borrowers, with a cumulative repayment of $473.0M. However, the average loan defaulter rate is high at 14%, indicating significant risk in the portfolio.
•	Implication: This suggests a large portion of borrowers struggle to meet their repayment obligations.
________________________________________
2. Loan Defaulters by Employment Length:
•	Insight: Borrowers with over 10 years of employment (45 defaulters) have the highest default rates. Surprisingly, borrowers with less than one year of employment also have high defaults (16 defaulters).
•	Implication: Employment length does not consistently correlate with loan repayment reliability.
________________________________________
3. Loan Purpose by Income Level:
•	Insight: Loans for debt consolidation and credit card purposes dominate across all income levels. High-income borrowers typically take loans for major purchases, while low-income borrowers rely heavily on loans for debt consolidation.
•	Implication: Low-income borrowers may be struggling financially and are using loans to manage existing debts rather than for new opportunities.
________________________________________
4. Interest Rates by Loan Status:
•	Insight: Loans with medium interest rates had the highest count of issued loans 84%, but higher interest rates result in a significant proportion of loans being "charged off."
•	Implication: High interest rates may lead to higher default risks, especially for low-income borrowers.
________________________________________
5. Loan Distribution by State:
Project Scope:
Objective
This project focuses on analysing a loan dataset to identify patterns, optimize loan approval criteria, and evaluate loan performance based on borrower demographics, risk levels, and other key factors. Additionally, the goal is to visualize insights through an Excel dashboard.
Key Deliverables
•	Detailed analysis of loan performance by interest rates, loan status, and risk categories.
•	Recommendations for loan approval optimization and risk mitigation.
•	An Excel dashboard summarizing key metrics and KPIs.


Problem Statement:
Business Problem
TDI Financial needs to optimize its loan approval process to minimize default risks and maximize profitability. High default rates from risky borrowers, unclear patterns in approvals, and inefficient risk assessment criteria require targeted solutions.
Key Questions
•	Which borrower demographics and loan conditions are associated with higher default rates?
•	How do interest rates impact loan performance?
•	What patterns can be identified in loan approvals and rejections?
•	What KPIs should TDI monitor to optimize performance?

Data Cleaning and Transformation
1.	Import the Dataset:
o	Load the dataset into Excel.
2.	Handle Missing Values:
o	Identify and address missing values by either filling them with appropriate values or removing incomplete records.
3.	Remove Duplicates:
o	Identify and remove duplicate entries to ensure data accuracy.
4.	Correct Data Entry Errors:
o	Review the dataset for any data entry errors and correct them.
5.	Standardize Data Formats:
o	Ensure that all data is in a consistent format (e.g., dates, currency, percentages)

Additional Data Cleaning Steps:
•	Standardized Dates: Ensured all dates are in a consistent format.
•	Removed Blanks: Addressed blank cells in the dataset.
•	Proper Case: Converted employment titles to proper case.
•	Converted abbreviations to full names: Home Ownership (e.g., "O" to "Own", "R" to "Rent", "MO" to "Mortgage").
•	Verification Source Column: Standardized verification sources (e.g., "V" to "Verified", "SV" to "Source Verified", "Not V" to "Not Verified").
•	Used XLOOKUP and TRIM functions to convert state codes to full names.
•	Interest Rate and DTI to Percentage: Converted interest rates and debt-to-income ratios to percentage format.
•	Default Indicator: Created a default indicator using the formula:
excel
=IF(K2="Charged Off", 1, 0)
•	Income Segmentation: Segmented income using the formula:
excel
=IF(R3 >= 1000000, "High Income", IF(R3 >= 100000, "Medium Income", "Low Income"))
•	Interest Rate Segmentation: Segmented interest rates using the formula:
excel
=IF(U2 >= 20%, "High", IF(U2 >= 10%, "Medium", "Low"))


Dashboard Features:
KPI Section
1.	Total Loan Borrowers: Displays the total number of borrowers.
              38,574 borrowers.
2.	Total Loan Repayment: Shows the cumulative amount repaid.
             $473.0 million.
3.	Average Loan Amount: Displays the average loan amount issued.
             $435.7 thousand.
4.	Average Loan Defaulter Rate: Shows the average percentage of loans defaulted.
             14%.
5.	Average Interest Rate: Displays the overall average interest rate.
             12%.
________________________________________
Charts and Visualizations
1.	Loan Defaulters by Employment Length:
o	Bar chart showing the number of defaulters based on employment length.
o	Insight: Borrowers with employment lengths of 10+ years had the highest defaulters (45 cases).
2.	Loan Purpose by Income Level:
o	Horizontal bar chart categorizing loan purposes by income levels (High, Medium, Low).
o	Insight: Common purposes include debt consolidation, credit cards, and small business loans.
3.	Interest Rate by Loan Status:
o	Line chart comparing the number of loans across interest rate levels (High, Low, Medium).
o	Insight: Medium interest rate loans had the highest numbers 84%.
4.	Loan Distribution by State:
o	Two visualizations:
	Map: Displays loans distributed across states using colour intensity.
	Bar Chart: Shows loan counts by state.
o	Insight: Some states like California and Texas had significantly higher loan distributions.
________________________________________
Filters
1.	Loan Status: Filter to view data for loans categorized as Charged Off, Current, or Fully Paid.
2.	Grade: Filter to Analyse loans by borrower grade (A–G).

Insights
1. Total Loan Borrowers & Loan Repayment:
•	Insight: There are 38,574 total loan borrowers, with a cumulative repayment of $473.0M. However, the average loan defaulter rate is high at 14%, indicating significant risk in the portfolio.
•	Implication: This suggests a large portion of borrowers struggle to meet their repayment obligations.
________________________________________
2. Loan Defaulters by Employment Length:
•	Insight: Borrowers with over 10 years of employment (45 defaulters) have the highest default rates. Surprisingly, borrowers with less than one year of employment also have high defaults (16 defaulters).
•	Implication: Employment length does not consistently correlate with loan repayment reliability.
________________________________________
3. Loan Purpose by Income Level:
•	Insight: Loans for debt consolidation and credit card purposes dominate across all income levels. High-income borrowers typically take loans for major purchases, while low-income borrowers rely heavily on loans for debt consolidation.
•	Implication: Low-income borrowers may be struggling financially and are using loans to manage existing debts rather than for new opportunities.
________________________________________
4. Interest Rates by Loan Status:
•	Insight: Loans with medium interest rates had the highest count of issued loans 84%, but higher interest rates result in a significant proportion of loans being "charged off."
•	Implication: High interest rates may lead to higher default risks, especially for low-income borrowers.
________________________________________
5. Loan Distribution by State:
•	Insight: States like California and Texas have significantly higher loan distributions compared to others. However, default rates are also likely to be higher in these regions due to the sheer volume of loans.
•	Implication: These states could represent both high-opportunity and high-risk regions for loans.
________________________________________
Recommendations:
1.	Risk Mitigation Strategies:
o	Adjust loan approval criteria to include more robust credit score requirements, particularly for low-income and high-interest loans.
o	Implement stricter conditions for borrowers with short employment histories or provide smaller loan amounts to minimize default risk.
2.	Interest Rate Policy:
o	Offer incentives for low-interest loans to attract reliable borrowers and reduce default rates.
o	Cap interest rates for high-risk borrowers to prevent "charged off" loans.
3.	State-Specific Strategies:
o	Focus on targeted marketing and risk management in states like California and Texas to balance opportunity and risk.
4.	Loan Purpose Adjustments:
o	Encourage loans for productive purposes (e.g., education, business) over debt consolidation to enhance financial sustainability for borrowers.
________________________________________
Conclusion
The dashboard provides a clear picture of TDI's loan performance. While the organization serves a large number of borrowers and generates significant repayments, the default rate of 14% indicates a need for improved risk management strategies. By refining loan approval criteria, adjusting interest rates, and focusing on specific high-risk regions, TDI can enhance profitability while minimizing default risks.

•	Insight: States like California and Texas have significantly higher loan distributions compared to others. However, default rates are also likely to be higher in these regions due to the sheer volume of loans.
•	Implication: These states could represent both high-opportunity and high-risk regions for loans.
________________________________________
Recommendations:
1.	Risk Mitigation Strategies:
o	Adjust loan approval criteria to include more robust credit score requirements, particularly for low-income and high-interest loans.
o	Implement stricter conditions for borrowers with short employment histories or provide smaller loan amounts to minimize default risk.
2.	Interest Rate Policy:
o	Offer incentives for low-interest loans to attract reliable borrowers and reduce default rates.
o	Cap interest rates for high-risk borrowers to prevent "charged off" loans.
3.	State-Specific Strategies:
o	Focus on targeted marketing and risk management in states like California and Texas to balance opportunity and risk.
4.	Loan Purpose Adjustments:
o	Encourage loans for productive purposes (e.g., education, business) over debt consolidation to enhance financial sustainability for borrowers.
________________________________________
Conclusion
The dashboard provides a clear picture of TDI's loan performance. While the organization serves a large number of borrowers and generates significant repayments, the default rate of 14% indicates a need for improved risk management strategies. By refining loan approval criteria, adjusting interest rates, and focusing on specific high-risk regions, TDI can enhance profitability while minimizing default risks.

