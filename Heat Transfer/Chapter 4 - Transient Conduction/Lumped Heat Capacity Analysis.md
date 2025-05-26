# Note
- In exams, when tackling problems, always check for applicability

# One Dimensional Capacitance Method

## Formula

$$
\frac{\theta}{\theta_{i}}=\frac{{T-T_{\infty}}}{{T_{i}-T_{\infty}}}=\frac{e^{-hA_{S}}}{\rho Vc}
$$
Where:
- h=convection heat transfer coefficient
- $A_{s}$= surface area
- $\rho$ = density
- c = specific heat capacity
- $T_{i}$ = T at t=0
- $T_{\infty}$ = Surface temperature
- $\theta=T(t)-T_{\infty}$ 
- $\theta_{i}=T_{i}-T_{\infty}$


## Checking for Applicability
Lumped Capacitance method is only applicable if Biot number is less than or equal to 1

$$
\text{Biot Number} = \frac{\text{Resistance due to Conduction}}{\text{Resistance due to Convection}} \text{ must be } \leq 0.1
$$

$$
\text{Biot Number}=\frac{T_{s_{1}}-T_{s_{2}}}{{T_{s_{2}}}-T_{\infty}}=\frac{\frac{L_{c}}{kA}}{\frac{1}{hA}} = \frac{hL_{c}}{k}
$$
$$
L_c=\text{Characteristic Length}=\frac{{\text{Volume of Solid}}}{\text{Total Surface Area}}
$$
$$
\text{Fourier's Number} = Fo = \frac{\alpha t}{L^2_{c}}\text{ where } \alpha=\text{thermal diffusivity }
$$
Final solution for Lumped Heat Capacity Analysis for a solid one dimensional heat transfer would be:
$$
\frac{\theta}{\theta_{i}}=\frac{T(t)-T_{\infty}}{T_{i}-T_{\infty}}=e^{\left( \frac{Bi}{Fo} \right)}=\exp\left( -\frac{hA_{s}t}{\rho Vc} \right).\frac{\alpha t}{L^2_{c}}
$$
WARNING: ONLY USE WHEN BI<=0.1


