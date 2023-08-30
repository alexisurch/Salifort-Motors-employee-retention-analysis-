    Problem Statement: Employee Retention Prediction
🏢 Business Scenario:
Salifort Motors has recently received the results of an employee survey it carried out as a step in solving it’s problem of high employee churn. As a part of the data team, our mission is to analyse the survey data and develop a model that accurately predicts whether an employee will leave the company. We are focusing on key variables like department, number of projects, average monthly hours, and other relevant data points to gain valuable insights.

📝 Steps Taken:
1. Checked the distribution of the dataset and carried out necessary data cleaning while also refining column names for clarity.
2. Addressed outliers in the work duration column to improve data integrity.
3. Visualized the relationships between various variables to gain deeper insights into the factors contributing to high employee churn.
4. Analyzed the correlation between each variable using a correlation heatmap to identify significant patterns.
5. Leveraged the logistic regression model for building a predictive model tailored to our analysis.

Conclusion:
The model's performance was evaluated using various metrics. It achieved an accuracy of 83%, indicating its overall performance is reasonable. However, the precision and recall for the "Predicted would leave" class were relatively lower, at 80% and 83% respectively. This indicates that the model struggles to correctly identify instances of the "Predicted would leave" class, leading to the lower precision and recall values for this class. The model performed well in predicting the "Predicted would not leave" class with high precision and recall.
 
📊 Data Snapshot:
Number of rows: 14,999
Number of columns: 10
Data source: Kaggle

                            Recommendation  

Recommendation:
Based on the finding of the analysis, the following recommendation were made on how increase the employee retention of Salifort Motors.
1) Consider promoting employees who have been with the company for atleast four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
2) Either reward employees for working longer hours, or don't require them to do so.
3) If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.
4) Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
5) High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort.

