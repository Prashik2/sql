# sql
sql exercise
Online Resources:
Video
https://www.youtube.com/watch?v=HXV3zeQKqGY
Web Pages
https://sqlbolt.com/
https://www.w3resource.com/sql-exercises/employee-database-exercise/index.php

3 Days
    
    1. https://www.w3resource.com/sql-exercises/employee-database-exercise/index.php
Write a query to find the grade and name of the salary-grade wise employee getting the highest salary.
    
    2. Consider following Table
|Id|date|amount|deposit_withdrawal|
|-----|----|----|---|
|1|10-03-2021|1000|deposit|
|2|15-03-2021|2000|deposit|
|3|20-04-2021|100|withdrawal|
|4|22-04-2021|300|deposit|
|5|30-06-2021|1500|withdrawal|

Write a query to produce following result

|Id|date|deposit|withdrawal|balance|
|-----|------|------|-----|------|
|1|10-03-2021|1000||1000|
|2|15-03-2021|2000||3000|
|3|20-04-2021||100|2900|
|4|22-04-2021|300||3200|
|5|30-06-2021||1500|1700|




    3. Create a table and put the following contents in the table. Assuming the quantity of each book sold per record is 1.

|Author|Book|Price|Customer|Date|
|------|----|-----|--------|----|
|Arthur Conan Doyle|A Study in Scarlet|$50|Perry mason|26/11/2020|
|Agatha Christie|The Murder of Roger Ackroyd|$52|Erle Stanley Gardner|25/11/2020|
|Rabindranath Tagore|Gora|$52|Miss Marple|25/11/2020|
|Agatha Christie|Murder on the Orient Express|$14|Miss Marple|28/11/2020|
|Agatha Christie|Murder on the Orient Express|$14|Mark Twain|24/11/2020|
|Mark Twain|The Adventures of Tom Sawyer|$26|Agatha Christie|24/11/2020|
|Agatha Christie|The Murder of Roger Ackroyd|$52|Arthur Conan Doyle|26/11/2020
|Erle Stanley Gardner|Careless Kitten|$15|Agatha Christie|28/11/2020|
|Mark Twain|The Gilded Age|$24|Perry Mason|26/11/2020|
|Rabindranath Tagore|Gora|$52|Miss Marple|28/11/2020|
|Mark Twain|The Gilded Age|$24|Perry Mason|25/11/2020|
|Agatha Christie|Peril at End House|$53|Arthur Conan Doyle|28/11/2020|
|Mark Twain|The Adventures of Tom Sawyer|$26|Agatha Christie|28/11/2020|
|Mark Twain|The Gilded Age|$24|Rabindranath Tagore|24/11/2020|
|Rabindranath Tagore|Gitanjali|$41|Mark Twain|24/11/2020|
|Agatha Christie|Peril at End House|$53|Mark Twain|25/11/2020|
|Mark Twain|The Adventures of Huckleberry Finn|$27|Arthur Conan Doyle|27/11/2020|
|Arthur Conan Doyle|The Sign of Four|$26|Harry Potter|26/11/2020|
|Erle Stanley Gardner|Careless Kitten|$15|Sherlock Holms|27/11/2020|
|Rabindranath Tagore|Gitanjali|$40|Perry Mason|24/11/2020|
|Rabindranath Tagore|Gitanjali|$50|Miss Marple|28/11/2020|
|Rabindranath Tagore|Gitanjali|$50|Perry Mason|28/11/2020|


Write a query to find book-wise 
no of distinct customers who are authors, (count1)
no of distinct customers who are not authors. (count2)

Sample Output
BookName	count1		count2
.
.
.
Gitanjali	1 		 2

.
    4. Write a query to find author wise total cost of books sold in descending order by total cost.
       
       
    5. Find the name of books having the second highest cost.
        

    6. Find the date on which the highest amount received.

