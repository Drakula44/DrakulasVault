## Definicija Uniforma raspodela
$X\sim \mathcal{U}[a,b]$
$$
\begin{align}
EX &= \frac{1}{2} (a+b) \\
varX &= \frac{1}{12} (b-a)^2
\end{align}
$$
## Dokaz 
$$
\begin{align}
EX &= \int_{a}^{b} x \frac{1}{b-a}dx \\
 &= \frac{1}{2} \frac{b^2-a^2}{b-a} \\
&= \frac{b+a}{2} \\
var(x) &= \int_{a}^{b} x^2 \frac{1}{b-a}dx - \left( \frac{b+a}{2} \right)^2 \\
&= \frac{1}{3} \frac{b^3 - a^3}{b-a} - \left( \frac{b+a}{2} \right)^2\\
&= \frac{1}{3} (b^2 +ab + a^2)  - \left( \frac{b+a}{2} \right)^2\\
&= \frac{1}{12} (b-a)^2
\end{align}
$$
