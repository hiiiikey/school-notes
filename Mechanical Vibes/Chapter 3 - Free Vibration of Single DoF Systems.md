# Response
1. Select a suitable coordinate
2. Determine static equilibrium configuration of the system, measure displacement from that equilibrium position
3. Draw FBD of mass when positive displacement and velocity are given
4. Write EoM (Equation of Motion)
	1. Newton's 2nd law of motion
	2. D'Alembert's Principle
	3. Virtual work method (The principle of virtual displacement)
	4. Energy method (The principle of conservation of energy)
NB: Newton's Law
- $m\dot{x}\dot{}(t)=-kx(t), x(0)=x_{0}, \dot{x}_{0}=V_{0}$

## EoM of a spring-mass system in vertical position
### Newton's second law of motion
$F(t)=m\ddot{x}$
$M(t)=J\ddot{\theta }$
### D'Alembert's Principle
$F(t)-m\ddot{x}=0$
$M(t)-J\ddot{\theta}=0$

### Principle of Virtual Displacement
Virtual work done by spring force = $\Delta W_{s}=-(kx)\delta x$
Virtual work done by the inertia force = $\Delta W_{i}=-(mx)\delta x$

"total virtual work done by the forces will be zero"

$\Delta W_{s}+\Delta W_{i}=0$

### Principle of Conservation of Energy

$\text{Kinetic Energy} + \text{Potential Energy}=constant$
$\frac{d}{dt}(KE+U)=0$

## Solution For Translational System

Divide the EOM by m
$\ddot{x}+\frac{k}{m}x=0$
Solution could be in the ff forms:
$x=X\cos \omega t$
$x=X\sin \omega t$
$x=A\cos \omega t+B\sin \omega t$ (we pick this one)
$x=Ce^{st}$

We pick the third one.

$\omega=\pm \sqrt{ \frac{k}{m} }\text{ is the undamped natural frequency of the system}$

Apply $x_{t=0}=A=x_{o}\text{ (initial displacement)}$ and $\frac{dx}{dt}=B\omega_{n}=\dot{x_{0}}=V_{0}\text{ (intial velocity)}$

Hence, the particular solution becomes:

$$x(t)=x_{0}\cos(\omega_{n}t)+\frac{{\dot{x_{o}}}}{\omega _{n}}\sin(\omega_{n}t)$$
where $\omega_{n}=\text{Undamped natural frequency}$

$\text{Amplitude}= \sqrt{ A^{2}+B^{2} }$
$\text{Phase Angle}=\tan^{-1}\left( \frac{B}{A} \right)$
$f_{n}=\frac{\omega}{2\pi}\text{ in Hz}$
$\text{Time Period}=\frac{1}{f_{n}}$

## Torsional System
### Equation of Motion

$J_{0}\ddot{\theta}+k_{t}\theta=0$
$\omega_{n}=\sqrt{  \left( \frac{k_{t}}{J_{0}} \right)}$
$f_{n}=\frac{\omega}{2\pi}\text{ in Hz}$
$\text{Time Period}=\frac{1}{f_{n}}$

### Solution
$$\theta(t)=A_{1}\cos \omega t+A_{2}\sin \omega t$$
$\theta(t=0)=\theta_{0}\text{ and } \dot{\theta}(0)=\text{Initial Radial Velocity}$

$\text{Where } A_{1}=\theta_{0}\text{ and } A_{2}={\frac{\dot{\theta}}{\omega}}$


