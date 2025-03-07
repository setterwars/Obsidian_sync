#forFinal #forMidterm #Recap 

---
# Lecture 1.  Intro to Machine Learning

What is Machine Learning? Machine Learning  computer program that improve their performance at some task through experience.

Data 
$D={(x_i,y_i)}_{i=1}^N$

Performance needs to be defined according to the given task. For example: the ratio of correctly identified malware.
Goal of learning a "Functional" relationship between predictors and target.
![[Pasted image 20250306212422.png]]

### Assessing the quality of learning

${MSE}_{Tr}={Ave}_{i-Tr}[y_i - f(x_i)]^2$

#### What can be wrong in data?

Data is inherently noisy.

---

# Lecture 2.  Linear regression, LR objective, Method of Least Squares, Closed Form Solution, Polynomial Regression


{#} of defects in $p_i$ = $f({features Of p_i})$
First part is $y_i$, second part is $x_i$

From this we can create a linear regression formula.

#### Linear regression formula:

$y = w_0+w_1x_1 + w_2x_2 + + w_px_p$


Least Square Solution 

Polynomial Regression.


---
# Lecture 3. Gradient Descent, Logistic Regression, LoR Objective, Confusion Metrics, Accuracy, Precision, Recall, F1

Gradient descent Learning the machine learning model by iteratively reducing the loss. More like how we learn: **learn by making mistakes**.
