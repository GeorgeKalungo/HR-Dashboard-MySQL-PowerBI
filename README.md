# HR-Dashboard-MySQL-PowerBI
An HR dashboard visualized using Power BI with data analyzed and cleaned using MySQL.

![HR Dashboard](HR%20Dashboard%20Screenshot.png "A snapshot of the dashboard")

### Sources of Data

- **Data Used** - HR data file with over 22000 records from the year 2000 to 2020.

### Technologies Used

- **Data Cleaning & Analysis** - MySQL
- **Data Visualization** - PowerBI

### Questions

1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at the headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed overtime based on hire and termination dates?
11. What is the tenure distribution for each department?

### Summary of Findings

- There are more male employees.
- The most dominant race in the workplace is White. The Native Hawaiian and American Indian are the least dominant.
- The oldest employee is 59 years old while the youngest is 22 years old.
- A large number of employees are in the (35-44) age group. The smallest number of employees are in the (18-24) age group.
- A large number of employees work at the headquarters than remotely.
- The average length of employment for terminated employees is around 8 years.
- The gender distribution across departments is fairly balanced but generally, there are more male than female employees.
- The Auditing department has the highest turnover rate while Marketing has the least turnover rate.
- Ohio has the largest number of employees while Wisconsin has the smallest.
- The net change in employees has increased over the years.
- The average tenure for each department is around 8 years, with Legal and Auditing departments having the highest turnover rate while HR, Business development and Marketing have the lowest.

### Limitations

- Some records had negative ages and they were excluded from the Querying. Ages used were 18 years and above.
- Some termination dates were far into the future and were not used during the analysis. The only termination dates used were those below or equal to the current date.

### Acknowledgments

This dashboard was created by following the tutorial by [Her Data Project](https://youtu.be/PzyZI9uLXvY?si=qJp2y59iwKddOpgv). A huge thanks to Irene for her clear guidance and valuable insights.
