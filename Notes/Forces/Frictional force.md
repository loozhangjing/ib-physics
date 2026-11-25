Frictional forces, $f$ oppose a body's motion.
# Static and dynamic friction
The difference is in the name — static friction acts on a static body, while dynamic friction acts on a body in motion. These two forces are mutually exclusive — a body cannot be static and move at the same time!

When pulling a body with force $F$, the frictional force $f$ varies as shown below.

```desmos-graph
bottom=-1;
left=-1;
hideAxisNumbers=true;
grid=false;
xAxisLabel=F;
yAxisLabel=f;
---
y = x | x > 0 | x < 5 | red
x = 5 | y > 3.5 | y < 5 | red
y = 3.5 | x > 5 | red

y = 3.5 | x > 0 | x < 3.5 | #999999 | dashed
y = 5 | x > 0 | x < 5 | #999999 | dashed

(0, 5) | black | label: μ_s * R
(0, 3.5) | black | label: μ_d * R
```

As $F$ increases, the body does not move until $F$ exceeds the **maximum** possible *static* friction force, $$f_s = \mu_s R$$
after which the body accelerates and the constant *dynamic* frictional force on the body is
$$f_d = \mu_d R$$
where $R$ is the normal force between the surfaces, $\mu_s$ is the coefficient of static friction and $\mu_d$ is the coefficient of dynamic friction.

>[!info]
>- $R$ is equal to the weight, $W$, i.e. $R = mg$
>- $\mu_s > \mu_d$ (which is obvious from the graph)

> [!warning]
> $\mu_sR$ does not give the static friction force, it gives the **maximum** possible static friction force!
