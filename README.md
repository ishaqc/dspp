# Luxury Loan Analysis

## Objective  
The aim of this project is to analyse a luxury loan portfolio to identify patterns and risk factors influencing loan defaults. This analysis can provide actionable insights for optimising loan performance and mitigating financial risks.

## Tools & Techniques  
- **Tools**: Python, Jupyter Notebook, Excel  
- **Techniques**: Exploratory Data Analysis (EDA), Feature Engineering, Logistic Regression, Decision Trees  

## Process  
1. **Data Cleaning**:  
   - Removed missing or inconsistent values.  
   - Standardised numerical fields like loan amount, income, and duration.

2. **Exploratory Data Analysis (EDA)**:  
   - Analysed loan size, income distribution, and default patterns.  
   - Created visualisations (histograms, boxplots, and correlation matrices) to detect relationships between variables.

3. **Feature Engineering**:  
   - Added new metrics such as **loan-to-income ratio** and **debt-to-asset ratio**.  
   - Prepared the dataset for model training.

4. **Model Development**:  
   - Selected **Logistic Regression** to predict loan defaults.  
   - Evaluated model performance using **accuracy**, **precision**, **recall**, and **F1 score**.

## Results  
- Strong correlations were observed between loan default rates and factors like **loan size**, **loan duration**, and **debt-to-income ratio**.  
- The logistic regression model effectively identified high-risk loans.  

## Key Insights  
- High loan-to-income ratios significantly increase the likelihood of default.  
- Customer income and loan duration were critical predictors of loan risk.  

## Recommendations  
1. Enhance customer segmentation based on risk factors identified in the analysis.  
2. Incorporate economic indicators, such as interest rates or inflation, to improve the model.  
3. Periodically update the model with new loan data to maintain accuracy and relevance.
