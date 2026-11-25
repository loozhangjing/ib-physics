# A man runs 800m due north in 100 s, followed by 400 m due south in 80 s. Calculate his change in velocity, for the whole journey.

Change in velocity is $v - u$, where $v$ is the final velocity and $u$ is the initial velocity.

Assuming that motion due north is positive, the displacement for the latter part of the journey is **-400 m**, with a negative sign!

$$\begin{aligned}
Change\ in\ velocity &= v - u\\
&= \dfrac{-400}{80} - \dfrac{800}{100}\\
&= -5 - 8\\
&= - 13\ ms^{-1}
\end{aligned}$$

Do **not** do $\dfrac{400}{80} - \dfrac{800}{100}$!
# An object with an initial velocity of 20 m s<sup>-1</sup> and initial position of -75 m experiences a constant acceleration of -2 m s<sup>-2</sup>. Sketch the position-time graph for this motion for the first 20 s.
Use the equation $s = ut + \dfrac{1}{2}at^2$.
$$\begin{aligned}
s &= 20t + \dfrac{1}{2}(-2)t^2\\
s &= -t^2 + 20t
\end{aligned}$$
Note that this is a quadratic equation, and the maximum point of the graph lies within the range defined in the question, i.e. 0 to 20 seconds. So do the two roots of the graph.

```desmos-graph
left=-10; right=30;
top=110; bottom=-10;
---
s = -t^2 + 20t|t>=0|t<=20|
```
The above graph, however, does not take into account **the initial displacement of -75 m**. The equation representing the displacement of this object should have a constant term of -75.
$$s = -t^2 + 20t -75$$

```desmos-graph
left=-10; right=30;
top=35; bottom=-85;
---
s = -t^2 + 20t - 75|t>=0|t<=20
(0,-75)|label:t = 0, s = -75
(5,0)|label:t = 5, s = 0
(10,25)|label:t = 10, s = 25
(15,0)|label:t = 15, s = 0
(20,-75)|label:t = 20, s = -75
```

