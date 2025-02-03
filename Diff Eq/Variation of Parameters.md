$\frac{dy}{dt}=p(t)y+q(t)$
IDEA:
$\frac{dy}{dt}=p(t)y$
$y=Ce^{\int p}$
Maybe the solution to $Ly=q(t)$ looks similar?
Guess $y(t)=v(t)e^{\int p}$

If $y(t)=v(t)e^{\int p}$ solves $\frac{dy}{dt}=p(t)y+q(t)$
then $y\prime=v\prime e^{\int p}+v(e^{\int p})\prime$
=$y\prime=v\prime e^{\int p}+pve^{\int p}$
=$v\prime e^{\int p}+py$
$v\prime=e^{-\int P}q(t)$
$v=\int e^{-\int P}q(t)dt$

This leads to

$y(t)=e^{\int p} \int e^{-\int p}q(t)dt$

### Example
solve $y\prime+\frac{1}{t+1}y=2$
$y(0)=0$
$y\prime=-\frac{1}{t+1}y+2=f(t,y)$
$f$ and $f_y$ are continuous except when $t=-1$ so picards applies except there

$L=\frac{d}{dt}+\frac{1}{t+1}$


Step 1: Solve the homogenous problem
$y\prime=-\frac{1}{t+1}y$
$ln|y|=-ln|t+1|+C$
$y=\frac{C}{t+1}$ The constant can keep track of the abs for us

Step 2: Solve $Ly=2$
guess $ve^{\int p}$;$p(t)=-\frac{1}{t+1}$ is a solution
$\int p=-ln|t+1|$
$e^{\int p}=e^{-ln|t+1|}=\frac{1}{t+1}$
Guessing $y(t)=\frac{v(t)}{t+1}$ is a solution
$v\prime=(t+1)2$
$v(t)=t^2+2t$

Step 3: General Solution to $Ly=2$
$y(t)=\frac{C}{t+1}+\frac{t^2+2t}{t+1}$

Step 4: Plug into initial data
$0=y(0)=C$
$y(t)=\frac{t^2+2t}{t+1}$




