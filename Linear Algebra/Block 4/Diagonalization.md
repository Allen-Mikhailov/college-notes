
Example

$$
A=
\left[
\begin{array}{cc}
7 & 2 \\ -4 & 1
\end{array}
\right]
B=v_1,v_2;
B=\left[
\begin{array}{cc}
1 \\ -1
\end{array}
\right],
\left[
\begin{array}{cc}
1 \\ 2
\end{array}
\right]
$$
$A$ is the standard matrix for some transformation $T: \mathbb{R}^2 \rightarrow \mathbb{R}^2$
$Av_1=5v_1$, $v_1$ is an eigenvector with a value of 5

$A=[T]_{E\leftarrow E}=\underset{E \leftarrow B}{P}[T]_{B \leftarrow B}\underset{B \leftarrow E}{P}$


If **and only if** there is a basis of $\mathbb{R}^n$ consisting of eigenvectors of $A$, $A$ is diagonalizable
This makes large powers easier to compute and a bunch of other things

$A$ is diagonalizable if $\sum{ge.mu(\lambda)}=n$

### How to actually do it
1. Compute the eigenvalues and throw out defective ones
2. Find as many lineally independent eigenvectors as possible
3. Combine those into a matrix $P$
4. Build a diagonal matrix $D$ whose diagonal elements are the eigenvalues of $A$.
5. $D=P^{-1}AP$




