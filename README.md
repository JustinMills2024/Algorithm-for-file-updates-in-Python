<h1>Algorithm for file updates in Python</h1>


<h2></h2>
<br> You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. 


The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. 


There's also a remove list that identifies which employees you must remove from this allow list.


Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.

<br/>
<h2>Open the file that contains the allow list
</h2>
<br> For the first part of the algorithm, I opened the "allow_list.txt" file. First, I assigned this file name as a string to the import_file variable:
<br>

<img src="https://github.com/JustinMills2024/Algorithm-for-file-updates-in-Python/assets/159082478/3dc9d037-8bd8-4ea6-96ba-625a9d8b1913" alt="1707844414523">



<br>Then, I used a with statement to open the file:</br>



<H2>Retrieve login attempts on specific dates</H2>



<h2>Retrieve login attempts outside of Mexico</h2>
<br> Scenario: After investigating the organization’s data on login attempts, I believe there is an issue with the login attempts that occurred outside of Mexico. These login attempts should be investigated.

The following code demonstrates how I created a SQL query to filter for login attempts that occurred outside of Mexico.</br>

<img src="https://github.com/JustinMills2024/Apply-filters-to-SQL-queries/assets/159082478/a1582050-6d31-4362-b15f-e9c8d17a18db" alt="1707189394904">
<h2>Retrieve employees in Marketing</h2>
<br> Scenario: My team wants to update the computers for certain employees in the Marketing department. To do this, I have to get information on which employee machines to update.

The following code demonstrates how I created a SQL query to filter for employee machines from employees in the Marketing department in the East building.</Br>

<img src="https://github.com/JustinMills2024/Apply-filters-to-SQL-queries/assets/159082478/b74a19fa-9a6c-45a0-9ad5-d9507b6c13d0" alt="1707189682247">

<h2>Summary</h2>
<br>I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. 

I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.</br>






