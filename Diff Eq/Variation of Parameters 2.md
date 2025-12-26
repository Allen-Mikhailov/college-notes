Linear second-order (variable coefficient) DE
$Ly=y''+p(t)y'=q(t)=f(t)$

In the first order we just integrate to get $y_p=v(t)y_1$

First solve the homogeneous equation
Let $y_1,y_2$ be a basis of solutions to $Ly=0$
$y_p=v_1y_1+v_2y_2$,       $v_1,v_2$ are functions
$y_p'=v_1y_1'+v_2y_2'+v_1'y_1+v_2'y_2$


Lets be greedy and search for $v_1,v_2$ such that:
$v_1'y_1+v_2'y_2=0$   **Equation 1**

$y''=v_1y_1''+v_2y_2''+v_1'y_1'+v_2'y_2'$

Plug these in 
Ly=$(v_1y_1''+v_2y_2''+v_1'y_1'+v_2'y_2')+p(t)(v_1y_1'+v_2y_2'+v_1'y_1+v_2'y_2)+q(t)(v_1y_1+v_2y_2)$
the terms with $v_1,v_2$ cancel as you you can create the original differential equation so it is 0 by definition
$Ly=v_1'y_1'+v_2'y_2'=f(t)$ **Equation 2**

We have two variation equations
$v_1'y_1+v_2'y_2=0$
$v_1'y_1'+v_2'y_2'=f(t)$

$v_1',v_2'$ are unknown so we can put them in a matrix
$$
\left[
\begin{array}{cc}
y_1 & y_2 \\ y_1' & y_2'
\end{array}
\right]
\left[
\begin{array}{c}
v_1' \\ v_2' 
\end{array}
\right]=
\left[
\begin{array}{c}
0 \\ f 
\end{array}
\right]
$$
Now we can use Cramer's Rule
$$
v_1'=
\frac{det\left[
\begin{array}{cc}
0 & y_2 \\ f & y_2'
\end{array}
\right]}{W(y_1,y_2)}],\:
v_2'=
\frac{det\left[
\begin{array}{cc}
y_1 & 0 \\ y_1' & f
\end{array}
\right]}{W(y_1,y_2)}]
$$

This turns into
$$
v_1'=-\frac{y_2f}{W(y_1,y_2)},
v_2'=\frac{y_1f}{W(y_1,y_2)}
$$
And now we ca integrate to solve for $v_1,v_2$


Example: $y''+y=\frac{1}{\cos t}$
Characteristic roots $r^2+1=0; r=\pm i$
Basis = $\cos t, \sin t$

Use variation of parameters to find $y_p$ 
We guess $v_1\cos t+v_2\sin t$

compute $W$
$$W=
\left[
\begin{array}{cc}
\cos t & \sin t \\ -\sin t & \cos t
\end{array}
\right]
=\cos^2t+\sin^2t=1
$$

$v_1'=-f(t)y_2=-\tan t$

