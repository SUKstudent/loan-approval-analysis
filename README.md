# Loan Approval Analysis

## Project Overview
This project analyzes loan application data to explore loan approval patterns and identify applicant characteristics associated with approval outcomes.

Using Python and Power BI, the project examines the dataset through data quality checks, exploratory data analysis (EDA), and visualizations.

## Objectives
- Analyze the distribution of approved and rejected loan applications.
- Explore applicant demographics and financial characteristics.
- Check data quality, including missing values and duplicate records.
- Perform exploratory data analysis (EDA).
- Visualize patterns associated with loan approval status.
- Summarize key findings and conclusions.

## Dataset
The dataset used in this project is available on Kaggle:

[Loan Approval Classification Dataset](https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data)

The dataset contains 45,000 loan application records and 14 columns describing applicant characteristics, financial information, credit history, and loan status.

The target variable is `loan_status`:
- `0` — Loan Rejected
- `1` — Loan Approved

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook
- Power BI
- GitHub

## Project Workflow
1. **Data Loading:** Load the dataset into Python.
2. **Data Inspection:** Examine dataset dimensions, column names, and data types.
3. **Data Quality Checks:** Check for missing values and duplicate records.
4. **Exploratory Data Analysis:** Analyze loan approval outcomes and applicant characteristics.
5. **Data Visualization:** Create charts to explore patterns and distributions.
6. **Findings and Conclusion:** Summarize observations from the analysis.

## Project Files
- `loan_data.csv` — Dataset file.
- `Loan_Approval_Analysis.ipynb` — Python notebook containing data inspection, analysis, and visualizations.
- `Loan_Approval_Analysis.pbix` — Power BI dashboard, if included in the repository.

*Note: Ensure the filenames above match the files actually uploaded to the repository.*

## Key Questions
- What proportion of loan applications are approved or rejected?
- How do credit scores differ between approved and rejected applications?
- What income patterns can be observed across loan outcomes?
- Which applicant characteristics may be associated with loan approval status?

## Key Findings
- The dataset contains 45,000 loan applications: 22.22% were approved and 77.78% were rejected.
- Mean and median credit scores were similar for approved and rejected applications.
- Rejected applications had higher mean and median applicant incomes than approved applications.
- The maximum recorded income in the rejected group was substantially higher than in the approved group, indicating a value worth investigating further.

## Conclusion
The analysis identified differences in applicant income between approved and rejected loan applications, while credit score averages were similar. Further exploration of other applicant characteristics may provide additional insights into loan approval patterns.

## Disclaimer
This project is intended for educational and analytical purposes. Observed relationships in the data do not necessarily imply causation and should not be interpreted as a definitive basis for real-world lending decisions.
