# Undamped Vibrations

$$\Large{m\ddot{x}+kx=F(t)}\text{ is the Equation of Motion}$$

General solution: $X(t)=\underbrace{ C_{1}\cos \omega t+C_{2}\cos \omega t }_{ x_{h} }+\underbrace{ x\cos \omega t }_{ x_{o} }$

inserting $x_{p}(t)$ into the Equation of Motion, we get:

=> $m(-x\omega^{2}\cos \omega t)+k(x\cos \omega t)=F_{0}\cos \omega t$

This get simplified to:

=> $\Large{x=\frac{F_{0}}{k-m\omega^{2}}=\frac{\frac{F_{0}}{k}}{\frac{k-m\omega^{2}}{k}}}$ 
=> $\Large{x=\frac{\delta_{st}}{1-\left( \frac{\omega}{\omega_{n}} \right)^{2}}}$
$$\Large{\underbrace{ \frac{x}{\delta_{st}} }_{ \text{Magnification factor} }=\frac{1}{1-\underbrace{ \left( \frac{\omega}{\omega _{n}} \right)^2 }_{ \text{Frequency Ratio} }}}$$

Case 1: 
Case 2: 
# Damped Vibrations

$$\Large{m\ddot{x}+c\dot{x}+kx=F(t)}\text{ is the Equation of Motion}$$

Assumed solutions:
$x_{p}(t)=X\cos(\omega t-\phi)$
$x_{h}(t)=c_{1}\cos \omega_{n}t+ c_{2}\sin \omega_{n}t$

$x_{p}(t)=X\cos(\omega t-\phi)$
$\dot{x}_{p}(t)=-X\omega \sin (\omega t-\phi)$
$\ddot{x}_{p}(t)=−X\omega^{2}cos(\omega t−ϕ)$

$m(−Xω^{2}cos(ωt−ϕ))+c(−Xωsin(ωt−ϕ))+k(Xcos(ωt−ϕ))=F_{0}cosωt$

Use the trigonometric relations:
$\cos(\omega t-\phi)=\cos(\omega t)\cos (\phi) + \sin (\omega t)\sin (\phi)$
$\sin(\omega t-\phi)=\sin(\omega t)\cos(\phi)-\cos(\omega t)\sin(\phi)$

3

expand the shifted trig functions using  


Solution of the above two equations:

$$
\Large{X=\frac{F_{0}}{[(k-m\omega^2)+c^{2}\omega^{2}]^{1/2}}}
$$

and 

$$
\Large{\phi=\tan ^{-1}\left( \frac{c\omega}{k-m\omega^{2}} \right)}
$$

Dividing both numerators and denominators of the amplitude's equation by k, and making the following substitutions: 

$\omega_{n}=\sqrt{ \frac{k}{m} }$
$\zeta=\frac{c}{c_{c}}\implies \frac{c}{m}=2\zeta \omega_{n}$
$\delta_{st}=\frac{F_{0}}{k}$

we obtain

$$\Large{\underbrace{ \frac{X}{\delta_{st}} }_{ \text{Magnification Factor} }=\frac{1}{\left( \left[ 1-\left( \frac{\omega}{\omega_{n}} \right)^{2} \right]^{2} + \left[ 2\zeta\left( { \frac{\omega}{\omega_{n}} } \right) \right]^{2} \right)^{1/2}}}=\frac{1}{\sqrt{ (1-r^{2})^{2} +(2\zeta r)^{2}}}$$



