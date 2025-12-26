### Kernel
If $T$ is a linear transformation then the kernel of $T$ (ker $T$) is the set of all points where $v\in V: T(v)=0$
$ker(A)=\{x: Ax=0\}=ker(REF(A))$
### Image
$im(T)=image(T)=\{w\in W: v \in V, w=T(v)\}$
All the vectors in $W$ that map to a output of $T$

The image of $A$ is spanned by the corresponding pivot columns of $A$

Proposition:
$T$ is into if and only if the $ker(T)=\{\textbf{0}\}$

Proof: Suppose $T$ is into, If $v \in ker(T)$ then $T(v)=0=T(0)$, so $v=0$ 
Suppose that $ker(T)=\{0\}$, and $T(v)=T(u)$
Subtracting $0=T(u)-T(v)=T(u-v), u-v \in ker(T), u=v$ 
This proves it because $u,v$ are arbitrary 



