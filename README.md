# Pewlett-Hackard-Analysis
SQL analysis of retirment age employees for Pewlett Hackard

## Overview
This project used Postgres SQL in order to analyze employee data and determine which employees were about to retire, what titles they hold and the employees in that group that would be eligible for a mentorship progrram.

## Results
The analysis of retirment aged employees shows the following:
- The majority of the employees that are retiring soon are either Senior Engineers or Senior Staff.
- There are a total of 72,458 employees that are eligible for retirment in the next 3 yearrs.
- Of the roughly 72,000 employees that are retiring only about 1,550 are eligible for the mentorship program
- There were a lot of duplicates when joining data sets, with a lot of the employees having multiple titles in the _retirement_titles_ table.

## Summary
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
- The team will need to fill about 100,000 senior roles since there are about 50,000 of each Senior Enigneers and Senior Staff.

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
- No, I do not believe that 1550 employees will be able to properly mentor the amount of employees that will need to be trained to help pick up the difference for the retiring employees.

What other queries or tables could help in this analysis?
- One table that would be helpful in order to check for mentors is a table that checks a larger set of employees other than just the ones that were born in 1965. There are likely more employees that could help here and expanding the range of mentorship would help fill in the gaps.
- On the other side of looking for retirement aged employees, it would be good to create a table of employees that are the right age to be mentored, or new to the company and workforce in general.
