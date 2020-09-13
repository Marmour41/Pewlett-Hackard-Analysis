# Pewlett-Hackard-Analysis

## Overview of the Analysis
The purpose of this analysis was to assist Bobby's manager understand the impact of the "silver tsunami" will have on Pewlett-Hackard. Using SQL, we were able to identify the total employees retiring, and how they are broken down by department, among other things. Additionally, Bobby's manager tasked us with determining the number of retiring employees per title, and the number of employees who are eligible to participate in a mentorhisp program. 

## Results
The first task Bobby's manager gave us was to determine the number of retiring employees per title. As you can see from [Retiring by Title](retiring_titles.png) there are major items we need to discuss with Bobby's manager:
- A total of 57,668 employees that are retiring have "Senior" titles.
- A total of 45,397 employees that are retiring have "Engineer" titles.
- Only 2 "Managers" are retiring. 

From the [Eligible Mentorhisp](mentorship_eligibility.png) analysis:
- There are 1,549 employees are eligbile for the mentorship program. 

## Summary

In order to look at a more short-term effect the "silver tsunami" will have on the company, I refactored the *Retiring by Title* query to only look at the first year of the retirement eligible employees (January 1, 1952 to December 31, 1952). Based on this query, Pewlett-Hackard will need to fill 21,209 roles as the "silver tsunami" begins to make its impact. 

