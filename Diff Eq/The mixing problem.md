There is a bucket with a hole that is letting things out and a pipe going into it
A fluid is going into it through the pipe
A fluid is going outside the hole
$V(t)$ volume
The solution carries substance 
$x(t)$ is the amount of substance of time $t$.
Input comes in at a known concentration and rate of flow
Output is the substance that comes out
$\frac{x(t)}{V(t)}$

Example:
$x(t)$ lbs salt
$V(t)$ gal "solution"
concentration is lbs/gal
flow rate is gal/min

$\frac{dx}{dt}$ = rate in - rate out
units: $\frac{lbs}{min}$
 $rate\_in(\frac{lbs}{gal})=concentration (\frac{lbs}{gal}) \cdot flow\_ rate\_in (\frac{gal}{min})$
 $rate\_out=concentration \cdot flow\_rate\_out$
 
Example (Brine Mixing)
$V(t)=50 gal$
$rate\_in=2*3$
solution is well mixed and pours out at a rate of
$3\frac{gal}{min}$
What IVP satisfies $x(t)$
$\frac{dx}{dt}=6\frac{gal}{min}-(concentration\_out)3\frac{gal}{min}$
$=6-\frac{x(t)}{50}3=6-\frac{3}{50}x$
$x(0)=0$


$x\prime+\frac{3}{50}x=6$
$p(t)=\frac{3}{50}$
integrating factor $g(t)=e^{\int p(t)dt}$
$g(t)=e^{\frac{3}{50}t}$
$gx\prime+g\frac{3}{50}x=g6$
$(g(t)x(t))\prime=6e^{\frac{3}{50}t}+C$
$e^{\frac{3}{50}t}x(t)=\int 6e^{\frac{3}{50}t}dt+C$
$x(t)=\frac{6\cdot 50}{3}+Ce^{-\frac{3}{50}t}=100+Ce^{-\frac{3}{50}t}$
$x(0)=0=100-C, C=100$
$x(t)=100(1-e^{-\frac{3}{50}t})$








 
 

