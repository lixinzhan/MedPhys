## Fundamental Physics in Radiation Therapy

- 1 electron mass = 0.511 MeV, 1 amu = 931.6 MeV,  $m=m_0/\sqrt{1-β^2}$
- 1 Ci=37 GBq, the disintegration of $1 g ^{226}Ra/sec$. $^{226}Ra$ specific activity: 37 GBq/g or 8.25 $(R⋅cm^2)/(hr⋅mCi)$.
- 1 R = 0.876 cGy = $2.58×10^{-4}$ C/kg; $\left(\frac{W}{e}\right)_{air}$ = 33.97 J/C = 33.97 eV/ion pair; 1 eV = $1.6×10^{-19}$ J.
- Elements: $Pb_{82}^{207}$; $W_{74}^{184}$; $^{64}_{29}Cu$; $^{7.51}H_2O$; $^{7.78}Air$; $^{8.3}LiF$; 
- Compton: $h \nu' = h \nu \frac{1}{1 + \alpha (1 - \cos \theta)}$, $E = h \nu \frac{\alpha (1 - \cos \theta)}{1 + \alpha (1 - \cos \theta)}$ 
with $\alpha = h \nu / m_0 c^2$ 
- Classical/Thomson scattering: $\frac{d \sigma_0}{d \Omega} = \frac{r_0^2}{2} \times (1 + \cos^2 \theta)$
or $\frac{d \sigma_0}{d \theta} = \frac{r_0^2}{2} \times (1 + \cos^2 \theta) \times 2\pi sin\theta $

### Attenuation Coefficients

| $\tau / \rho$ (Photoelectric) | $\sigma_R / \rho$ (Rayleigh) | $\sigma / \rho$ (Compton) | $\kappa / \rho$ (Pair Production) |
| :---           |          :---      | :---             | :---              |  
| $1/(h \nu)^3$ | $1 / (h \nu)^2$   | Decrease with $h \nu$ | Increase with $h\nu$ |
| $Z^3$         | $Z$               | Independent     | $Z$ |
| Photon energy totally absorbed by a bound electron, which is ejected with energy $h \nu - E_B$. All the photon energy is transferred to medium | $\gamma \xrightarrow{having} \lambda$ $\xrightarrow{\text{vibration of}} e^-$  $\xrightarrow{emit} \lambda$ $\xrightarrow{combined} \gamma$ | Photon interacts with an electron at rest, which results in the photon get scattered and the electron set to a motion. Part of the photon energy is transferred to the medium | Photon disappeared with all energy transferred to the electron-positron pair. |

![mu_rho_jc](https://user-images.githubusercontent.com/6154401/230149872-449fa1dc-ea48-455b-b7b4-fd41921ff404.PNG)

- $\left( \frac{\mu}{\rho} \right)_{water}$: Start from 5 $cm^2 / g$ at 0.01 MeV; Co-60 (1.25 MeV) 5\% per cm or 0.05 $cm^2 / g$; 6 MeV 3\% per cm or 0.03 $cm^2 / g$; and 15 MeV 2\% per cm or 0.02 $cm^2 / g$.
- $\left( \frac{\mu_{ab}}{\rho} \right)_{water}$: Start from 5 $cm^2 / g$ at 0.01 MeV; 0.02 $cm^2$/g @ 0.1 MeV; 0.03 $cm^2 / g$ @ 1 MeV; and 0.015 $cm^2 / g$ @ 10 MeV.

### F-factor: 
```math 
D_{med} = X f_{med} \;\;\;\;\;\;\text{with}\;\;\;\;\;\;
f_{med} = \left(\frac{W}{e}\right)_{air} \left(\frac{\bar{\mu}_{ab}}{\rho} \right)_{air}^{med}
```
- For $E \gtrsim 200$ keV, $f_{bone}$, $f_{muscle}$, and $f_{wat}$ are roughly the same, since Compton dominates.
- $f_{muscle} \lesssim f_{wat}$ for $E \gtrsim 200$ keV.
- $f_{bone} \lesssim f_{wat}$ for 200keV $\lesssim E \lesssim 6$ MeV.
