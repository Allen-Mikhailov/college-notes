
Example
$$
\begin{bmatrix}
-2 & 1 & 1 \\ 1 & -2 & 1 \\ 1 & 1 & -2
\end{bmatrix}
$$
$A$ is symmetric as $A^T=A$
$det(A-\lambda)=\lambda(\lambda+3)^2$
$\lambda=0$ is an e-value with algebraic multiplicity of 1
$\lambda=-3$ has an algebraic multiplicity of 2
We are not immediately guaranteed to have a basis of eigenvectors because we have repeated roots

Calculate these sets by row reducing $(A-\lambda I)$ and getting the kernel


$E_0=span\left(\begin{bmatrix} 1 \\ 1 \\ 1\end{bmatrix} \right)$
- Geometric multiplicity of 1

$E_{-3}=span\left(\begin{bmatrix} -1 \\ 1 \\ 0\end{bmatrix},\begin{bmatrix} -1 \\ 0 \\ 1\end{bmatrix} \right)$
- Geometric multiplicity of 2

Eigenspaces are orthogonal when the matrix is symmetric

With differential equations
$y''-y'-2y=0$
$r^2-r-2=(r-2)(r+1)$
$r=2,r=-1$
Basis of solution space
$e^{2t},e^{-t}$

$y'=v$
$v'=v+2y$

$$
\begin{bmatrix}
y' \\ v'
\end{bmatrix} = 
\begin{bmatrix}
0 & 1 \\ 2 & 1
\end{bmatrix}
\begin{bmatrix}
y \\ v
\end{bmatrix}
$$
Find eigenvalues
$det(A-\lambda I)=\lambda^2-\lambda-2;2,-1$
If $y_1=e^{2t}$ then $\begin{bmatrix} y_1 \\ y_1'\end{bmatrix}=e^{2t}\begin{bmatrix} 1 \\ 2\end{bmatrix}$
Calculate 
$$
A\begin{bmatrix}y_1 \\ y_1' \end{bmatrix}
=
e^{2t}
\begin{bmatrix} 0 & 1 \\ 2 & 1\end{bmatrix}
\begin{bmatrix} 1 \\ 2\end{bmatrix}
$$
$\begin{bmatrix}y_1 \\ y_1'\end{bmatrix}$ is an eigen vector of $A$ with an eigenvalue of $2$
$$
e^{2t}=\left(\begin{bmatrix}
0 \\ 2
\end{bmatrix} + 2\begin{bmatrix}
1 \\ 1
\end{bmatrix}\right)
$$
$y_2=e^{-t}$
$\begin{bmatrix}y_2 \\ y_2'\end{bmatrix}$ has an eigenvalue of $-1$
$$
2e^{2t}
\begin{bmatrix}
1 \\ 2
\end{bmatrix} = 2\begin{bmatrix} y_1 \\ y_1'
\end{bmatrix}
$$


