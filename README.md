# -Pewlett-Hackard-Analysis.-
-Deliverable 3 A written report on the employee database analysis (README.md)

--Overview of the analysis: Explain the purpose of this analysis.
The purpose of the analysis is to uplode the data and creat a table that would join the two different data to one 
table, showing the data more clearly. 

--Results: 
The results are clearly have been combined from the two different data. In Deliverable 1, The results have shown 
the emp_no first_name,last_name,from_date,to_date, and specific birth search. Which what the table provided. 
For Deliverable 2, the results were conclusive. the results show that have joined four different data to create one table 
with the existent data provided. 
four major points from the two analysis deliverables. 
1.Frist_name
2.last_name
3.birth_date
4. emp_no

--Summary: 

provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
--silver tsunami
Select Count (DISTINCT r.emp_no) as retirement_eligable
from retirement_titles as r
Union 
Select Count (DISTINCT m.emp_no) as mentorship_eligable
From mentorship as m 

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
The data shows that 1940 retirement Eligible colums, and as mentorship_eligable the number is 90398 
which would indcate that about 45% are retirement Eligible.
There are enough of retierment Eligiblefor the next generation. 
