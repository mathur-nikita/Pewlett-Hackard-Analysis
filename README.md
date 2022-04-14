# Pewlett-Hackard-Analysis

## Overview

Pewlett Hackard is looking to the future as the Baby Boomer generation is starting to retire, leaving thousands of vacancies within the company.  As part of employee research, HR Analyst Bobby has been tasked to determine who will be retiring in the next few years and how many positions will need to be filled.  We are helping Bobby build an employee database to help with this analysis, and specifically need to complete the following tasks:
1) Determine the number of retiring employees per job title
2) Identify employees who are eligible to participate in a mentorship program

We then need to prepare a report that summarizes the findings of our analysis.

## Results

- There are a total of 72,458 employees at Pewlett Hackard approaching retirement.

![retiring_total_count.PNG](https://github.com/mathur-nikita/Pewlett-Hackard-Analysis/blob/main/images/retiring_total_count.PNG)

- The majority of the roles that will need to be filled are Senior Engineers, followed by Senior Staff.
- Two managers are approaching retirement.                                                
                   
![retiring_title_counts.PNG](https://github.com/mathur-nikita/Pewlett-Hackard-Analysis/blob/main/images/retiring_title_counts.PNG)

- A total of 1,549 employees are currently eligible to participate in a mentorship program.

![mentorship_eligibility_count.PNG](https://github.com/mathur-nikita/Pewlett-Hackard-Analysis/blob/main/images/mentorship_eligibility_count.PNG)

## Summary

1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?
As determined in the results section earlier, a total of 72,458 roles will need to be filled.

2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
There are a total of 1,549 who are approaching retirement based on the criteria of being born in 1965 who are eligible to become mentors.  However Pewlett Hackard currently has thousands of employees and it's not reasonable to say that 1,500 employees can train or mentor that many people.

Some suggestions:

1) The current criteria for identifying employees who could be mentors is only limited to those born in 1965.  It's possible that we can increase the amount of eligible employees if we expand this date range within our query to include more people.
2) We could create queries that are specific to employees who are not nearing retirement and fit at least one of the following criteria:
- have gone through at least two job title changes 
- have been with the company for a minimum of 5 years

We could then use this information to help build an on-going mentorship program that won't be strained/abruptly end as currently eligible employees retire.  This information could also be useful in considering job vacancies being filled internally, allowing employees with more experience a chance to make lateral and upward moves in the company.
