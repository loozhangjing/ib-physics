# Prelude
## Terminology
Let
$$
\begin{aligned}
M_1 &= a \pm \Delta a\\
M_2 &= b \pm \Delta b
\end{aligned}
$$
- $M_1$ is the measurement
- $a$ is the measured value
- $\Delta a$ is the absolute uncertainty of $a$
## Absolute and fractional uncertainty
- **absolute** uncertainties are expressed in the same unit of measurement as the measured value, while:
$$\text{Fractional uncertainty} = \dfrac{\text{Absolute uncertainty}}{\text{Measured value}}$$
# Propagation of uncertainties
## Addition & subtraction
Add their **absolute** uncertainties together:
$$
\begin{aligned}
M_1 + M_2 &= a + b\pm (\Delta a + \Delta b)\\
M_1 - M_2 &= a - b\pm (\Delta a + \Delta b)
\end{aligned}
$$
Multiplying a measurement by a constant also multiplies its absolute uncertainty:
$$2M_1 = 2a \pm 2\Delta a$$
## Multiplication & division
Add the **fractional** uncertainties of the measurements together, and convert it back to an absolute uncertainty.
$$
\begin{aligned}
M_1 \cdot M_2 &= ab \pm (\dfrac{\Delta a}{a} + \dfrac{\Delta b}{b}) \cdot ab\\
\dfrac{M_1}{M_2} &= \dfrac{a}{b}\pm (\dfrac{\Delta a}{a} + \dfrac{\Delta b}{b}) \cdot \dfrac{a}{b}
\end{aligned}
$$
## Why?
[[Derivation of the formulas for the propagation of uncertainties]]