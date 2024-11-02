## Binomna raspodela
$X\sim Bin(n,p)$
ili $X\sim \sum_{i=1}^nX_{i}$ gde je $X_{i}$ nezavisna slucajna promenljiva bernulijeve raspodele 
$$p_{X}(k)={\binom{n}{k}}p^{k}(1-p)^{n-k},\qquad k=0,1,\ldots,n$$
## Dokaz

$$
\begin{align}
X_{i}\sim Ber(p)\;\; \text{i sve su ne zavisne medjusobno} \\
E\{ X \} = E\left\{  \sum X_{i}  \right\} = n E\{ X_{0} \} =np 
\end{align}
$$
$$
var(X) =var\left( \sum X_{i} \right) = \sum var(X_{i}) = np(1-p)
$$
Takodje moze da se dokaze kao: $$


\begin{align}
(x+y)^n &= \sum_{k=0}^n \binom{n}{k}x^ky^{n-k} \\
&\Downarrow \frac{d}{dx} \\
n(x+y)^{n-1} &= \sum_{k=0}^n k \binom{n}{k}x^{k-1} y^{n-k} \\
nx(x+y)^{n-1} &= \sum_{k=0}^n k \binom{n}{k}x^{k} y^{n-k} \\
&\Downarrow \frac{d}{dx} \\
nx(x(n-1)(x+y)^{n-2} + (x+y)^{n-1}) &= \sum_{k=0}^n k^2 \binom{n}{k}x^{k} y^{n-k} \\
nx(x+y)^{n-2}(xn - x + x + y) &= \sum_{k=0}^n k^2 \binom{n}{k}x^{k} y^{n-k} \\
\Downarrow x=p \;\;&\land\;\; y = 1-p \\
np((1-p)+ np) &= E\{ X^2 \} \\
var(X) &= E\{ X^2 \} - (EX)^2 \\
var(x) &= np(1-p) + (np)^2 - (np)^2 \\
var(x) &= np(1-p)
\end{align}
$$

