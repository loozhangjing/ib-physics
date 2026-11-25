# Question
A moving body of mass $m$ collides with a stationary body of double the mass and sticks to it. Calculate the fraction of the original kinetic energy that is lost.
# Solution
Let $u$ be the initial velocity of the body of mass $m$.
Let $v$ be the final velocity.

Momentum is conserved, therefore
$$\begin{aligned}
p_\text{before collision} &= p_\text{after collision}\\
mu &= (m + 2m)v\\
mu &= 3mv\\
u &= 3v\\
v &= \dfrac{1}{3}v
\end{aligned}$$
Note that the initial momentum of the body of mass $2m$ is $0$ because it was stationary. 

$$\begin{aligned}
\dfrac{\Delta E_K}{E_{K_\text{before collision}}} &= \dfrac{E_{K_\text{after collision}} - E_{K_\text{before collision}}}{E_{K_\text{before collision}}}\\
&= \dfrac{ \dfrac{1}{2} (m + 2m)v^2 - \dfrac{1}{2}mu^2 }{ \dfrac{1}{2}mu^2 }\\
&= \dfrac{3v^2 - u^2}{u^2}\\
\text{Substitute } v &= \dfrac{1}{3}u,\\
\dfrac{\Delta E_K}{E_{K_\text{before collision}}} &= \dfrac{3(\dfrac{1}{9}u^2) - u^2}{u^2}\\
&= -\dfrac{2}{3}\\
\end{aligned}$$

$$\therefore \text{Fraction of the original kinetic energy that was lost } = \dfrac{2}{3}$$
# Why I wrote this question down here
I did not realise that momentum is conserved, so I couldn't progress beyond $\dfrac{3v^2 - u^2}{u^2}$.