# Pewlett HackardAnalysis

## Project Overview - 
*Determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program*

## Resources
- Data Source:
    - Employee_challenge_starter_code.sql
    - departments.csv
    - dept_emp.csv
    - dept_manager.csv
    - employees.csv
    - salaries.csv
    - titles.csv

- Software: 
    - Anaconda Version 3.7.3
    - MacOS Catalina Version 10.15.7
    - PgAdmin4
    - Jupyter Notebook 

## Project Results:

- Analysis of retiring_titles list:
    - The retiring_titles list shows the total number of the employees who are ready to retire by their most recent job title
    - The list shows that there are total of 90,398 "silver tsunami" employees who are about ready to retire
    - Approx 50% are in the Engineering Dept.
    - Approx 44% are in of the Staff Dept.
    - Approx 63% of the employees are in Senior positions.
    - Only a total of 2 are in managerial roles

![retiring_titles](https://user-images.githubusercontent.com/36451701/120945129-e70bb480-c705-11eb-9a6d-5df66ab1e7c3.png)

_________________________________________________________________________________________________________________________________________________________________________________    
- Analysis of mentorship_eligibilty list:
    - To be eligible for the mentorship program the employee had to be born in 1965 and currently employed by the company
    - There are a total of 1,549 employees eligible for the mentorship program
    - Approx 47% are in the Staff Dept
    - Appox 48% are in the Engineering Dept
    - Approx 5% are in the Technique Leader Dept
    - There are 0 eligible in the Manager Dept

![mentorship_program_elig](https://user-images.githubusercontent.com/36451701/120945137-eecb5900-c705-11eb-97aa-bd50554c1e2f.png)


![mentorship_program_elig_2](https://user-images.githubusercontent.com/36451701/120945320-9183d780-c706-11eb-9f68-bb015eac98b3.png)

_________________________________________________________________________________________________________________________________________________________________________________
## Project Summary:

Pewlett Hackard is a well establish company that currently has approximately 300,000 employees.  Like most companies, Pewlett Hackard is starting to look at their future. The company is currently looking at offering retirement packages for it's near retirement age baby boomer employees.  It's also starting to think about what positions will need to be filled due to those retirements.  Judging by the number of "silver tsunami" employees eligible for the retirement package, preparing now is a wise decision by the company.  

Currently, there are 90,398 employees expected to be eligible for the retirement package. This means that Pewlett Hackard needs to prepare for 30% of their workforce to be retiring, and at a rapid rate.  This is huge chuck of thier workforce. Hiring new and qualified employees to fill these roles will be of great importance. Approximately 94% of the retirement ready employees are working in the Engineering and Sales Departments. The Engineering and Sales Depts. will have to be the focal point of recruitment process. Perhaps most alarming is that fact there are only a total of two Managers eligible for retirement package. 

To help prepare for the exodus of all these employees, Pewlett Hackard has decided they would like to keep some of them on in a "mentor" role to help prepare the new employees. This would look to be a great decision considering the amount of hiring that needs to be done.  Having employees who understand what needs to be done can really help with the learning curve for the new hires.  There are currently 1,549 employees who qualify for the mentor role. That is a very small number compared to the 90,398 who are expeted to be retiring. The Engineering and Staff positions make up the majority of mentor eligible. There are no managers eligible for a mentor position.  Seeing as there are only expected to be a total of two managers retiring, there appears not to be big need for new manager positions. It is possible that Pewlett Hackard needs to look into hiring more from within to fill their managerial positions in the future should they need them. 
