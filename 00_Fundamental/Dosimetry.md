## Fundamental for Dosimetry

### Photon Beams

| X (MV) | D_{max} | PDD @ 5 cm | PDD @ 10 cm | PDD @ 20 cm | Surface Dose (%) |
| :---   | :---    | :---       | :---        | :---        | :---             |
| Co $^{60}$ | 0.5  | 80.4       | 58.7        | 41.6        | 30               |
| 6FFF   |  |  |  |  |
| 6      | 1.5     | 86         | 67          | 40          | 15               |
| 10FFF  |  |  |  |  |
| 10     | 2.4     | 91         | 74          | 46          | ??               |
| 15     | 2.9     | 94         | 77          | 50          | 10               |

| X (MV) | $TPR_5^{10}$|$TPR_{10}^{20}$| TMR(5) | TMR(10) | $S_{cp} (40)$ | $S_c (40)$ | $S_{cp} (3)$ | $S_c (3) $ |
| :---   | :---        | :---          | :---   | :---    | :--- | :--- | :--- | :--- |
| Co $^{60}$ |         | 0.6           | 0.87   |  0.69   | | | | |
| 6FFF   |             |               |        |         | | | | |
| 6      | 0.84        | 0.67          |        |         | 1.12                       | 1.05 | 0.9 | 0.95 |
| 10FFF  |             |               |        |         | | | | |
| 10     | 0.87        | 0.74          |        |         | | | | |
| 15     | 0.89        | 0.76          |        |         | 1.08                       | 1.04 | 0.9 | 0.95 |

- Dose fall-off with depth --- $Co^{60}$: ~4\%/cm; &emsp; 6MV: ~3\%/cm; &emsp; 10MV: ~2.5\%/cm; &emsp; 15MV: ~2.2\%/cm

- FS $5\times 5$ has the biggest $d_{max}$. When FS > 5, $d_{max}$ decrease due to $S_c$; when FS < 5, $d_{max}$ decrease due to $S_p$.

- Photon FS $\uparrow$, $d_{\max} \downarrow$; Electron FS $\uparrow$, $d_{\max}\uparrow$

- Photon PDD shape due to: (i) attenuation, (ii) ISF, (iii) scatter, (iv) $e^-$ energy deposite nonlocally.

- For 20 cm separation, $D_{\max} = 1.06$ for 6 MV and 1.03 for 15 MV.

- POP clinically, if $d < 15$ cm, 6 MV or lower can be used; if $d > 20$ cm, 10 MV or higher must be used.

### Electron Beams

| E (MeV) | Surface (70+E)\% | Dmax | $d_{ref}$ | R50  | X (E/5)\% |
| :---:   | :---:            | :---:| :---:| :---:| :---:     |
| 6       | 73 (76)          | 1.3  | 1.3  | 2.4  | 1.2       |
| 9       | 78 (79)          | 2.1  | 2.1  | 3.6  | 1.8       |
| 12      | 83 (82)          | 2.9  | 2.9  | 5.0  | 2.4       |
| 16      | 88 (86)          | 3.3  | 3.9  | 6.7  | 3.2       |
| 20      | 93 (90)          | 1.9  | 4.9  | 8.3  | 4.0       |

- $d_{ref} = 0.6 R_{50} - 0.1$  &emsp;  $R_{50} = E_0/2.33$  &emsp;  $\bar{E_d} = \bar{E_0}\left( 1-\frac{d}{R_p} \right) $

- Therapeutic range: E/3 ($R_p \approx E / 2$, $R_{80} \approx E / 3$, $R_{90} \approx E / 4$, $PDD_X \approx E / 5$). Penumbra: $\sim 1$ cm

- Lateral scatter equilibrium: E/2.5 (field size) or 0.88 $\sqrt{E_{p, 0}}$ (distance from field edge)

- Lead shielding requirement: E/2+1 (mm) &emsp; [1 mm is the safety margin]

- Cerrobend shielding requirement: (E/2) $\times$ 1.2 + 1 (mm)

- PDD $e^\-$: $E \uparrow$ $\Rightarrow$ surface dose $\uparrow$, more X contamination. FS $\downarrow$ $\Rightarrow$ if FS < $R_p$, $d_{\max}$ $\downarrow$, surface dose $\uparrow$

- Oblique incidence ($> 20^{\circ}$) $\Longrightarrow$ surface dose $\uparrow$, dmax $\downarrow$, $R_p \uparrow$, and PDD shape change dramatically

- $R_p$ is independent of FS and dependent on beam energy only. $R_p$ is at $\sim$ 10\% depth dose position.

- X contamination typically <1\% for 4 MeV and <4\% for 20 MeV (dual scattering foils) (IAEA)

- $SSD_{\text{eff}}$ determined by ISF and dose measured @ dmax: $\frac{D_0}{D_g} = \left( \frac{SSD_{\text{eff}} + dmax + g}{SSD_{\text{eff}} + dmax} \right)^2$ with $g$ the gap btwn phantom and applicator (0 - 15 cm).

