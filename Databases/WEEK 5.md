# Lecture 5 
---
Distinct - need to remove duplicates
ORDER BY - need to order output by some parameter

JOINS
OUTER JOIN, LEFT OUTER JOIN
Tuple Variables.
Subqueries

# Tutorial 5
---
### Q8
```
SELECT Fname, Lname, Super.Fname, Super.Lname FROM EMPLOYEE JOIN EMPLOYEE AS Super WHERE EMPLOYEE.Super_ssn=Super.Ssn
```
### Q2
```
SELECT Pnumber, Dnum, Lname, Address, Bdate FROM PROJECT, DEPARTMENT, EMPLOYEE WHERE Plocation = 'Stafford' AND Dnum = Dnumber AND Mgr_ssn = ssn
```
### Q9&10
```
SELECT Ssn
FROM EMPLOYEE;

SELECT Ssn, Dname
FROM EMPLOYEE, DEPARTMENT;
```
