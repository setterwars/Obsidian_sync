# Naive Bayes Classifier

Takes its name from the equation it is based in.

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.10 - 7.07am.writing"
}
```
## Bayes Rules
Bayes classifiers based on Bayes equation.
![[Pasted image 20250210070921.png]]

## Likelihood
# Nearest Neighbor Methods
1. Find the example (x, t) from the stored training set which is closest to x. that is 

$x^*=argmin_{distance}$ 

#### Noisy or Mis-Labeled Samples
![[Pasted image 20250210094400.png]]
Что бы решить эту проблему используем несколько точек и орентируемся по ним.

## $k$ - nearest Neighbor (KNN)
![[Pasted image 20250210094620.png]]


# Validation and Test sets 

We have hyper parameters to tune, we split data as:

----------------------------- Data ------------------------------
Training data ---------- Validating Data -------------- Test data 


 - Solve the "Model Selection" problem


## K-fold Cross-Validation

	-------------------- Data ------------------------
	Fold 1 ---------------- fold 2 ------------ fold 3
	1. Test ---------------- Train -------------- Train
	2. Train -------------- Test ----------------- Train
	3. Train -------------- Train ---------------- Test

$E=\frac{1}{K}\cdot\sum_{i=1}^{K}(E_i)$ 


## Regularization 

${Success}={GoodnessOfFit}+{SimplicityOfTheModel}$


## $L_2$ Regularization

## $L_1$ Regularization


# Lab 4

```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.11 - 10.59am.writing"
}
```
Idea of the regularization is a preventing of the overfiting.

## Naive Bayes
## KNN
## Cross validation 




```handwritten-ink
{
	"versionAtEmbed": "0.3.3",
	"filepath": "Ink/Writing/2025.2.11 - 11.10am.writing"
}
```
