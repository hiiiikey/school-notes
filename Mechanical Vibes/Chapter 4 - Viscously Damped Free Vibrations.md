$\text{Viscous Damping Force}=\tau A=\frac{\mu AV}{h}=-c\dot{x}$
c is the damping constant (Ns/m or kg/s)

1. Select a suitable coordinate
2. Determine static equilibrium position, measure from that position
3. Draw FBD
4. Apply Newton's second law of motion

* $m\ddot{x}=-c\dot{x}-kx$

We assume a solution of $x(t)=Ce^{st}$ where C and s are constants.

- $ms^{2}+cs+k=0$

![[Pasted image 20251122002743.png]]


solving for s using the quadratic formula, we get:

$s_{1,2}=\frac{-c\pm \sqrt{ c^2-4mk }}{2m}$

then, we will have two particular solutions:
$\large{x(t)=C_{1}e^{s_{1}t}+C_{2}e^{s_{2}t}}$

$\text{Critical Damping Constant }= C_{cr}=2m\sqrt{ \frac{k}{m} }=2m\omega_{n}$

$\Large{\zeta=\frac{c}{c_{cr}}}$

Overdamped = $\zeta>1$
Underdamped = $\zeta<1$
Critically damped = $\zeta=1$

$\text{Frequency of damped vibration } = \omega_{d}=\sqrt{ 1-\zeta^2}\omega_{n}$
- Always less than the undamped natural frequency $\omega_{n}$

For underdamped systems:

$\large{x=Xe^{\zeta \omega_{n}t}\cos(\omega_{d}t-\phi)}$

### Logarithmic Decrement $\delta$

$\delta=\frac{1}{n}\ln\left( \frac{x_{1}}{x_{1+n}} \right)$
$$\delta=\frac{2\pi\zeta}{\sqrt{ 1-\zeta^2 }}$$

Energy dissipated for one cycle:

$\Delta U=\int_{0}^{2\pi/\omega}c\left( \frac{dx}{dt} \right)^{2}dt=\pi c\omega X^2$

## Torsional System
