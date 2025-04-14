- An extended surface (also known as a combined conduction-convection system or a fin) is a solid within which heat transfer by conduction is assumed to be one dimensional, while heat is also transferred by convection (and/or radiation) from the surface in a direction transverse to that of conduction.
![[Pasted image 20250413150537.png|350]]

- Fins increase surface area.
  
  ![[Pasted image 20250413150556.png|350]]
## Fins of Uniform Area
![[Pasted image 20250413150706.png|300]]

$$
\frac{d^2T}{dx^2}-\frac{hP}{kA_{c}}(T(x)-T_{\infty})=0
$$
where 
- P = perimeter
- Ac = Cross-Sectional Area

Let's define a excessive temperature $\theta(x)=(T(x)-T_{\infty})$

at the base (x=0), $T=T_b\,\text{ OR  } \theta=\theta_{b}$ 

and $m^2=\frac{hP}{kA_{c}}$

$$
\frac{d^2\theta}{dx^2}-m^2\theta=0
$$


## Temperature distribution and heat loss for fins 

![[Pasted image 20250413152511.png]]

## Fin heat transfer rate
$$
M = q_{f}=\sqrt{hPkA_{c}}\,\,\theta_{b} \, \text{, where } \theta_{b}=T_{b}-T_{\infty}
$$

## Fin Effectiveness

Note that:
$$q_{f}=\frac{T_{b}-T_{\infty}}{R_{thermal,fin}}=\sqrt{hPkA_{c}}\,\,\theta_{b} \, $$

Therefore:

$$\epsilon_{f}=\frac{R_{thermal,base}}{R_{thermal,fin}}$$

- where: $R_{t,b}=\text{resistance due to convection of the exposed base}= \frac{1}{hA_{c,base}}$

## Fin Efficiency

$$
\eta_{f}=\frac{q_{f}}{q_{max}}
$$

but $q_{max}=hA_{f}\theta_{b}$ (where $A_f$ is surface area of the fin)

therefore:
$$\eta_{f}=\frac{q_{f}}{hA_{f}\theta_{b}}$$

For a straight fin of uniform cross section and an adiabatic tip:
$$
\eta_{f}=\frac{M \tanh mL}{hPL\theta_{b}}=\frac{\tanh mL}{mL}
$$

