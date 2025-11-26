Lielina Solomon Getachew - UGR/6634/17
# Assignment 01 - Number 7

$$I_s = I_1 + I_2$$

Use current-division:
$$I_1 = I_s \frac{G_1}{G_1 + G_2}, \qquad 
I_2 = I_s \frac{G_2}{G_1 + G_2}$$

**Conductances.**  
$$G_1 = \frac{1}{2}, \qquad G_2 = \frac{1}{3}$$  
$$G_1 + G_2 = \frac{5}{6}$$


Through the $2\:\Omega$ resistor:
$$I_1 = 12 \cdot \frac{\tfrac{1}{2}}{\tfrac{5}{6}}
       = 12 \cdot \frac{1}{2} \cdot \frac{6}{5}
       = 7.2\:\text{A}$$

Through the $3\:\Omega$ resistor:
$$I_2 = 12 \cdot \frac{\tfrac{1}{3}}{\tfrac{5}{6}}
       = 12 \cdot \frac{1}{3} \cdot \frac{6}{5}
       = 4.8\:\text{A}$$

- Current through the $2\:\Omega$ resistor:  
  $$I_{2\Omega} = 7.2\:\text{A}$$

- Current through the $3\:\Omega$ resistor:  
  $$I_{3\Omega} = 4.8\:\text{A}$$

# Assignment 02 - Number 1

Write the sum as a single sinusoid:
$$
i(t)=A\sin\omega t + B\cos\omega t
$$
with $A=56.5685,\; B=42.4264$.

Amplitude:
$$
R=\sqrt{A^2+B^2}=70.71064
$$

Phase (radians):
$$
\phi=\tan^{-1}\left( \frac{B}{A} \right)=0.64350139\ \text{rad}\approx36.8699^\circ
$$

Thus
$$
\boxed{\,i(t)=70.71064\sin\!\big(\omega t+0.64350139\big)\,=70.71064\sin(\omega t+36.8699^\circ)}
$$

(Alternatively $i(t)=70.71064\sin(\omega t+36.8699^\circ)$.)

# Assignemnt 02 - Number 2

Given:
- $R = 8\:\Omega$
- $L = 15.915\text{ mH} = 0.015915\:\text{H}$
- $f = 50\:\text{Hz}$  
- $\omega = 2\pi f = 2\pi(50) = 314.159\:\text{rad/s}$

Inductive reactance:
$$X_L = \omega L = 314.159 \times 0.015915 = 5.0\:\Omega$$

Impedance of a series RL coil:
$$Z = R + jX_L = 8 + j5\:\Omega$$

Magnitude:
$$|Z| = \sqrt{8^2 + 5^2} = \sqrt{89} = 9.434\:\Omega$$

Phase angle:
$$\theta = \tan^{-1}\left(\frac{5}{8}\right) = 32.005^\circ$$


$$\boxed{Z = 8 + j5\:\Omega}$$  
or  
$$\boxed{|Z| = 9.434\:\Omega \;\angle\; 32.0^\circ}$$