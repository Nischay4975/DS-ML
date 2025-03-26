## Why are Employees Leaving? Understanding Employee Attrition Through Data ##
### Introduction ###
Employee attrition is a critical challenge for organizations striving to maintain a stable and productive workforce. This analysis delves into key factors influencing employee turnover, using **exploratory data analysis (EDA)** to uncover meaningful patterns. By examining attributes such as **job satisfaction, salary levels, promotions, work hours, and project workload**, this report aims to provide **data-driven insights** into why employees leave and what can be done to improve retention.

Through **visualizations and statistical analysis**, I identified trends that distinguish employees who stay from those who exit. The goal is to **equip decision-makers with actionable insights** to enhance employee engagement, optimize HR policies, and foster a more resilient workforce.
### The Dataset ###
File can be found in the repository under the name 'Why are employees leaving.csv'
The dataset contains the list of employees in the payroll of a company with various columns that define each of them. Various columns and their meanings are as follows
* ID => Just an ID to represent an employee. Its just a serial number to prevent any PII leaks.
* left => Did the employee leave. 0 means no and 1 means yes
* satisfaction_level => Employee's satisfaction level as per self-evaluation. Its a number between 0 and 1
* last_evaluation => Measure of their performance as per their supervisors. Its a number between 0 and 1
* number_project => Number of projects the employee is working on.
* average_monthly_hours => Average Hours clocked every month.
* time_spend_company => Number of years passed since the employee has joined the company.
* work_accident => Has the employee faced any workplace accident during his tenure in the company. Boolean value with 0 meaning No and 1 meaning Yes
* salary => Salary has been categorised into 3 brackets/ bins namely 'low', 'medium', 'high'
* division => Division that the employee belongs to.
* promotion_last_5years => Boolean measure to represent whether the person has gotten any promotions in the last 5 years.
