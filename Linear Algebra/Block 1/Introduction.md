Linear algebra is about solving systems of equations 

First you must check if a solution to a system of equations exists. (Existence)
Then you must check if there is only one or many solutions. (Uniqueness)

$R1: x_1+5x_2=7$
$R2:-2x_1-7x_2=-5$
$R2\leftarrow 2R1 + R2$ 

$R1: x_1+5x_2=7$
$R2: 0x_1+3x_2=9$
$R2\leftarrow \frac{1}{3}R2$

$R1: x_1+5x_2=7$
$R2: 0x_1+x_2=3$
$x_2=3, x_1=-8$

$$
\left[
\begin{matrix}  
1 & 0 & 0 & 1 & 1 \\
0 & 1 & 0 & -1 & -1 \\
0 & 0 & 1 & 1 & 0
\end{matrix}
\right]
$$
When a term is free it is when it can be any value and it creates a solution
Everything else is a pivot variable

$$
\left [
\begin{matrix}
0 & 1 \\
1 & 0
\end{matrix}
\right]
\rightarrow
\left \{
\begin{matrix}
0x_1=1 \rightarrow 0=1\\
1x_1=0 \rightarrow x_1=0\\
\end{matrix}
\right\}
$$
Inconsistent system because it has no solutions
Consistent means that there is a solution

Coefficient Matrix:
$$
\left[
\begin{matrix}
0 & 1 \\
1 & 0
\end{matrix}
\right]
$$
Augmented Matrix
$$
\left[
\begin{array}{cc|c}
0 & 1 & 3\\
1 & 0 & 2 
\end{array}
\right]
$$