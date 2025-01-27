If $a_1,a_2,...,a_n,b$ are constants
$a_1x_1+a_2x_2+...+a_nx_n=b$ is a linear equation.
When $b=0$ it is called **homogeneous**

Define function $F(x)=a_1x_1+a_2x_2+...+a_nx_n$
Proposition: $F$ is linear
$F(\overrightarrow{x}+\overrightarrow{y})=F(\overrightarrow{x})+F(\overrightarrow{y})$
$cF(x)=F(cx)$

homogeneous system is when the output is just 0s

A D.E. is **linear** if it has the form

$a_n(t)\frac{d^ny}{dt^n}+a_{n-1}(t)\frac{d^{n-1}y}{dt^{n-1}}+...+a_1(t)\frac{dy}{dt}+y(t)=f(t)$
$f(t)=0$

Ex:
$y\prime\prime+ty\prime-3y=0$ Linear, homogeneous
$y\prime+y^2=0$ Non Linear, homogeneous
$y\prime+sin(y)=1$ Non Linear, Non homogeneous
$y\prime\prime-3y+y=sin(t) Linear, Non homogeneous

If $I$ part of $\mathbb{R}$ is an interval. Let $C^n(I)$ be the set of functions defined for $t\in I$ which are continuous, and whose first derivatives are continuous. 
Ex: $y(t)=t^2$ is in $C^3(\mathbb{R})$  (for any $n$ as well)

Define an operator $L: C^h(I)\rightarrow C^o(I)$ by $L(y)=a_n(t)y^{(n)}+...+a_1(t)y\prime+a_0(t)y$

Claim: $L$ is linear
$L(y_1+y_2)=a_n(t)(y_1+y_2)^{(n)}=a_n(t)(y_1^{(n)}+y_2^{(n)})=L(y_1)+L(y_2)$
$L(cy)=cL(y)$

Suppose that $L$ is a **linear** transformation.
- (includes linear algebraic functions, and linear differential operators as special cases)

If $v_1$ and $v_2$ are solutions to the homogenous equation $L(x)=0$ then so are their sum $v_1+v_2$ so their span is a solution

Example $F([x,y,z])=z$; $F(x)=0$
Both $[1,0,0]$ and $[0,1,0]$ are both solutions 

Set of solutions is "2-dimensional" as any solution can be created with the combination of two vectors

Ex:
$L(y)=y\prime\prime-4y$ is linear
Check $y_1(t)=e^{2t},y_t(t)=e^{-2t}$ solve $L(y)=0$


Nonhomogeneous Principle
$L$ is linear
Let $y_p$ be any particular solution to $L(y)=f$
Let $y_h$ be any solution to $L(y)=0$
Then $L(y_p+y_h)=f$
and every solution of $L(y)=f$ has the form $y_p+y_h$
for some $y_h$

Strategy for finding all y where $L(y)=f$
Find a solution to $L(y)=f$
Find all solutions to $L(y)=0$








