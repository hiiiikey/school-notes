![[Pasted image 20250526022928.png|150]]

$$
T=\frac{FD}{2}
$$
Therefore, the shearing stresses will be two: direct shear and torsion
$$
\tau=\frac{F}{A}+\frac{Tr}{J} \text{ where } r=\frac{d}{2} \text{ and } J=\frac{\pi d^4}{32}
$$

Lets define Spring Index, a measure of Coil Curvature (D), as:

$$C=\frac{D}{d}$$
Therefore, $\tau$ simplifies to:
$$
\tau=\frac{8FD}{\pi d^3}\left( \frac{2C+1}{2C} \right)=\frac{8FD}{\pi d^3}k_{S}\text{ where ks= shear stress correction factor}
$$
For design purposes, it is recommended to use C values of $4\leq C\leq 12$

## Wahl Stress Factor
In order to consider the effects of both direct shear as well as curvature of the wire, a Wahl's stress factor (K). It's defined as:
$$
K=\frac{4C-1}{4C-4}+\frac{0.615}{C}
$$
The Wahl's Stress factor may be considered as made of two sub-factors,

$K=Ks\times Kc$ where kc is Stress concentration factor due to curvature, and Ks is Stress factor due to shear

## Stresses in Helical Springs of Circular Wire

Say a load W is acting on a spring

$T=\frac{FD}{2}=\frac{WD}{2}=\frac{\pi}{16}\tau_{1}d^3$ where $\tau_{1}=\text{Torsional Shear Stress}$

Therefore: $$\tau_{1}=\frac{8WD}{\pi d^3}$$
$\tau_{2}=\text{Direct shear stress due to the load}=\frac{W}{\text{Cross-sectional Area of the Wire}}$
$$
\tau=\tau_{1}+\tau_{2}=\frac{8WD}{\pi d^3}\pm \frac{4W}{\pi d^2}
$$
The positive sign is used for the inner edge of the wire and negative sign is used for the outer edge of the wire.

## Deflection of Helical Springs of Circular Wire
$T=\frac{WD}{2}$
$L = \pi D\times n$
$\theta=\text{Angular deflection of the wire}$

$\text{Axial Deflection of the Spring } \delta=\theta \times \frac{D}{2}$
$\theta=\frac{TL}{JG}\text{ where G = Modulus of Rigidity}$
$\frac{W}{\delta}=\frac{Gd^4}{8C^3n}=constant$

