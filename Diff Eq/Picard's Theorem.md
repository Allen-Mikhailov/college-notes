## Existence and uniqueness of solutions to IVPs

Ex 1: $y\prime=y$
eq. soln at $y=0$
![[Picard's Theorem 2025-01-22 10.08.17.excalidraw]]

$y\prime=y$
$ln|y|=t+C$
$|y|=e^t+C$
$y=+-e^t+C$
Solutions do not cross

Ex 2:
$y\prime=\sqrt{y}$
$\frac{dy}{\sqrt{y}}=dt$
$2y^\frac{1}{2}=t+C$
$y^\frac{1}{2}=.5t+C$
$y=.25(t+C)^2$

$y=0$ is a solution to the IVP
$y=.25(t+0)^2, C\leftarrow0$ is also a solution but it crosses at y=0 so it is not unique

there is existence of solutions to the IVP
but not uniqueness as solution curves cross

Ex 3:
$y\prime=\frac{1}{y}$
$y(0)=0$ does not exist

$y(0)=1$
$ydy=dt$
$.5y^2=t+C$
$t=+-\sqrt{2t+C}$
solutions exist where $2t>=-C$
domain of time is constrained
![[Picard's Theorem 2025-01-22 10.24.45.excalidraw]]
$1=y(0)=+-\sqrt{C} \rightarrow C=1$
$y(t)=\sqrt{2t+1}$
$2t+1>0 \rightarrow t > -1/2$



### Picard's existence and uniqueness theorem.
#### Part 1: Existence
Suppose $f(t,y)$ is continuous on the rectangle
R={(t,y): a<t<b, c<y<d}
and $(t_0,y_0)$ in R
Then there exists a positive number h>0 such that the IVP
$y\prime=f(t,y), y(y_0)=y_0$ has a solution y(t) defined on $(t_0-h,t_0+h$)
#### Part 2: Uniqueness
If $\frac{\partial f}{\partial y}(t,y)$ is continuous on R then the solution from Part 1 is unique
