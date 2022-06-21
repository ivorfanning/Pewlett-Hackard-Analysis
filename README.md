# Pewlett-Hackard-Analysis

## Project Overview

The purpose of this project is on behalf of Human Resources Department in Pewlett_Hackard company, to analyz the number of retiring employees and number of job opening in the future. To figure out the best way to arrange the employees going to be retired, the company will set up a mentorship program, we need to filter the candidates our from the given condition from current employees, in order to support the company decisions.

At the beginning, I create a ERD to visualize the relationship of each data file:

![ERD](https://github.com/ivorfanning/Pewlett-Hackard-Analysis/blob/main/Result%20Pictures/QuickDBD-export.png)

## Resources
-Data: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

-Software: Postgres, pgAdmin4

## Results
1. With the first review of creating a list of potential "silver tsunamis," the query resulted in many duplicates employee due to they may get promoted after their first title, so those employees have multiple titles.

![silver](https://github.com/ivorfanning/Pewlett-Hackard-Analysis/blob/main/Result%20Pictures/silver.png)

2. After using the 'distinct on' method, the duplicates data were removed, and the most recent job title remained.

![silver unique](https://github.com/ivorfanning/Pewlett-Hackard-Analysis/blob/main/Result%20Pictures/silver_unique.png)

3. Retiring Counts by Title for a total of 90,398 potential retirees.

![unique title](https://github.com/ivorfanning/Pewlett-Hackard-Analysis/blob/main/Result%20Pictures/Unique%20Titles.png)


4. create a mentor eligibility table for those employees were born in 1965.

![mentorship](https://github.com/ivorfanning/Pewlett-Hackard-Analysis/blob/main/Result%20Pictures/metorship.png)

## Summary

From the retiring_titles, it shows us the a majority of the employees of retirment age (57,668/90,398 = 64%) have senior titles, so there will be many positions to be filled in the future years. There might be lack of employees in the workforce to take care of the tasks. Therefore the company could try to implentment the mentorship program so let the retiring employees can be mentors for the new workers. The mentor candidates can be selected from the experienced employeed in the above last pictures.
