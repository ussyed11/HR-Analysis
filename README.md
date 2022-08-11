
# Pewlett-Hackard-Analysis

## Overview 
We were tasked by the Pewlett-Hackard management to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, we need to write a report that summarizes our analysis and helps prepare Pewlett-Hackard management for the “silver tsunami” as many current employees reach retirement age. 



## Procedure & Results: 
In this project, we use QuickDBD and Schemas to design databases and writing intermediate-level SQL queries to answer important business questions for the company’s HR department. We utilized PostresSQL as the data base system to load, build, and host the company data. We used pgAdmin to run quarries and generated reports in a well-designed database with reporting capabilities. Initially, we imported 6 csv files containing employee details and job position information.

1.  For our first task we ran querries to :
 
    * create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955.
    * create a unique titles table without the duplicates.
    * Sort the Unique Titles table in ascending order by the employee number and descending order by the last date (i.e., to_date) of        the most recent title.
    The image below shows the query and the table:
    
       ![Screen Shot 2022-04-04 at 5 09 15 PM](https://user-images.githubusercontent.com/98566486/161653921-c906bb7b-031f-4558-93f3-c7b9d8024f7f.png)


    
    * Then we wrote another query in the Employee_Database_challenge.sql file to retrieve the number of employees by their most recent       job title who are about to retire as shown in the image below:
    
    ![Screen Shot 2022-04-04 at 5 14 12 PM](https://user-images.githubusercontent.com/98566486/161633261-59cfeec4-480c-4b36-9be1-258bec1c003b.png)
    
 2. For our second task we ran and executed a query to create a Mentorship Eligibility table that holds the employees who are eligible to participate in a mentorship program.

![Screen Shot 2022-04-04 at 5 19 37 PM](https://user-images.githubusercontent.com/98566486/161634024-aa308bab-e07a-4942-98d5-1f8ae34cf4e2.png)

## Summary: 

According to our analysis,there are 72,458 retiring titles need to be filled as the "silver tsunami" begins to make an impact at the Pewlet-Hackard as shown in the image below:

![Screen Shot 2022-04-05 at 9 44 13 AM](https://user-images.githubusercontent.com/98566486/161767701-bdefb91e-3b35-4cef-9cbd-617c0091afee.png)

Most retiring titles belong to senior engineers and senior staff: 25,916 and 24,926 respectfully.  These higher levels positions need to be filled by providing mentorship programs to current elegible employees.  There are 1,549 employees who are ten years away from retirement and can become mentors to train to upcoming young and talented employees.  Each mentor needs to provide training to about 47 employees to get them ready to take the retiring titles from each department(1549 x 47 = 72,803).  

![Screen Shot 2022-04-04 at 5 14 12 PM](https://user-images.githubusercontent.com/98566486/161769957-6c81d827-2def-4dc8-b233-1034d778d3d5.png)

Our prior analysis shows that the most impacted departments are the Development depart. and Production depat. with 9,281 and 8,174 retiring people.

![Screen Shot 2022-04-05 at 9 59 02 AM](https://user-images.githubusercontent.com/98566486/161770819-d310c758-261b-401a-8113-4489c40d8d19.png)

We ran two querries to find elegible mentors for development and production departments and found that there are 435 eligible mentors in the Development dept. and 356 eligible mentors in the Production dept. shown in images below:


![Screen Shot 2022-04-04 at 9 13 55 PM](https://user-images.githubusercontent.com/98566486/161771258-581c4607-70b7-45d0-863c-90cf932b0e25.png)



![Screen Shot 2022-04-05 at 10 08 13 AM](https://user-images.githubusercontent.com/98566486/161772776-1bb395a5-bbc8-41a4-b31a-c2c9aaf65830.png)

The retiring rate is alarming, and it does feel like Pewlet-Hackard will be facing a "silver tsunami"  to make an impact. However, if the HR start taking our analytics considerations and start planning to offer the mentorship programs as soon as possible, this retiring impact will be handled gracefuly.  

 
