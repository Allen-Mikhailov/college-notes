## Rules of RREF
1. Any rows of all 0's must be at the bottom (just swap to get there)
2. In any non zero row the first non-zero entry is 1. These numbers are called <span style="color:orange">pivots</span>
3. Each pivot is the only non-zero entry in its column
4. Any pivot in a lower row is to the right of any pivot in a higher row (Down and to the right)
$$
\left[
\begin{array}{ccccc|c}
\textcolor{orange}1 & 0 & 0 & 0 & 4 & 3\\
0 & 0 & \textcolor{orange}1 & 0 & 1 & 0 \\
0 & 0 & 0 & \textcolor{orange}1 & -2& 1
\end{array}
\right]
$$
Use the [[Row Reduction Algorithm]] to do these manipulations

## Interpreting a RREF Matrix
Any rows that look like mean that there is no solution (Inconsistent)
$$
\left[
\begin{array}{ccc|c}
0 & 0 & 0 & 5 
\end{array}
\right]
$$
Finding solutions:
$$
\left[
\begin{array}{cccc|c}
1 & 4 & 3 & 0 & 3 \\
0 & 0 & 1 & 0 & 4 \\
0 & 0 & 0 & 0 & 0
\end{array}
\right]

$$
Free variables are variables when a column does not have any <span style="color:orange">pivots</span>. Ex: $x_2$ and $x_4$. This means they can be any value you want.
$x_3=4$ because $0x_1+0x_2 + 1x_3 + 0x_4=4$ 
$x_1=3-4x_2-3x_3$ so it s dependent on
