Shaft - Rotating Member
Axle - Non-rotating Member

# Shaft stresses
Assuming a solid shaft with round cross section:

$$
\sigma_{a}=K_{f}\times \frac{32M_a}{\pi d^3}, \text{    }
$$
$$\sigma_{m}=K_{f}\times \frac{32M_m}{\pi d^3}$$
$$\tau _{a}=K_{fs}\times \frac{16T_a}{\pi d^3}$$
$$\tau _{m}=K_{fs}\times \frac{16T_m}{\pi d^3}$$

Combining the stresses into Von-Misses Stresses:

$$\sigma'_{a}=\sqrt{{\sigma_{a}}^{2}+{3\tau_{a}}^{2}}, \text{ same for mean stresses}$$

Depending on the failure criteria equation:

**Goodman**
$$
\frac{1}{n}=\frac{\sigma'a}{S_{e}}+\frac{\sigma'm}{S_{ut}}
$$


**Gerber:**
![[Pasted image 20251113201935.png|300]]

# Stresses for Rotating Shaft
- For rotating shaft with cyclic bending, and steady torsion:
	- $M_{m}$ and $\tau_{a}$ are 0

### ALWAYS CHECK FOR YIELDING IN SHAFTS
- Gerber and modified Goodman criteria require specific check for yielding
- ASME-Elliptic criteria takes yielding into account, but is not entirely conservative

Do this by:
$$n_{y}=\frac{S_{y}}{\sigma'_{max}}$$

where $\sigma'_{max}=\sqrt{(\sigma_{m}+\sigma_{a})^{2}+3(\tau_{m}+\tau_{a})^{2}}$

If $n_{y}\geq 1$, then the part will not yield.


S'e = 0.5*Sut

$ka=aS_{ut}^b$

