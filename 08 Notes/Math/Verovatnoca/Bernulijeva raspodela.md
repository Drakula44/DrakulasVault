# Bernulijeva raspodela
$X \sim Ber(p)$
$$
\begin{align}
X&\sim\left({\begin{array}{l l}{0}&{1}\\ {1-p}&{p}\end{array}}\right) \\
EX &= p \\
varX&=p - p^2 = p(1-p)
\end{align}
$$
## Dokaz
### Ocekivanje
$$
\begin{align}
x_{0}&=1-p,\;\;x_{1}=p \\
E\{ X \} &= 0(1-p) + 1p  \\
&= p \\ \\ \\
\end{align}
$$
### Varijansa
$$
\begin{align}
var(X) &= E\{ (X-EX)^2 \}  \\
&= E\{ X^2 \} - p^2  \\
&= 0^2(1-p)+1^2p - p^2 & \\
&= p - p^2
\end{align}
$$
