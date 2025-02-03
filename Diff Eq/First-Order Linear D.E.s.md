$y\prime=f(t,y)$ Non Linear

$y\prime=p(t)y+q(t)$ inhomogeneous Linear D.E.
- $L=\frac{d}{dt}-p(t)$, $Ly=q(t)$

$y$ is the value of a bank account accumulating interest at a rate of $p(t)$, with a rate of deposit of $q(t)$

Suppose $y=0$ is an equilibrium solution of $y\prime=f(t,y)$
Near $y=0$, $f(t,y)\approx f(t,0)+y\frac{\partial f}{\partial y}(t,0)\approx p(t)y+q(t)$

This is an example of Linearization

### Steps
#### Step 1
$L=\frac{d}{dt}-p(t)$ what is $Ly=q(t)$
Solve $Ly=0$
$Ly=\frac{dy}{dt}-p(t)y=0$
$\frac{dy}{y}=p(t)dt$
$ln|y|=\int p(t)dt+C$
$|y|=e^{\int p(t)dt}e^C$
General Solution
$y=Ce^{\int Pdt}, C\in (-\infty,\infty)$

#### Step 2 (Duhamel's Principle)
Assume p(t) is constant
$y\prime=py+q(t)$
I deposit $q(s)ds$ dollars in the interval $[s,s+ds]$
It accumulates $e^{p(t-s)}q(s)ds$
Add up all the values (take an integral)
$y(t)=\int_{t_0}^te^{p(t-s)}q(s)ds$
Now just check if y(t) actually solves it
$y=\int_{t_0}^te^{p(t-s)}q(s)ds$
$y\prime=\frac{d}{dt}(\int_{t_0}^te^{p(t-s)}q(s)ds)$
$=p\int_{t_0}^te^{p(t-s)}q(s)ds+e^{pt}e^{-pt}q(t)$
$=py+q(t)$
**For $p(t)$ not constant


#### Step 3. Add solutions to $Ly=0$ to the particular solution$
General Solution to $Ly=0: y(t)=Ce^{\int_{t_0}^tp(s)ds}$
Particular Solution $y(t)=\int_{t_0}^te^{\int_s^tp(u)du}q(s)ds$ which solves $Ly=q(t)$
Add
General solution Solution to $Ly=q(t)$ is $Ce^{\int_{t_0}^tp(s)ds}+\int_{t_0}^te^{\int_s^tp(u)du}q(s)ds$

Does not have to apply to bank accounts


Example:
$y\prime=t+y$
#### Step 1:
$y\prime=y$
$\frac{dy}{y}=dt$
$ln|y|=t+C$
$y=Ce^t$
#### Step 2:
$\int_{t_0}^te^{(t-s)}sds=e^t \int_0^te^{-s}sds=e^t[-se^{-s}-e^{-s}]^t_0$
$=e^t[-te^{-t}-e^{-t}+1]$
$y(t)=-t-1+e^t$
$y\prime=-1+e^t=-t-1+e^t+t=$
