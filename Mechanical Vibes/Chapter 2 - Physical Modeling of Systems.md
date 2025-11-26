Assumptions taken:
- Physical system can be treated as a continuous piece of matter
- Newton's laws of motion apply
- Gravity is the only external force field
- The systems are not subject to reactions
- All materials are lineasr, isotropic, and homogeneous
- The usual assumptions of mechanics of material apply. 

# Discrete System Elements
### 1. Springs
- possesses the property of elasticity
- store or release potential energy
- K = N/m or Nm/rad
- $\text{Restoring Force } f_{k}=-F=-kx$
- $\text{Potential Energy}=U=\frac{1}{2}kx^{2}$
- Massless, no damping, linear
- There are TORSIONAL SPRING
	- $M_{s}=K_{\phi}\phi$ where $\phi=\text{Twist}$ and $M_s$ is torsional moment
	- $U=\frac{1}{2}K_{\phi}\phi^{2}$
Stiffness formulas

![[Pasted image 20251121181400.png]]
![[Pasted image 20251121181412.png]]

### 2. Mass
- possesses the inertia property
- store kinetic energy

$KE = \frac{1}{2}J\dot{\theta}^{2}$ for rotation

### 3. Dampers
- Used to dissipate energy
- Damping model mostly used in practice is linearly proportional to velocity
- Viscous damping coefficient (Ns/m or Nms/rad)
## Combinations of Springs
Parallel =  $\sum_{i=1}^{n} k_{i}$
Series = $\frac{1}{\sum \left( \frac{1}{k_{i}} \right)}$
