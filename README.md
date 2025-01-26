# SHOPPING MALLS SALES ANALYSIS

I carried out this analysis in SQL, where the data cleaning, data manipulation and analysis were done to extract key insights from the data. 
And then the insights were visualized using Power BI.

## PROJECT OBJECTIVES
1. Data loading and cleaning
2. Calculate basic statistics
3. Analyze consumer demographics
4. Analyze sales trend over time
5. Presenting findings through visualizations.

## DATASET USED
## STEPS TAKEN TO PREPARE DATA FOR ANALYSIS
1. I removed trailing spaces in the 'Invoice_date' column using the LTRIM and RTRIM functions in SQL.
2. I created a new 'Date_Of_Invoice' column using the 'ALTER TABLE' clause.
3. I populated the new column with the values in the 'Invoice_date' column using the 'UPDATE' Clause. During the process of populating the new column, I converted the Data Type of the old column from 'Character' to 'Date' data type.
4. I also created two new columns to seperate the 'Month' and 'Year' Of the 'Date_Of_Invoice', then populated them with values from the 'Date_Of_Invoice' column using the 'UPDATE' and 'FORMAT' clauses.


   ## KEY QUESTIONS
   1. What is the total Revenue from sales?
   2. What is the total number of customers in the sample?
   3. What is the Average number of items purchased per transaction?
   4. How much revenue were generated from different categories of items
   5. What is the total Revenue generated by different shopping malls
   6. Which age group has the highest spending?
   7. What is the Average spending by gender?
   8. What is the Revenue growth over time(Month-On-Month and Year-On-Year)?

  ## DASHBOARD

  ![powerBI Dashboard](https://github.com/user-attachments/assets/5e6c60e2-bb06-4cf5-a7f2-cbdd77966ea7)

   
    In Conclusion, This analysis reveals how customer behaviours can affect sales in the shopping malls and it helps stakeholders in decision making that will optimize sales and increase revenue in the shopping malls
