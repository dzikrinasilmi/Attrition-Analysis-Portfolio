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
-	What factors influence employees’ decision to stay?

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
-	Customer service is the division with the highest attrition rate, 19.93%
-	The dominant cause of attrition in the Customer Service division is Low Salary, followed by Workload, and Poor Management.
### 2. What are the main reasons why employees leave the company?
-	Based on the “ReasonForLeaving” data from the dataset, the dominant reason that causes overall workers to leave the company is Workload, followed by Low Salary, Poor Management, Lack of Growth, and the last is Personal Reasons.
-	Low Salary and Workload are the 2 main reasons for high attrition in the company.
