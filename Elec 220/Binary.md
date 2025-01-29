Unsigned Binary Integers 
- $x=x_{n-1}2^{n-1}+x_{n-2}2^{n-2}+...+x_1n^1+x_{0}2^{0}$
- Range from 0 to $2^n-1$

2s-Complement Signed Integers
- $x=-x_{n-1}2^{n-1}+x_{n-2}2^{n-2}+...+x_1n^1+x_{0}2^{0}$
- Range from $-2^{n-1}$ to $2^{n-1}-1$

To make an Unsigned Binary Integer -x you invert all the bits and add 1

What if we want to go from an 8bit to a 16bit representation in 2s-Complement Signed Integers.
What we do is we take the signed bit and replicate it to the left 
Ex:
- +2: 0000 0010 $\rightarrow$ **0000 0000 0**000 0010 = +2
- -2: 1111 1110 $\rightarrow$ **1111 1111 1**111 1110 = -2