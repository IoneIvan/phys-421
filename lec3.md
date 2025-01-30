# Lectuer 3

### Electric FIeld due to a Dipole

![pic11 picture of body diagram of positive and negative charges E field and point P](./images/lect2/pic11.png)

$\vec{E_{net}} = \vec{E_+} + \vec{E_-}$

Because the direction of $E_+$ and $E_-$ are in the same axis we simply write:

$\Rightarrow E_{net_z} = \frac{k(+Q)}{r_+^2} + \frac{k(-Q)}{r_-^2} \,$
$\Rightarrow E_{net_z} = kQ[\frac{1}{r_+^2} - \frac{1}{r_-^2}]$

Assume you are given $d$ and $z$ (the dinstance between charges and the distance from the origin to point $p$).

$r_+= z + \frac{d}{2}$
$r_- = z - \frac{d}{2}$

$E_{net_z} - kQ[\frac{1}{(z+\frac{d}{2})^2} - \frac{1}{(z-\frac{d}{2})^2}]$

**P.S.**: The answer will be 
$$E_{net} = E_{net_z} = -2k\frac{Qd}{z^3}$$

To solve this you would need *Binomial Expansion*
```could be used during the exam```
$(1+x)^n = a + nx + \frac{n(n-1)}{2!} ...$
if $-1 < x < 1$

```Force somthing in equation to look like binomial exxpansion```

Asume $z>>d$ `resonable assumption irl` <br>
$\Rightarrow (z \frac{d}{2})^2 = z^2(1-\frac{d}{2z})^2$
$\Rightarrow (z +\frac{d}{z}) = z^2(1 +\frac{d}{2z})^2$
$\Rightarrow (1 + \frac{d}{2z})^2 = 1 + 2(\frac{d}{2z}) + (\frac{d}{2z})$
$\Rightarrow (1-\frac{d}{2z})^2 = 1 + 2(-\frac{d}{2z}) + (\frac{d}{2z})$

**Temrs**: 
define $p = qd$
$\Rightarrow$ dipole momnet $\vec{p} =+/- qd\hat{z}$

The direction of $\vec{p}$ goes from negative charge to positive charge.
so $\vec{p} = -qd\hat{z}$

[pic 2]

## 5 Electric FIeld due to a Continuous Charge Distribution


You have a material (not a conductor) that has a collection of charged particles. Creating a charge distribution. 

In that distribution each section $dq$ will produce an E-field, $dE$ at some point $p$.

The total E field at opint p is $E_net = \int{dE} \Rightarrow dE = \frac{kdq}{r^2}$

`The charge would get so small (in scale) as if its a particles.

### A long line of charge
What is the electric field due to a long line of charge at point $p$?

[pic 3]

Point $p$ is the distance $x$ away from the center of the long line.
How do we switch from $dQ$ to $dy$?
**Charge Density**: Charge is uniformly distributed accross the material.
**Charge Linear Density**, $\lambda = \frac{Q}{y} = \frac{dQ}{dy}$`amout of charge held in the dinstance over charge???`
\rarw dQ =lamda dy
dE =frac{k lamda dy}{r^2}
r depends on y =. r^ = x^2 + y^2

=> dE = frac{K lamd}{x^2 + y^2}

Breakup dE into components
=> dE_x = dEcos thet
dE_y = dEsin thet

After this you can integrate.
Also assuming you have limits of dy

>Q: in 3d?
>A: you use volume densityt, 3d integral


Assume now the long line is infinitly long => +/- $\infin$
\theta becoms a more resonable integrand going from 0 to +/- frac{pi}{2} as y goes from +/- infinity.

=> dE_x = dEcos thet = frac{k lamd}{x^2 + y^2}dcos thet dy
tan thet = y/x => y = x tan thet
=> dy/d thet = x/cost^2thet
=> dy = (xd thet) cos^2 thet

----------------
=> x = r cos thet
=> r = x / cos thet

=> dE_x = (k lamd)/(x^2 + y^2) cos thet dy
= (k lamd)/r^2 cos thet dy = (k lamd)/r^2 cos thet (x d thet)/cos^2 thet
= k lamd(cos^2 thet)/x^2 cos thet x\cos^2 thet d thet
= (k lamd)/x cos thet d thet

> do it yourself
=> dE_y = (k lamd)\x sin thet d thet

$dEy = \frac{k\lambda}$

int(dEx = Ex = int_(-pi/2)^(pi/2) (klamd)/x cos thet d thet 
=> Ex = k lamd / x(sin thet from )