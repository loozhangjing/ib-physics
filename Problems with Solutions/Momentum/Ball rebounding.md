# Question
A ball of mass $\pu{0.20 kg}$ moving at $\pu{3.6 m s^-1}$ on a horizontal floor collides with a vertical wall. The ball rebounds with a speed of $\pu{3.2 m s^-1}$. The ball was in contact with the wall for $\pu{12 ms}$. Determine the maximum force exerted on the ball, assuming that the force depends on time according to Figure 4.4.

```desmos-graph
hideAxisNumbers=true;
xAxisLabel=t;
yAxisLabel=F;
left=-2;
bottom=-2;
---
y = 2x - 4 | y > 0 | y < 4 | black
y = -2x + 12 | y > 0 | y < 4 | black
```
# Solution
The force in the graph is positive, and it acts on the ball in the direction away from the wall, causing it to rebound. Therefore, the direction away from the wall is the positive direction.
$$\begin{aligned}
u &= \pu{-3.6 m s^-1}\\
v &= \pu{3.2 m s^-1}
\end{aligned}$$
We have the mass of the ball, which means we can calculate the change in momentum, $\Delta p$, or the **impulse** of the ball.
$$\begin{aligned}
\Delta p &= mv - mu\\
&= 0.2 \cdot 3.2 - 0.2 \cdot -3.6\\
&= \pu{-1.36 N s}
\end{aligned}$$

$\Delta p$ is also $F_{avg}t$, the *average* force multiplied by time. $F_{avg} = \dfrac{F_{min} + F_{max}}{2}$, and since $F_{min} = 0 N$,
$$F_{avg} = \dfrac{1}{2}F_{max}$$
which in this case is obvious from the area of the diagram.

Therefore,
$$\begin{aligned}
\Delta p &= \dfrac{1}{2}F_{max}t\\
\pu{-1.36 N s} &= \dfrac{1}{2} F_{max} \cdot \pu{\dfrac{12}{100} s}\\
F_{max} &= \pu{226.667 N}
\end{aligned}$$

# Why I wrote this question down here

I was confused on whether $F = \dfrac{mv - mu}{t}$ gives average force or maximum force. My final answer turned out to be $\pu{-113.333 N}$, which is the value of $\dfrac{1}{2} F_{max}$ rather than $F_{max}$.
(Also, note the negative sign. I gave the velocities the wrong directions.)

Turns out, there is no such thing as impulsive force in IBDP Physics, which is what my previous curriculum associated this formula with. $\dfrac{mv - mu}{t}$ actually gives the *average* force, and I just didn't know that.
# Source
2023 Cambridge textbook: worked example 4.4