# Pewlett Hackard Analysis

## Overview
The purpose of this challenge is to find the number of employees about to retire. I made a query to find people born at the company born bewtween January 1, 1952 and December 31, 1955. Then filtered to show the currently employed people, a list of soon to be retirees and their titles gives an idea of the impact on the company. The result needed further filtering using the DISTINCT ON fuction to condense data from people who changed positions within. The SECOND deliverable shows employees 
who could serve as mentors. By changing the birth date in the query, we can see the senior positions of the company. 

![](https://github.com/lucaskocisko/Pewlett_Hackard_Analysis/blob/main/EmployeeDB.png)

Results

![](https://github.com/lucaskocisko/Pewlett_Hackard_Analysis/blob/main/retire_count.png)

This count of people retiring shows which departments wwill be most affected by people leaving the company. With the the mentorhsip_eligibility.csv we can see who might be qualified to serve as a mentor to new hires.
