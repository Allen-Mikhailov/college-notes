Constant Coefficient 2nd order linear homogeneous D.E.S

$ay\prime\prime + by\prime+cy=0$

Use the strategy of educated guessing
$y=e^{rt}$ solves this equation

$ar^2e^{rt}+bre^{rt}+ce^{rt}=0$
$e^{rt}$ is never 0
$ar^2+br+c=0$

$r=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$
$\Delta=b^2-4ac$

### Case $\Delta>0$

$r_+=\frac{-b+\Delta}{2a}$
$r_-=\frac{-b-\Delta}{2a}$

General solution
$y=C_1e^{r_+t}+C_2e^{r_-t}$
dim(solution space) = 2
Because we get two values we need to specify two initial conditions for the IVP

### Case $\Delta = 0$
lots of math
$y=e^{rt}+te^{rt}$

Case $\Delta<0$
$r=\frac{-b}{2a}\pm i\frac{\sqrt{-\Delta}}{2a}$
$r_1=a+iB$
$r_2=a-iB$
Basis $=e^{(a+iB)t}+e^{(a-iB)t}$

General Solution
$y=c_1e^{(a+iB)t}+c_2e^{(a-iB)t}$
$y=e^{at}(c_1e^{iBt}+c_2e^{-iBt})$
$y=e^{at}[c_1(\cos Bt + i \sin Bt)+c_2(\cos (-Bt) + i \sin (-Bt))]$
$y=e^{at}[(c_1+c_2)\cos Bt+i(c_1-c_2)\sin Bt]$
$y=A_1e^{at}\cos Bt+A_2e^{at}\sin Bt, A_1,A_2 \in \mathbb{C}$
Real Basis=$e^{at}\cos Bt,e^{at}\sin Bt$
$y=c_1e^{at}e^{iBt}+c_2e^{at}e^{-Bt}$

### Example
$y''-ty+13y=0$
$\Delta=16-4*13<0$
$r_1=2+3i,r_2=2-3i$
Basis: $e^{2t}\cos(3t),e^{2t}\sin(3t)$









### Euler's Formula
$e^{i\theta}=\cos \theta + i\sin \theta$
Justification is just the Taylor series




