# 1. Fixed point iteration

$f(x)=4x^3-6x^2+7x-2.3=0$
$g(x)=\frac{2.3-4x^3+6x^2}{7}=x$
$\text{let }x_0 \text{ be }1.5$
$g(x_{0})=0.328571=x_{1}$
$g(x_{1})=0.4008378=x_{2}$
$g(x_{2})=0.4294877=x_{3}$
$g(x_{3})=0.4414093=x_{4}$

After 4 iterations, the root according to fixed point iteration is 0.4414903.

> [!NOTE]
> The real root is 0.45012.

# 2. False Position Method

$$
v=\frac{gm}{c}(1-e^{-(c/m)t})
$$

Substituting known values, we get:

$$
35=\frac{9.81*m}{15}(1-e^{-(15/m)9})
$$
Rearranging:

$$
f(m)=\frac{9.81*m}{15}(1-e^{-(15/m)9})-35
$$

By trial and error, you find out that there is a zero between 50 and 70, so that is our interval.

$c=\frac{{a(f(b))-b(f(a))}}{f(b)-f(a)}$
$c_{1}=\frac{{(59*0.104134428192)-(60*-0.328759601786)}}{0.104134428192--(0.328759601786)}=60.4313975144$
$f(c) \approx 0.289083900093,\text{ which is positive}$
f(a) is negative, and f(c) is positive, so the root is between them

so take the interval (50,60.4313975144) and run the second iteration:

$c_{2}=\frac{{a(f(b))-b(f(a))}}{f(b)-f(a)}=59.8014130884$

$f(c) \approx 0.0186324516667,\text{ which is positive}$
f(a) is negative, and f(c) is positive, so again, the root is between them

$c_{3}=\frac{{a(f(b))-b(f(a))}}{f(b)-f(a)}=59.7609759457$

$f(c) \approx 0.00119400355848,\text{ which is positive}$

$c_{4}=\frac{{a(f(b))-b(f(a))}}{f(b)-f(a)}=59.7583853431$

after four iterations, c = 59.7583853431
therefore, mass = 59.7583853431 kg.