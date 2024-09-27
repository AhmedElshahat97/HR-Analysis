
# HR Analysis Dashboard (1989 - 2022)

![Project2 - HR Analysis_page-0001](https://github.com/user-attachments/assets/915434cc-2f4f-4dcf-93d9-22c730994b90)
![Project2 - HR Analysis_page-0002](https://github.com/user-attachments/assets/d3867845-07bc-4215-9d36-a78db6fbeea8)
![Project2 - HR Analysis_page-0003](https://github.com/user-attachments/assets/8809af9f-593a-49af-9075-c8a75cee1088)
![Project2 - HR Analysis_page-0004](https://github.com/user-attachments/assets/0e684277-dbc5-4a95-b46b-0cbc2598bb1c)
![Project2 - HR Analysis_page-0005](https://github.com/user-attachments/assets/d9a266e5-2e95-43c0-b547-d0cadc6858db)
![Project2 - HR Analysis_page-0006](https://github.com/user-attachments/assets/87781722-3b03-4de1-adfd-d71f29bff90b)
![Project2 - HR Analysis_page-0007](https://github.com/user-attachments/assets/4d806944-2c8b-4fa3-8490-d9fae455e71a)
![Project2 - HR Analysis_page-0008](https://github.com/user-attachments/assets/1c56bad2-94f9-441b-8c2d-3cc39120757e)


## Project Objectives
- The goal of this project was to create an HR analytics dashboard to track key **employee metrics**, analyze **turnover trends**, and understand **salary distribution** across branches and cost centers. 
- The insights aimed to inform better workforce management and **improve retention strategies**.

## Key Insights and Findings
### Workforce Overview:

- **Total Employees**: 2.1K
- **Active Employees**: 1.9K
- **Average Cost per Employee**: 5.6K
- **Average Tenure**: 9.5 years
- **Turnover Rate**: 18.76%
### Employee Demographics:

- **Gender Distribution**: 91.2% Male, 8.8% Female.
- **Age Groups**: The majority (66.4%) of employees are aged 31-45 and 46-60.
- Top 3 Nationalities:
  - India: 33.0%
  - Pakistan: 32.7%
  - Saudi Arabia: 13.9%

### Turnover Analysis:

- **Total Terminations**: 178 employees, with the highest turnover rate (11.17%) in the 31-45 age group.
- **Turnover by Department**: The Civil Projects branch had the highest turnover rate at 8.01%.
- **Tenure Insights**: Employees in Marine Projects and Civil Projects had a significantly higher tenure compared to other branches.
###  Financial Metrics:

- **Total Salary Cost**: 7.56M
- **Average Salary**: 3.9K
- **Highest-Paid Position**: Managing Director (MD), with an average salary of 75K.
- **Branch with Highest Salary**: Alumco Projects, averaging 9.7K per employee.
### Branch and Cost Center Analysis:

- **Top 3 Branches by Employee Count**:
   - Civil Projects: 57.4%
   - Marine Projects: 19%
   - Office: 11.1%
### Salary Distribution by Branch:
- The Alumco Projects branch had the highest average salary, while Fleet/Warehouse had the lowest.
## Key Questions Explored
1. What is the distribution of employees across different branches and cost centers?
   - Civil Projects have the most employees, accounting for 57.4% of the workforce.
2. Which age group and nationality have the highest turnover?
   - The 31-45 age group had the highest turnover rate (11.17%), while Pakistan had the highest turnover rate by nationality (3.48%).
4. Which branches have the highest salary costs?
   - The Alumco Projects branch had the highest salary per employee, averaging 9.7K.
4. How does the tenure differ across branches and nationalities?
   - Employees in Turkey had the highest average tenure (18 years), and Marine Projects had 9.9 years.
## Challenges and Limitations
1. Data Quality Issues:
   - Missing or incorrect values for gender and birthdate required manual correction.
2. Limited Data on Benefits:
   - While the analysis included salary and allowances, it lacked detailed data on benefits, limiting the depth of the financial analysis.
## Technical Details
### Semantic Model:
* The data model captures relationships between **employee demographics**, **financial metrics**, **turnover analysis**, and **branch/cost center breakdowns**.
* This allowed for complex cross-analysis to identify patterns in **turnover** and **cost management**.
### DAX Measures:

- Total Salary Cost = SUM(Employee[Salary Package])
- Average Salary = AVERAGE(Employee[Salary Package])
- Turnover Rate = DIVIDE(Terminated[Count], ActiveEmployees[Count], 0) and etc.

### Visualizations:

- Bar Charts: Showcased employee distribution across branches and age groups.
- Pie Charts: Used to display turnover rate by department and age group.
- Tables: Summarized salary distribution by branch and job title.
### Power BI Features Utilized:

- Slicers for filtering by employment status, branch, and year.
- Drill-through analysis to explore employee demographics and turnover for specific branches.
