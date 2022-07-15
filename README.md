# Pewlett-Hackard Analysis

## Project Overview 
### Purpose
The purpose of this analysis is to prepare Pewlett-Hackard for the upcoming “silver tsunami”. A large number of company employees will begin retiring at an increased rate in the next few years so the company wants to be prepared with the retirement packages, open positions, and new hire training. This analysis focuses on the following: 



## Results  

**1.	The list of retiring employees**
-	The table includes employee number, first name, last name, title, from-date and to-date.
-	The table displays a list of employees who is going to retire in the next few years.
-	The list is long and extensive, yet at-a-glance analysis gives us some insights about the query. Some employees appear more than once due to change of title during their career at Pewlett-Hackard.

![EmployeesTitleDuplicates](https://user-images.githubusercontent.com/105829106/179129033-9c2258a9-28d2-4539-9a5d-b4925892b680.PNG)


**2.	The list of retiring employees without duplicates**
-	The table includes employee number, first name, last name, title, from-date and to-date.
- The table displays a list of employees who are going to retire in the next few years.
-	In the table each employee is listed only once, by her or his most recent title.

![EmployeeTitleNoDuplicates](https://user-images.githubusercontent.com/105829106/179129146-470b5654-df94-4745-a3d8-2f0f12b99f20.PNG)


**3.	The number of retiring employees grouped by title**
-	The table includes employees’ titles and their sum. 
-	From this table we can quickly see how many employees with certain title will retire in the next few years.

![EmployeesTitle](https://user-images.githubusercontent.com/105829106/179129285-1c6e87d8-5645-49ca-88fb-f674c5a5f09f.PNG)


**4. The employees eligible for the mentorship program**
-	The table contains employee number, first name, last name, birth date, from date, to date and title. 
- The table displays a list of employees who is eligible for the mentorship program.

![Mentorship](https://user-images.githubusercontent.com/105829106/179129365-047591cb-ada5-422e-8136-8a63a2fb7c8f.PNG)


# Summary

Bobby's company must prepare for the "silver tsunami" since there are a large number of the employees that are approaching retirement. I believe the break down of employees per department will be beneficial for the company, so Bobby's manager can see what to expect in each department separately. The department name information can be seen in the table `departments` which was merged into the existing table `retirement_titles`.
