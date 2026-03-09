Overview:
DDSAnalytics was hired by Frito Lay to identify the key factors driving employee attrition and build predictive models to help the company proactively retain employees. Using a dataset of 1470 employees and across a wide variety of variables, we performed exploratory data analysis and built KNN and Naive Bayes classification models to predict which employees are most likely to leave.

Top 3 Factors Related to Attrition:
Overtime — Employees who work overtime have a 31.7% attrition rate compared to just 9.7% for those who do not. This was the single strongest categorical predictor.
Job Involvement — Employees with low job involvement had a 46.8% attrition rate compared to just 8.6% for those with very high involvement. Engaged employees are far more likely to stay.
Monthly Income — Employees who left had significantly lower monthly incomes than those who stayed. Lower compensation is a strong driver of attrition.

Model Performance:

KNN Model:
Accuracy: 83.03%
Sensitivity: 66.67%
Specificity: 83.49%

Naive Bayes Model:
Accuracy: 85.32%
Sensitivity: 60.00%
Specificity: 90.16%

Both models meet the required threshold of at least 60% sensitivity and 60% specificity. The Naive Bayes model is recommended as the primary model due to its higher accuracy and specificity.

Business Impact:
Replacing an employee costs between 50% and 400% of their annual salary. With an average salary of $76,683 at Frito Lay, proactive retention using our Naive Bayes model could save the company between $798,172 and $6,434,372 by targeting at-risk employees with a $200 retention incentive.

Additional Findings:
Gender and Relationship Satisfaction showed no significant relationship with attrition
Stock Option Level was a strong predictor — employees with no stock options had much higher attrition rates
Marital Status was significant — single employees had higher attrition rates than married or divorced employees

Link to Youtube: 
https://youtu.be/9Q0orRQZbNo
