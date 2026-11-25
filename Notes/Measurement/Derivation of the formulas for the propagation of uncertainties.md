# Addition and subtraction
$$
\begin{aligned}
M_1 + M_2 &= a + b\pm (\Delta a + \Delta b)\\
M_1 - M_2 &= a - b\pm (\Delta a + \Delta b)
\end{aligned}
$$
### Why?
Think of uncertainties as a range, with a minimum and maximum value.
$$
\begin{aligned}
&(M_1+M_2)_\text{minimum}\\
&= M_{1_\text{minimum}} + M_{2_\text{minimum}}\\
&= a - \Delta a + b - \Delta b\\
&= a + b - (\Delta a + \Delta b)
\end{aligned}
$$
Similarly,
$$\begin{aligned}
&(M_1 + M_2)_\text{maximum}\\
&= a + b + (\Delta a + \Delta b)
\end{aligned}$$
Therefore,
$$M_1 + M_2 = a + b \pm (\Delta a + \Delta b)$$
## Multiplication & division
$$
\begin{aligned}
M_1 \cdot M_2 &= ab \pm (\dfrac{\Delta a}{a} + \dfrac{\Delta b}{b}) \cdot ab\\
\dfrac{M_1}{M_2} &= \dfrac{a}{b}\pm (\dfrac{\Delta a}{a} + \dfrac{\Delta b}{b}) \cdot \dfrac{a}{b}
\end{aligned}
$$
## Explanation
$\dfrac{\Delta a}{a}$ and $\dfrac{\Delta b}{b}$ are the fractional uncertainties of $a$ and $b$ respectively. Multiplying their sum by the measured value ($a \cdot b$ or $\dfrac{a}{b}$) converts it back into an absolute uncertainty.
## Why do we sum the fractional uncertainties?
$M_1 = a \pm \Delta a$ means the minimum and maximum values of $M_1$ are $a - \Delta a$ and $a + \Delta a$ respectively. The same goes for $M_2$.

The minimum value of $M_1 \cdot M_2$ would be the product of the minimum values of $M_1$ and $M_2$, i.e.
$$\begin{aligned}
&(a - \Delta a) \cdot (b - \Delta b)\\
&= ab - a \Delta b - b \Delta a + \Delta a \Delta b\\
&= ab - (a \Delta b + b \Delta a) + \Delta a \Delta b\\
&= ab - a \cdot (\Delta b + \dfrac{b \Delta a}{a}) + \Delta a \Delta b\\
&= ab - ab \cdot (\dfrac{\Delta b}{b} + \dfrac{\Delta a}{a}) + \Delta a \Delta b\\
&= ab - ab \cdot (\dfrac{\Delta b}{b} + \dfrac{\Delta a}{a}) + \Delta a \Delta b\\
\end{aligned}$$
Rearranged, and ignoring the product of 2 delta values:
$$\begin{aligned}
&(M_1 \cdot M_2)_\text{minimum}\\
&= ab - (\dfrac{\Delta a}{a} + \dfrac{\Delta b}{b}) \cdot ab
\end{aligned}
$$
Similarly,
$$\begin{aligned}
&(M_1 \cdot M_2)_\text{maximum}\\
&= ab + (\dfrac{\Delta a}{a} + \dfrac{\Delta b}{b}) \cdot ab
\end{aligned}
$$
### More intuitively
Multiplying two measurements causes the range of possible values to multiply too.