# Question
An object is thrown vertically upwards with an initial velocity of $\pu{20 m s-1}$ from the edge of a cliff that is $\pu{25 m}$ from the sea below.

Determine the time to hit the sea.
# Solution(s)
## Shorter method
Assume motion vertically upwards is positive.
$$\begin{aligned}
u &= 20 \text{ m s}^{-1}\\
g &= -9.81 \text{ m s}^{-2}\\
\text{Final displacement}, s &= ut + \dfrac{1}{2}gt^2\\
\end{aligned}$$
Take the displacement at $t = 0$ s to be $0$ m.
$\therefore$ The displacement when the object hits the sea is $-25$ m.
$$\begin{aligned}
-25 &= 20t + \dfrac{1}{2} \cdot 9.81 \cdot t^2\\
t &\approx 5.08 \text{ s}\\
\end{aligned}$$
Graph of $s$ against $t$:

```desmos-graph
top=25;bottom=-30;
left=-2;right=6;
---
y = 20t + 1/2 * gt^2|t >= 0|t <= 5.08|
g = -9.81
```
## Longer method
Find the time taken for the motion upwards and the motion downwards separately.

```desmos-graph
top=25;bottom=-30;
left=-2;right=6;
---
y = 20t + 1/2 * gt^2|t >= 0|t <= 2.04|
y = 20t + 1/2 * gt^2|t >= 2.04|t <= 5.08|red|
g = -9.81
```

When the object is at its highest point (the maximum point of the graph), the velocity is $0 \text{ m s}^{-1}$.
$$\begin{aligned}
v &= u + gt\\
0 &= 20 + -9.81t\\
t &\approx 2.0387 \text{s}\\
\end{aligned}$$
Now we need to find the maximum height of the object, in order to find the total displacement for the motion downwards.
$$\begin{aligned}
v^2 &= u^2 + 2gs\\
0^2 &= 20^2 + 2(-9.8)s\\
s &= \dfrac{-(20^2)}{2(-9.8)}\\
s &\approx 20.4082 \text{ m}
\end{aligned}$$
The velocity of the object is also $0 \text{ ms}^{-1}$ when it has reached its lowest point, the sea.
$$\begin{aligned}
s &= ut + \dfrac{1}{2}gt^2\\
- 20.4082 - 25 &= 0t + \dfrac{1}{2} \cdot -9.81 \cdot t^2\\
t &\approx 3.0426 \text{ s}\\\\
\text{Total time} &\approx 2.0387 + 3.0426\\
&\approx 5.08 \text{ s}
\end{aligned}$$
Notice how the longer method still uses the same motion of equation $s = ut + \dfrac{1}{2}gt^2$ as the shorter method. I used this method when I first encountered this question because there were previous sub-questions asking for the object's maximum height and the time taken to reach that maximum height, so the redundancy you see here of calculating extra information just to apply the same equation did not occur to me then. And, I didn't realise one equation could give both positive and negative displacements.
