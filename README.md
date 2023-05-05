Download Link: https://assignmentchef.com/product/solved-dbs301-lab-6-sub-select
<br>
This week’s lab continues using the SELECT command in addition to now incorporating multiple tables in the FROM statement to gather information together.

<h2>Tasks</h2>

<strong><em>It is important that Steps 1, 2, and 3 are completed first.</em></strong>

<ol>

 <li>SET AUTOCOMMIT ON (do this each time you log on) so any updates, deletes and inserts are automatically committed before you exit from Oracle.</li>

 <li>Create an INSERT statement to do this. Add <strong>yourself </strong>as an employee with a NULL salary, 0.21 commission_pct, in department 90, and Manager 100.  You started TODAY.</li>

 <li>Create an Update statement to: Change the salary of the employees with a last name of Matos and Whalen to be 2500.</li>

</ol>

You must use subqueries for these questions (must minimize the number of tables being used in the main query)

<ol start="4">

 <li>Display the last names of all employees who are in the same department as the employee named Abel.</li>

 <li>Display the last name of the lowest paid employee(s)</li>

 <li>Display the city that the lowest paid employee(s) are located in.</li>

 <li>Display the last name, department_id, and salary of the lowest paid employee(s) in each department. Sort by Department_ID. (<em>HINT:</em> careful with department 60)</li>

 <li>Display the last name of the lowest paid employee(s) in each city</li>

 <li>Display last name and salary for all employees who earn less than the lowest salary in ANY department. Sort the output by top salaries first and then by last name.</li>

 <li>Display last name, job title and salary for all employees whose salary matches any of the salaries from the IT Department. Do NOT use Join method. Sort the output by salary ascending first and then by last_name</li>

</ol>