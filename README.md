# Customer Data Cleaning & Quality Assessment

## Project Overview
This project demonstrates a practical customer data cleaning and quality assessment workflow using Google Sheets.

The objective was to identify inconsistent, missing, and duplicate information while preserving the original dataset.

## Tools & Functions
- Google Sheets
- TRIM and PROPER
- SUBSTITUTE
- IF
- COUNTIF and COUNTA
- COUNTUNIQUE
- Conditional Formatting

## Data Cleaning Process
- Standardized customer names and city names.
- Identified email addresses requiring validation and generated suggested corrections.
- Flagged missing phone numbers and customer status values.
- Detected duplicate customer IDs.
- Documented unresolved issues for client review.
- Created a data quality summary with automated calculations and conditional formatting.

## Data Quality Results

| Metric | Result |
|---|---:|
| Total Customer Records | 10 |
| Unique Customer IDs | 9 |
| Records Flagged as Duplicate | 2 |
| Missing Phone Numbers | 2 |
| Missing Status Values | 1 |
| Emails Requiring Review | 2 |
| Open Issues | 4 |
| Resolved Issues | 0 |

## Project Files
`P02_Customer_Data_Cleaning.xlsx` contains four worksheets:

- **Original_Data:** Unmodified source records.
- **Working_Data:** Data cleaning and validation formulas.
- **Issue_Log:** Documented issues requiring client clarification.
- **Data_Quality_Summary:** Summary metrics and conditional formatting.

## Key Learning
Data cleaning is not just correcting inconsistent values. It also involves preserving source data, identifying uncertain information, documenting issues, and presenting results clearly.

*This project uses a simulated dataset for portfolio and training purposes.*