# Executive Summary - Frito Lay Employee Attrition Analysis

DDSAnalytics, a leader in talent management solutions for Fortune 100 companies, was commissioned by Frito Lay to analyze employee attrition. The primary objectives were to identify key factors contributing to employee turnover, develop predictive models to anticipate attrition, and assess the financial implications of these models. Understanding these drivers enables Frito Lay to implement targeted retention strategies, thereby reducing turnover-related costs and maintaining a stable workforce.

# Factors Significantly Related to Attrition

Our analysis identified three primary factors significantly associated with employee attrition:

OverTime: Employees who frequently worked overtime exhibited higher attrition rates, suggesting potential burnout or work-life imbalance. Employees who worked overtime were 70% more likely to leave the company compared to those who maintained standard work hours. This aligns with existing research indicating that excessive work hours contribute to stress and dissatisfaction, leading employees to seek positions with better work-life balance.

JobInvolvement: Employees with lower job involvement scores exhibited significantly higher attrition rates. Those with low job involvement were 40% more likely to leave compared to highly engaged employees. This suggests that employees who feel disconnected from their work or perceive their contributions as undervalued are at greater risk of turnover. Addressing job involvement through improved engagement strategies, recognition programs, and career development opportunities could help mitigate attrition.

MaritalStatus: Marital status appeared to influence attrition, with single employees showing a 25% higher likelihood of leaving compared to married employees. This could be attributed to greater career mobility among single employees or a higher inclination to seek new opportunities that align with personal goals.

These insights align with existing literature that emphasizes the impact of work-life balance and job satisfaction on employee retention.

## Work-Life Balance and Job Satisfaction on Employee Retention

Employee retention is a multifaceted challenge influenced by various personal and professional factors. Two of the most critical determinants—work-life balance and job satisfaction—have been extensively studied in human resource literature, consistently proving to be key drivers of employee turnover.

## Work-Life Balance and Its Role in Retention

Work-life balance refers to an individual’s ability to effectively manage work responsibilities while maintaining personal and family commitments. When employees experience high levels of work-related stress, extended hours, and frequent travel, they may feel overwhelmed, leading to dissatisfaction and, eventually, higher turnover.

According to the Society for Human Resource Management (SHRM) and various organizational studies, employees who perceive a poor work-life balance are significantly more likely to leave their jobs in search of roles that offer flexibility, reduced stress, and more manageable workloads.

Our study supports this trend, revealing that employees with frequent overtime obligations exhibited higher attrition rates. While overtime may sometimes be necessary due to business demands, persistent overwork without sufficient recovery time can contribute to burnout, disengagement, and eventually, resignation. Organizations that actively promote work-life balance—through flexible scheduling, remote work options, and workload management strategies—tend to retain employees at a significantly higher rate.

## Job Satisfaction and Employee Retention

Beyond work-life balance, job satisfaction is another crucial predictor of attrition. Job satisfaction encompasses multiple factors, including compensation, recognition, career growth opportunities, relationships with colleagues and management, and overall alignment with company culture.

Studies show that employees who feel undervalued, unchallenged, or unsupported by their employers are more likely to seek opportunities elsewhere. Our analysis found that specific job roles experienced higher attrition rates, suggesting that certain positions may be more prone to dissatisfaction, whether due to lack of advancement opportunities, unmanageable workloads, or mismatches between employee expectations and job realities.

Furthermore, we observed that single employees were more likely to leave compared to their married counterparts. This may be due to a higher level of career mobility among single professionals, who may feel less anchored to a specific job or location. Additionally, single employees might place a stronger emphasis on career progression, seeking new roles that offer greater satisfaction and professional growth.

# Model Performance: K-Nearest Neighbors (KNN) vs. Naive Bayes (NB)

Two predictive models were developed to forecast employee attrition. The following table compares their key performance metrics:

## K-Nearest Neighbors Model

Accuracy = 79%

Sensitivity = 83%

Specificity = 61%

## Naive Bayes Model

Accuracy = 73%

Sensitivity = 75%

Specificity = 61%

The KNN model demonstrated higher sensitivity, making it more effective at identifying employees who are likely to leave the company.

Both models performed similarly in terms of specificity (61%), meaning their ability to correctly classify employees who are likely to stay was comparable.

The KNN model’s higher accuracy (79%) compared to Naive Bayes (73%) indicates a better overall performance in predicting attrition cases correctly.

Given the KNN model’s higher accuracy and superior ability to capture employees at risk of leaving, it was selected as the preferred model for Frito Lay’s attrition forecasting.

# Costs of Attrition

Based on our predictive modeling and cost assumptions, attrition costs for Frito Lay are estimated as follows:

Total Cost of Attrition Misclassification: $255,000 per evaluation cycle, based on model-calculated False Negatives and False Positives.

Estimated Annual Savings Potential: If predictive modeling helps prevent 100 unnecessary turnovers per year, the estimated savings would be $1,000,000 annually ($10,000 per prevented turnover).

This cost of $255,000 per cycle underscores the financial impact of misclassified attrition cases, where failing to retain employees results in high replacement costs, while misallocating retention incentives leads to unnecessary expenditures. By leveraging our KNN model to reduce false negatives, Frito Lay can significantly lower attrition-related expenses and improve workforce stability.

# Conclusion and Recommendations

We appreciate the opportunity to support Frito Lay in this critical analysis. To further enhance employee retention, we recommend:

Implementing Flexible Work Arrangements: Addressing the high attrition among employees with frequent overtime by promoting work-life balance.

Conducting Job Role Evaluations: Assessing roles with high turnover to identify and mitigate underlying issues.

Developing Targeted Retention Programs: Creating initiatives tailored to specific demographics, such as single employees or those in high-turnover departments.

Enhancing Employee Engagement Programs: Investing in mentorship programs, employee recognition initiatives, and professional development to increase job satisfaction.

By adopting these strategies, Frito Lay can mitigate attrition risks, reduce associated costs, and foster a more engaged and stable workforce.

