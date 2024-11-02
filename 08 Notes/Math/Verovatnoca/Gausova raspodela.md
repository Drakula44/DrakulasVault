---
aliases:
  - Normalna raspodela
---
## Normalna raspodela
$X\sim\mathcal{N}(m,\sigma^2)$
$$
\begin{align}
f(x)&=\frac{1}{\sqrt{ 2\pi \sigma^2 }}e^{-\frac{(x-m)^2}{2\sigma^2}} \\
EX&=m \\
varX&=\sigma^{2}
\end{align}
$$

## Dokaz
$$
\begin{align}

E(X- m) &= \int_{-\infty}^{\infty} (x-m) \frac{1}{\sqrt{ 2\pi \sigma^2 }}e^{-\frac{(x-m)^2}{2\sigma^2}} \, dx \\
\Downarrow (x-m) = y &\land dy = dx \\
&= \int_{-\infty}^{\infty} y \frac{1}{\sqrt{ 2\pi \sigma^2 }}e^{-\frac{y^2}{2\sigma^2}} \, dy \\
\Downarrow & \text{neparna funkcija} \\
&= 0 \\
\Downarrow \\
E(X) - m &= 0 \\
E(X) &= m
\end{align}
$$
moze i bez ove pretpostavke samo uvede se smena $(x-m) = u$ i raspasce se integral na jedan koji je $m*1$ i drugi koji je 0 zbog neparnosti
$$
\begin{align}
var(X) &= \int_{-\infty}^{\infty} (x-m)^2 \frac{1}{\sqrt{ 2\pi \sigma^2 }}e^{-\frac{(x-m)^2}{2\sigma^2}} \, dx \\
\Downarrow & u=(x-m) \\
&= \int_{-\infty}^{\infty} u^2 e^{- \frac{u^2}{2\sigma^2}} \, dx  \\
&= 2*\int_{0}^\infty 
\end{align}

$$
Parcijalna integracija i onda moze da se primeni ![[Dokaz gausovog integrala]] bas kul #todo dovrsiti ovo nekad
