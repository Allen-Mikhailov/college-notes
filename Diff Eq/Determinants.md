For a square matrix n x n
$$
\left[
\begin{array}{ccc}
-&v_1&-\\
-&v_2&-\\
&.&\\
-&v_n&-\\
\end{array}
\right]
$$
There is a number called the determinant of A denoted det A or $|A|$
Measuring the volume of the matrix as it was a parallelepiped.

1. The det$(I_n)=1$ The unit cube has a value of 1

2. Swapping two rows flips the sign
$$
\left[
\begin{array}{ccc}
-&v_1&-\\
-&v_2&-\\
-&v_3&-\\
\end{array}
\right]=-
\left[
\begin{array}{ccc}
-&v_2&-\\
-&v_1&-\\
-&v_3&-\\
\end{array}
\right]
$$

3. Scaling a row by $k$ scales the det by $k$
4. Adding a multiple of one row to a different row does not affect the determinant

A matrix is invertible when its determinant is not 0

det$(AB)$=det$(A)\cdot$ det$(B)$
det$(A^{-1})=\frac{1}{det(A)}$

### Expansion by CO factors
Recursive idea
What is the det of 2x2 matrix
$$
det
\left(
\begin{array}{cc}
a_{11} & a_{12} \\ a_{21} & a_{22}
\end{array}
\right)
=a_{11}a_{22}-a_{12}a_{21}
$$
$A$ is n x n For every entry $a_{ij}$, we have $A_{ij}$ which is an $(n-1)$ x $(n-1)$ matrix called the minor of $A$ which is just $A$ without row $i$ or columns $j$

The $aij$ cofactor is $C_{ij}$ is $(-1)^{i+j}$ det$(A_{ij})$
#### Cofactor expansion along row $r$
det$(A)=\sum_{j=1}^n=a_{rj}C_{rj}=\sum_{j=1}^n=a_{rj}(-1)^{r+j}$ det$(A_{ij})$


