Let $F_n$ denote the $n$-th Fibonacci number.

From Joseph M. Shunia, March 9 2024 (Start):

$\binom{n-k}{k} = \left\lfloor \frac{(2^n+4^n)^k}{2^{n^2}} \right\rfloor \bmod{2^n}$

$F_n = ((2^n+1)^{n-1} \bmod{(4^n+2^n-1)}) \bmod{2^n}$

$F_n = \left\lfloor \frac{2^n(2^n + 1)^n}{4^n + 2^n - 1} \right\rfloor \bmod 2^n$

$F_n = \left\lfloor \frac{(2^n + 1)^n}{4^n + 2^n - 1} \right\rfloor \bmod 2^n$

$F_{n+k} = \left\lfloor \frac{2^n (2^n + 1)^{n+k+1}}{4^n + 2^n - 1} \right\rfloor \bmod 2^n ,$
for $n \geq k$.

$F_n = (2^{n (n-1)} \bmod{(4^n-2^n-1)}) \bmod{(2^n-1)}$

(End)

From Joseph M. Shunia, April 7 2024 (Start):

$F_n = 2^{-n} (((2^{n+1} + 1)^{n} \bmod{(4^{n+1} + 2^{n+1} - 1)}) - ((2^n + 1)^{n-1} \bmod{(4^n + 2^n - 1)}))$

(End)
