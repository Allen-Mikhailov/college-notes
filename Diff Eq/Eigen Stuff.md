
Consider the system
$$
\left\{
\begin{array}{cc}
x_1'=3x_1 \\
x_2'=2x_1+x_2
\end{array}
\right.
$$
This is not decoupled so its not easy to solve
This turns into the matrix
$$
\begin{bmatrix}
x_1'\\x_2'
\end{bmatrix}
=
\begin{bmatrix}
3 & 0 \\ 2 & 1
\end{bmatrix}
\begin{bmatrix}
x_1\\x_2
\end{bmatrix}
$$

Def: If $T: V \rightarrow V$ is, and $v\in V$ is nonzero such that $T(v)=\lambda$ for some $\lambda$, then $v$ is in eigen vector of $T$ with and eigen value of $\lambda$ 
This will make the matrix diagonal which would be it decoupled and way easier to solve

If $Av=\lambda v$
$\lambda v = \lambda I_n v$
$(A-\lambda I)v=0$
$v$ is non zero so it has something non linear it is kernel
so $ker(A- \lambda I)=\{x \in \mathbb{R}^n:(A-\lambda I)x=\vec{0}\}\neq 0$
Which means it is not linearly independent and none invertible so we can use the determinant 

The characteristic polynomial is $p(\lambda)=det(A-\lambda I)$
We need to find $\lambda$ such that $p(\lambda)=0$ as these will be our eigen values

The eigen space $E_\lambda = ker(A- \lambda I)$ 
This is the set of all eigen vectors of $A$ with eigen value $\lambda$


