Zelimo da dokazemo:
$$
\begin{align}
\int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi},
\end{align}
$$
$$
\begin{align}

I &= \int_{-\infty}^{\infty} e^{-x^2} \, dx \\

I^2 &= \left( \int_{-\infty}^{\infty} e^{-x^2} \, dx \right)^2 \\
I^2 &= \int_{-\infty}^{\infty} e^{-x^2} \, dx \int_{-\infty}^{\infty} e^{-y^2} \, dy \\
I^2 &= \int_{-\infty}^{\infty} \int_{-\infty}^{\infty} e^{-(x^2 + y^2)} \, dy  \, dx   \\
\Downarrow & x=r \cos \theta \land y=r\sin \theta \land dx \, dy = r \, dr \, d\theta \\
I^2 &= \int_{0}^{2\pi} \int_{0}^{\infty} e^{-r^2} r \, dr \, d\theta
\end{align}
$$
#TODO zavrsiti ovo ali sada je ocigledno