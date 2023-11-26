# MANE 3351 - Manufacturing Engineering Analysis

## Laboratory 10 Assignment

### Assigned: November 27, 2023

### Due: December 4, 2023 (no late submissions)

---

## Learning Goals

1.  Use of linear algebra to implement linear regression, and
1.  Use of Python linalg module to solve linear algebra problems

## Problem Description

Linear regression is a statistical procedure to fit a line to data. There are several methods of implementing linear regression including linear algebra. In this lab, you will use linear algebra to solve a linear regression problem.

The linear algebra formulation of the regression problem is

$$
\mathbf{Y}=\mathbf{Z\beta}+\mathbf{\varepsilon}
$$

Where $\mathbf{Y}$ is a ($b\times 1$) vector containing the response variable values, $\mathbf{Z}$ is a ($n\times(r+1)$) matrix containing a column of ones and the values of the independent variables, $\mathbf{\beta}$ is a ($(r+1)\times 1)$) vector containing the parameters of value of the linear regression equation and $\mathbf{\varepsilon}$ is a ($n\times 1$) vector containing the error terms. $\mathbf{\varepsilon}$ is not observed.

The solution is given by

$$
\mathbf{\hat{\beta}}=\mathbf{\left(Z^\prime Z\right)^{-1}Z^\prime Y}
$$

The date for this laboratory is

$$
\mathbf{Y}=\left[\begin{matrix}9.95\\24.45\\31.75\\35.0\\25.02\\16.86\\14.38\\9.6\\24.35\\27.5\\17.08\\37.0\\41.95 \end{matrix}\right]
$$

and 

$$
\mathbf{Z}=\left[\begin{matrix}
1 & 2 & 50\\
1 & 8 & 110\\
1 & 11 & 120\\
1 & 10 & 550\\
1 & 8 & 295\\
1 & 4 & 200\\
1 & 2 & 375\\
1 & 2 & 52\\
1 & 9 & 100\\
1 & 8 & 300\\
1 & 4 & 412\\
1 & 11 & 400\\
1 & 12 & 500\\
\end{matrix}\right]
$$



## Your Solution

### Cell 1

Update your personal information found in the first cell that is a Markdown cell.

### Cell 2

In cell 2 (code cell), enter the Python code using the linealg module to find the value of find the value of $\mathbf{\beta}$.

**Use GitHub Desktop to upload your repository when you have completed the Lab 10 Assignment.**