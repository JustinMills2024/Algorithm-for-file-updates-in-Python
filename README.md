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

<img src="https://github.com/JustinMills2024/Algorithm-for-file-updates-in-Python/assets/159082478/5712843e-5ee2-43d0-bee5-1f78858cb34a" alt="1707844728004">
<br>In my algorithm, I utilize the 'with' statement alongside the '.open()' function in read mode to access the allow list file and retrieve its contents. 

This approach ensures efficient management of resources by automatically closing the file once the 'with' block is exited. The 'open()' function is called with two parameters: the first specifies the file to be opened, and the second indicates the desired mode of operation – in this case, 'r' for reading. 

Using the 'as' keyword, the output of the '.open()' function is assigned to a variable named 'file', facilitating operations within the 'with' statement.<br/>






<H2>Read the file contents </H2>

<Br> To read the file contents, I used the .read() method to convert it into the string.</Br>

<img src="https://github.com/JustinMills2024/Algorithm-for-file-updates-in-Python/assets/159082478/21fe32f3-4c07-4e18-840e-002ac1a1e7bf" alt="1707844728004">






<h2>Convert the string into a list </h2>
<br> To remove individual IP addresses from the allow list, I required it to be in list format. Consequently, I utilized the '.split()' method to transform the 'ip_addresses' string into a list.
.</br>

<img src="https://github.com/JustinMills2024/Algorithm-for-file-updates-in-Python/assets/159082478/ea975ae2-abc0-46af-b9a5-d118f8b325e9" alt="170784">

<h2>Iterate through the remove list</h2>

<br>An essential aspect of my algorithm is to iterate through the IP addresses listed in the 'remove_list'. To achieve this, I integrated a 'for' loop.</br>




<h2>Summary</h2>
<br>I applied filters to SQL queries to get specific information on login attempts and employee machines. I used two different tables, log_in_attempts and employees. 

I used the AND, OR, and NOT operators to filter for the specific information needed for each task. I also used LIKE and the percentage sign (%) wildcard to filter for patterns.</br>






