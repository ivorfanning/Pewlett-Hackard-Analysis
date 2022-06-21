# Pewlett-Hackard-Analysis

## Project Overview

The purpose of this project is on behalf of Human Resources Department in Pewlett_Hackard company, to analyz the number of retiring employees and number of job opening in the future. To figure out the best way to arrange the employees going to be retired, the company will set up a mentorship program, we need to filter the candidates our from the given condition from current employees, in order to support the company decisions.

## Resources
-Data: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

-Software: Postgres, pgAdmin4

## Results
1. With the first review of creating a list of potential "silver tsunamis," the query resulted in many duplicates due having multiple positions.

2. Using the 'distinct on' SQL script, the duplicates were removed leaving the most recent job title to create a unique list of retiring employees.

3. Retiring Counts by Title for a total of 90,398 potential retirees.

4. Mentor Eligibility List of 1549 employees born in 1965.

## Summary

Our retiring_titles shows us the a majority of the employees of retirment age (57,668/90,398 = 64%) have senior titles.
Seeing the 63 % of the workforce is either retirment or mentorship eligible there will most likely be many positions to fill over the next 5-10 years. There may not exactly be enough people in the workforce to take care of the tasks or even come close to the amount of experience to fill these roles so quickly but what companies can do is try to best learn about what these employees did to be so successful/ having such long lasting careers to continue the tradition for future employees. Most likely the future generation is more computer savy/ efficent due to technologies and can catch on quickly helping companies continue to trend in the right direction by keeping revenues up.
