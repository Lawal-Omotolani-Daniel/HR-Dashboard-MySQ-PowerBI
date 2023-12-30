# HR-Dashboard-MySQ-PowerBI

![HR DASHBOARD ](https://github.com/Lawal-Omotolani-Daniel/HR-Dashboard-MySQ-PowerBI/assets/155084512/d0d30c86-638d-4cdc-8576-b38e2907663c)

### Data Used
---

Data - HR Data with over 22000 rows from the year 2000 to 2020.

Data Cleaning & Analysis - MySQL, Jupyter Notebook(sql magic). 

Data Visualization - PowerBI.

### Questions
---

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquaters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job title in the company?
8. which department has the highest turnover rate?
9. what is the distribution of employees across locatins by state?
10. how has the company's count changed over time based on hire and term dates? 
11. What is the tenure distribution for each department?

### Summary of Finding
---
- There are more employees.
- White race is the most dominant while Native Hawaiian and American Indian are the least dominant.
- The youngest employee is 20 years old and oldest is 57 years old.
- 5 age groups were created (18-24, 25-34, 35-44, 45-55, 55-64). A large number of employees were between 25-34 followed by 35-44 while the smallest group was 55-64.
- A large number of employees work at the headquaters versus remotely.
- The average length of employment for terminated employees is around is 7 years.
- The gender distribution across departments is fairly balanced but there are generally more male than female employees.
- The Marketing department has the highest turover rate followed by Training. The least turn over rate are in the Research and development, Support and Legal departments.
- A large number of employees come from from the state of Ohio.
- The net change in employees has increased over the years.
- The average tenure for each department is about 8 years with Legal and Auditing having the highest and Services, Sales and Marketing having the lowest.

### Limitations
---

- Some records had negative ages and these were excluded during querying(967 records). Ages used were 18 years and above.
- Some termdates were far into the future and were not included in the analysis(1599 records). The only term dates used were those less than or equal to the current date.





