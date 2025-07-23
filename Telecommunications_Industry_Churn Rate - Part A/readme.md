# Telecommunications_Industry Churn Rate Analysis Dashboard

This project analyzes customer churn in the telecommunications industry to identify patterns and factors driving customer attrition.
The analysis uses SQL for data extraction, cleaning, and processing, and Power BI for creating interactive visualizations to communicate insights effectively.
Objectives calculate churn rates and analyze key drivers of customer attrition.
Examine customer demographics, contract details, and service usage to understand churn behavior.
Provide actionable insights to improve customer retention strategies.

## Dataset
The dataset contains customer information from a telecommunications company, including: Demographics: Age, gender, marital status, dependents, location
Service Details: Contract type, tenure, monthly charges, payment method, offer status
Churn Details: Churn status (Yes/No), churn remark, satisfaction score

## Analysis Performed 

A. SQL Analysis: The following analyses were performed using SQL (see sql_scripts/analysis_queries.sql):
	1. Active vs. Inactive Customers: Compared churn rates between active and inactive customers.
	2. Contract Duration vs. Churn: Analyzed churn rates by contract duration (e.g., month-to-month, one-year, two-year).
	3. Top 10 Locations by Churn: Identified the top 10 locations with the highest churn rates.
	4. Tenure Category: Grouped customers by tenure (e.g., <6 months, 6-12 months, >12 months) and analyzed churn patterns.

B. Power BI Visualizations: The following visualizations were created in Power BI :
	1. Average Tenure: Displays the average tenure of customers, segmented by churn status.
	2. ARPU (Average Revenue Per User): Shows ARPU across churned and retained customers.
	3. Churn Rate: Visualizes the overall churn rate and trends over time.
	4. Churn Status: Breaks down customers by churn status (Yes/No).
	5. Payment Method: Analyzes churn by payment methods (e.g., credit card, bank transfer).
	6. Offer Status: Examines churn based on promotional offer status.
	7. Contract Type: Displays churn rates by contract type (e.g., month-to-month, annual).
	8. ABC Analysis by Revenue: Categorizes customers by revenue contribution (A: top 20%, B: next 30%, C: bottom 50%).
	9. Distribution by Demographics: Visualizes churn by gender, marital status, age, and dependents.
	10. Churn Rate by Top 10 Cities: Highlights churn rates for the top 10 cities.
	11. Churn Rate by Location & Revenue Top 10 Cities: Combines churn and revenue analysis by location.
	12. Satisfaction Score: Shows the relationship between satisfaction scores and churn.
	13. Churn Remark: Summarizes reasons for churn based on remarks.

## Tools and Technologies
	1. SQL: Data extraction, cleaning, and analysis using BigQuery
	2. Power BI: Interactive dashboards and visualizations.



## Future Improvements
1. Integrate predictive modeling (e.g., logistic regression) to forecast churn.
2. Automate data pipeline for real-time churn monitoring.


## Usage
- Clone this repository to access the raw data, Power Query scripts, DAX measures, and Power BI files.
- Use the provided visualizations to guide business decisions.
- Modify the dashboards, queries, or calculations as needed for updated data.

## Contributing
Feel free to fork this repository, submit pull requests, or raise issues for improvements or additional analyses.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions, reach out via 

LinkedIn - https://www.linkedin.com/in/varmaanil/
email - anilvarma230395@gmail.com
