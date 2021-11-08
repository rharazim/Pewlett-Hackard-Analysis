# Pewlett-Hackard-Analysis
Module 7

## Overview
We have been helping our friend and coworker Bobby conduct an anlysis on the company's aging workforce to see how many current employees are retirement age, and how many are eligible to become a mentor for the newer generation of employees. We have been using PostgreSQL to import employee data into tables and to write queries that will answer management's questions about their employees. The company is worried about a "silver tsunami" where it may lose many of its retirement-age employees. We needed to help management find the exact number of employees that meet this criteria and which job titles they will need to make an effort to fill in the near future.


## Results
- About 90,000 employees will be retirement age at the time of this analysis
- Of those 90,000 employees, about 45,000 are engineers of varying seniority levels
- Therefore, management will need to focus hiring efforts about 50% on new engineers and 50% on other staff roles
- There are 1,549 employees who are eligible to become a mentor for the newer generation of employees


## Summary
Pewlett Hackard will need to fill up to 90,000 roles as a result of the "silver tsunami." These roles vary in department and title, about 50%$ of the retiring employees are engineers. So, the company will have to focus hiring efforts especially on new engineers.

There are only 1,549 employees who are eligible to become mentors for the replenished workforce, while new hires may be well up to 90,000 employees. This means the company does not have nearly enough mentors to work with the new hires, but it may consider having multiple mentees per mentor. 

Two additional queries/tables for further analysis:
We could filter the unique titles table by department to see which departments will need to hire the most new employees as a result of current employees hitting retirement age. It would not be too early to start devoting resources to those departments.

We could expand the number of qualified mentors by querying instead for time spent at the company equaling ten or more years. This would then include non-retiremnt age employees who would also be suited to mentor new hires.

