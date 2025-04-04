# Relational Algebra
-----
Project then we need to choose a row. Fist we select next we project.
Rename just rename rows or columns.
Cartesian product same as cartesian product of sets.
Difference data what in $R_1$ but not in $R_2$ .
Join $R_1$ and $R_2$ is a $R_1 R_2$. 


## EX 1
```
π Name (π SID ((π PID σ SID = 4 (Catalogue)) ⨝ (Catalogue)) ⨝ (Supplier))
```
## EX 2
```
π Name ((π SID (Catalogue) - (π SID (π PID ((π SID (σ City = 'Kazan' (Supplier))) ⨝ (Catalogue)) ⨝ (Catalogue)))) ⨝ (Supplier))
```
## EX 3 
```
π Item, Color ((( π PID, SID (Catalogue)) ÷ (π SID (σ City = 'Moscow' (Supplier)))) ⨝ Product)
```