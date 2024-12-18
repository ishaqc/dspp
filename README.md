# Faster Payments Reconciliation

## Objective  
The goal of this project was to reconcile Faster Payments statements provided by NatWest Bank with the internal ledger entries at C. Hoare & Co. Bank. This project aimed to automate the reconciliation process, ensuring accuracy, improving efficiency, and enhancing compliance with financial regulations.

## Tools & Techniques  
- **Tools**: SQL, Oracle Database, Microsoft SQL Server, Power BI  
- **Techniques**: ETL Pipeline (Extract, Transform, Load), Data Cleaning, Data Validation, Reconciliation Reporting  

## Process  
1. **Data Extraction**:  
   - Extracted two distinct datasets:  
      - **NatWest Statements**: Sourced via SQL queries from the Oracle database.  
      - **Internal Ledger Data**: Queried from the bank's internal payments table.  

2. **Data Transformation**:  
   - Cleaned the extracted datasets by handling:  
     - Duplicate entries  
     - Missing values  
     - Rejected and erroneous transactions  
   - Standardised fields for alignment (e.g., date formats, transaction references).

3. **Reconciliation Process**:  
   - Compared the two datasets to match transactions and identify discrepancies.  
   - Applied SQL-based matching logic to detect:  
     - Entries with exact matches  
     - Outstanding breaks (unmatched transactions)  

4. **Data Loading and Reporting**:  
   - Loaded the cleaned and reconciled data into **Power BI**.  
   - Developed an interactive dashboard to monitor reconciliation progress and outstanding breaks.  

## Results  
- **Efficiency Gains**: Processing time reduced by 40% through automation.  
- **Improved Accuracy**: Enhanced data quality reduced discrepancies by identifying unmatched entries early.  
- **Real-Time Insights**: Interactive Power BI dashboard enabled management to monitor the reconciliation process effectively.

## Key Insights  
- Most outstanding breaks were caused by timing differences and incomplete transaction details.  
- Regular automation significantly reduced manual intervention, improving operational efficiency.

## Recommendations  
1. **Anomaly Detection**: Implement a machine learning model to identify potential discrepancies automatically.  
2. **Data Lineage**: Improve transparency by documenting the data flow and transformation processes.  
3. **Timing Adjustments**: Allow for reconciliation margins to accommodate cut-off delays in bank statements.  
4. **Continuous Improvement**: Periodically audit the process to address new challenges and improve pipeline performance.  

## Business Impact  
This project aligns with the bank’s strategic goals of being **faster, simpler, and better** by:  
- Reducing manual workload and errors.  
- Providing accurate and real-time insights for decision-making.  
- Ensuring compliance with financial regulations and data governance policies.  
