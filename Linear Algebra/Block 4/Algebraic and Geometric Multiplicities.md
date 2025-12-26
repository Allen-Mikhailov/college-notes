Theorem (algebraic-geometric inequality)

If $\lambda$ is an eigenvalue of $A$, then $geometric\;multiplicity(\lambda)\leq algebraic\; multi.(\lambda)$

### Proof:
Let $k=ge.mu(\lambda)$. We have $k$ linearly independent eigenvectors $v_1,v_2,...,v_k$

By the extension theorem, we can extend this list to a basis $B=v_1,...,v_k,w_1,...,w_{n-k}$ of $\mathbb{R}^n$


Consider $[A]_B$
$$
[A]_B=
\begin{bmatrix}
| & | & | & | & | & | \\
[Av_1]_B & ...&[Av_k]_B &[Aw_1]_B & ...&[Aw_{n-k}]_B \\
| & | & | & | & | & | \\
\end{bmatrix}
$$
$A$ is similar to $[A]_B$, so they have the same characteristic polynomial

Note:
$\det([A]_B-tI)=(\lambda-t)^kP_c(t)$
algebraic multiplicity of $\lambda$ must be at least $k$


