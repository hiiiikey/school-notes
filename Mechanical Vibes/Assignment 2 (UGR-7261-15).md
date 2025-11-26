# Abel Sintayhu  - Section 1
### Assumptions:
- C (damping coefficient) is given,
- The system is a single degree of freedom 

Frequency-Response (a.k.a general amplitude ration) is given by: 

$$
|H(\omega)|=\frac{1}{\sqrt{ (1-r^{2})^{2} + (2cr^{2})^{2}}}, \text{ }r=\frac{\omega}{\omega_{n}}
$$

where:
$\omega=\text{Excitation frequency}$
$\omega_{n}=\text{Natural (Undamped) frequency}$

Maximum Amplitude occurs at the Resonant Frequency ($\omega_{r}$)

For small damping, we can approximate $\omega_{r}$ as follows:
$$\omega_{r}\approx \omega_{n}\sqrt{ 1-2c^{2} }$$
which means, after simplification, the max amplitude is given by:

$$
|H(\omega_{r})|\approx \frac{1}{2c\sqrt{ 1-c^{2} }}
$$
### Note 
If c isn't provided, it can be determined with 
$$
c=\frac{\Delta \omega}{2\omega_{n}}=\frac{\omega_{2}-\omega_{1}}{2\omega_{n}}
$$
where $\Delta \omega =\text{Bandwidth}$
and $\omega_{2} \text{ and } \omega_{1}$ are upper and lower half frequencies respectively, such that 
$$H(\omega_{1})=H(\omega_{2})=\frac{H(w_{r})}{\sqrt{ 2 }}$$


