How to calculate eigen values

Eigen Value is $b$
$Ax=bx$ when $b$ is an eigen value of $A$

This can become

$Ax-bIx=0$
$(A-bI)x=0$
Look for non trivial solutions

Row reduce the matrix $A-bI$ to find the non trivial solutions

To find the eigen vectors you need to find the solution space

Example
Is 2 an eigen value for $A$
$$
A=
\begin{bmatrix}
-2 & 4 & 8 \\
-2 & 4 & 4 \\ 
0 & 0 & 2
\end{bmatrix}
$$
$A-2I=$
$$
\begin{bmatrix}
-4 & 4 & 8 \\
-2 & 2 & 4 \\ 
0 & 0 & 0
\end{bmatrix}
$$
Row reduce
$$
\begin{bmatrix}
1 & -1 & -2 \\
0 & 0 & 0 \\ 
0 & 0 & 0
\end{bmatrix}
$$
$a_2,a_3$ are free as $a_1=a_2+2a_3$
solution space is
$$
\left\{
a_2
\begin{bmatrix}
1 \\ 1 \\ 0
\end{bmatrix}
+a_3
\begin{bmatrix}
2 \\ 0 \\ 1
\end{bmatrix}
:a_2,a_2\in \mathbb{R}
\right\}
$$
The solution space is two dimensional

This is the 2-eigen space because the eigen value in 2.
All the eigen vectors that have an eigen value of 2