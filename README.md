# Employee Payroll Data Analysis with excel
## Overview
This project is about employee payroll analysis for the month of January which I did. In this project I analized:
- The hours worked by employees
- Employee salary 
- Extra hours worked
- Employee bonuses and the total pay after the bonus for the month
- Minimum employee salary
- Maximum employee salary
- Average employee salary
  ### Employee salary by hours worked
  Every employee has an hour rate they get paid depending on the department they work. So the hour rate is multiplied by the number of hours worked to get the salary for all the weeks.<p>
  ![image](https://github.com/MYZDEE/Payroll-Analysis-1/assets/128803445/3be53bac-d7a6-41a6-9ca4-ae04bab52202)<p>
  ```
  =C4*D4
  ```
  ![image](https://github.com/MYZDEE/Payroll-Analysis-1/assets/128803445/bd280ab2-6c38-41f2-8547-49ccb4780533)<p>

  See below for the employee salary<p>
  ![image](https://github.com/MYZDEE/Payroll-Analysis-1/assets/128803445/1b6bbe51-c92d-452f-9d6d-21eef0e4bb01)<p>
### Employee Overtime pay
  The minimum hours for an employee to work is 40 hours. Employees that work for more than 40 hours gets an overtime bonus. That is half of the hourly rate for every 1hour overtime 
  worked. The number of overtime hours is multiplied by the hourly rate and divided by 2. Absolute referencing was used to copy the formula for the rest of the cells <p>
  ```
  =0.5*$C4*I4
  ```
![image](https://github.com/MYZDEE/Payroll-Analysis-1/assets/128803445/7471a1c2-45f9-4f7c-b569-9245f9ae12ff)
