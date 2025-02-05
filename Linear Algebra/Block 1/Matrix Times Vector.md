$A_{mxn}$ is some matrix 
x  $\in\mathbb{R}^n$, x is some vector. 
Number of elements in the vector must match the number of columns on the matrix
![[Matrix Times Vector 2025-01-23 23.58.19.excalidraw]]
$Ax=a_1v_1+a_2v_2+...+a_nv_n \in \mathbb{R}^m$

Example:
$$
A=\left[
\begin{matrix}
1 & 3 & 5 \\
2 & 4 & 6
\end{matrix}
\right]
,x=\left[
\begin{matrix}
3 \\ -2 \\ 1
\end{matrix}
\right]
$$
$$
Ax=3\left[
\begin{matrix}
1 \\ 2
\end{matrix}
\right]
-2\left[
\begin{matrix}
3 \\ 4
\end{matrix}
\right]
+1\left[
\begin{matrix}
5 \\ 6
\end{matrix}
\right]
=\left[
\begin{matrix}
2 \\ 4
\end{matrix}
\right]
$$
### Properties
- $A(w_1+w_2)=Aw_1+Aw_2$ - Respects vector addition
- $A(cw)=c(Aw)$ - Respects scalar multiplication
This means Matrix-vector product is linear
