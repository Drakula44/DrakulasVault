# Poasonova raspodela
$X\sim Poiss(\lambda)$
$$p_{X}(k)=e^{-\lambda}\cdot{\frac{\lambda^{k}}{k!}},\qquad\lambda>0,k=0,1,...$$
## Dokaz
$$
\begin{align}
\sum_{k=0}^{\infty} \frac{\lambda^k}{k!} &= e^\lambda \\
&\Downarrow \frac{d}{d\lambda} \\
\sum_{k=0}^{\infty} k\frac{\lambda^k}{k!} &= \lambda e^\lambda \\
&\Downarrow \frac{d}{d\lambda} \\
E\{ X^2 \} = e^{-\lambda}\sum_{k=0}^{\infty} k^2\frac{\lambda^k}{k!} &= \lambda(e^\lambda + \lambda e^\lambda) =\lambda(1+\lambda)e^\lambda\\
E\{ X \} &= \sum_{k=0}^{\infty}ke^{-\lambda} \frac{\lambda^k}{k!} \\
&= e^{-\lambda}\lambda\\
&= \lambda \\
var(X) = E\{ X^2 \} - (EX)^2 &= \lambda^2 + \lambda - \lambda^2  \\
&= \lambda
\end{align}
$$
