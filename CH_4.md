# CH_4

## Changes in Lengths of An Axially Loaded Members

$$
P=k\delta\qquad\delta=fP\\[2ex]
k\text{ is the stiffness of the spring}\\[2ex]
f\text{ is the flexibility of the spring}\\[2ex]
$$

- **stiffness**: is the force required to produce a unit elongation
- **flexibility**: is the elongation produced by a unit force

$$
\begin{cases}
    \delta = L\cdot \varepsilon\\[2ex]
    \sigma = E\cdot \varepsilon\\[2ex]
    P =\sigma \cdot A
\end{cases}\\[6ex]
\Rightarrow\;\delta=\frac{L}{EA}P\\[2ex]
$$

### Sign Convention

|    Sign     |   Forces    | Displacement |
| :---------: | :---------: | :----------: |
| Positive(+) |   Tension   |  Elongation  |
| Negative(-) | Compression | COntraction  |

### Use Method of Sections

$$
\begin{cases}
    \sigma=\frac{P(x)}{A(x)}=E\varepsilon\\[2ex]
    \varepsilon=\frac{d\delta}{dx}
\end{cases}\\[6ex]
\Rightarrow d\delta = \frac{P(x)}{A(x)E}dx\\[2ex]
\delta=\int_{0}^{L}{\frac{P(x)}{A(x)E}dx}
$$

- $P(x)$: internal normal force at the section, located a distance x from one end
- $A(x)$: x-sectional area of the bar, expressed as a function of x

**Constant Load and x-Sectional Area**

$$
\delta=\frac{L}{EA}P
$$

**Bars with Intermediate Axial Loads**

$$
\delta=\sum{\frac{L}{EA}P}
$$
