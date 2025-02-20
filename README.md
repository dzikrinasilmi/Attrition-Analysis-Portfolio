# Attrition-Analysis-Portfolio
## Introduction
Attrition Analysis is an analytical process that aims to understand the rate of loss of customers, employees, or members within an organization or business over a specific period.
### Key Components in Attrition Analysis
-	Attrition Rate : the ratio of lost employees or customers to the total population over a certain period of time.
Formula: (number of individuals leaving / total number of individuals at the beginning of period) x 100
-	Segmentation: categorizing data based on certain factors to find specific patterns (ex: age, location, customers category, etc)
-	Root Cause Analysis: Identify the main reasons for attrition
-	Prediction and Prevention: Utilize analytical model to predict the risk of loss and recommend a preventive steps

## Study Case
### Objective
PT. Creativa Solusi faced a high employee attrition rate (18% per year), especially in the product development and customer service divisions, exceeding the industry average (12%). This issue impacts productivity, recruitment costs, and the company's competitiveness in delivering quality products.
### Business Problem
High employee attrition rate caused several business problems
-	Increased operating costs
-	Decreased productivity
-	Decreased productivity satisfaction
-	Low employee morale
### Questions
-	Which division has the highest attrition rate?
-	What are the main reasons why employees leave the company?
-	Are there any particular patterns in the attrition data?
-	What is the impact of a high attrition rate?

## Dataset
<a href="https://github.com/dzikrinasilmi/Attrition-Analysis-Portfolio/blob/main/PTKreativaSolusi.csv">Dataset</a>

Dataset Explanation
-	Employee ID: a unique ID for each employee. Used as an identifier to distinguish one employee from another.
-	Division: the division in which the employee works (Product Development, Customer Service, Sales, HR)
-	Attrition: status of whether the employee is still working in the company (Yes: has left the company, No: still working)
-	Reason For Leaving: the reason why employees leave the company
  (Low salary: Employees feel that the salary is too low,
  Workload: the workload is too high,
  Poor management: problems with management,
  Lack of growth: there is no opportunity to grow,
  Personal reasons)
-	Job Satisfaction: the level of employee satisfaction with their work (scale 1 – 5, very dissatisfied to very satisfied)
-	Customer Complaints: the number of customer complaints related to their employees or divisions 
-	Productivity Score: employee productivity score, measured on relative scale (higher values indicate better productivity)
-	Workload Score: employee workload score, measured on a relative scale (higher values indicate heavier workloads)
-	Morale Score: employee moral score, measured on a relative scale (higher scores indicate better work morale)

## Result
### 1. Which division has the highest attrition rate?
-	Customer service is the division with the highest attrition rate, 19.93% ![Att_Rate_Div](https://github.com/user-attachments/assets/c77fd16d-ca7b-49ec-9a3a-43b2cc5ea89b)
-	The dominant cause of attrition in the Customer Service division is Low Salary, followed by Workload, and Poor Management ![reason_att_CS](https://github.com/user-attachments/assets/cce75bc2-7a87-487d-bf3f-d8dfeba3bd65)
### 2. What are the main reasons why employees leave the company?
-	Based on the “ReasonForLeaving” data from the dataset, the dominant reason that causes overall workers to leave the company is Workload, followed by Low Salary, Poor Management, Lack of Growth, and the last is Personal Reasons.
-	Low Salary and Workload are the 2 main reasons for high attrition in the company.
![overall_reason_att](https://github.com/user-attachments/assets/8c8b60e9-a562-4651-83e1-4bcff270aea1)
### 3. Are there any particular patterns in the attrition data?
The visualization results of the relationship between turnover status and various factors such as job satisfaction, workload score, morale score, and productivity score are as follows
-	Turnover employees tend to have lower job satisfaction.
-	The workload of employees who experience turnover tends to be higher.
-	Employees who leave the organization appear inferior to those who remain in the organization.
-	There is not too much difference in the pattern of productivity scores, but employees who continue to work are slightly more productive.
![patterns](https://github.com/user-attachments/assets/a5436184-6e6f-4d8f-8df3-cd33c88354c3)
### 4. What is the impact of a high attrition rate?
One of the impacts of a high attrition rate is an increase in employee operating costs.
Based on the following assumption:
-	Recruitment cost per employee: Rp200.000
-	Training cost per employee: Rp1.000.000
-	Number of employees experiencing attrition: 2 employees per month
-	
Then, there is an increase in costs as follows:
-	Total cost per employee = Rp200.000 + Rp1.000.000 = Rp1.200.000
-	With the assumption 2 employees that experiencing attrition per month
Rp1.200.000 x 2 = Rp2.400.000
-	Then the operating costs per month is Rp2.400.000, while the annual cost is Rp28.800.000

## Insight
-	High attrition rates can reduce the capacity to produce goods on time and lower the company's reputation in the labor market.
-	Losing employees can have operational impacts such as lower labor productivity and efficiency.
-	High operational costs can eat up a portion of costs that could otherwise be allocated to other activities.
-	Decreased productivity and customer satisfaction can impact long-term profitability.

## Recommendation
-	Redistribute workload to reduce worker pressure, especially in divisions with a high average workload score.
-	Adjusting salaries to the industry average to retain talent.
-	Improving morale and creating clear career paths to increase employee motivation.
-	Analyzing and monitoring data on an ongoing basis, as well as conducting surveys to get direct feedback from employees.
