# gptmath

apply gpt onto the math world

# tree

## philosophy

prompt gpt to do the 80% work;

## road map

let gpt complete the road map;

complete a math knowledge collector

interact with github repo

start training model

helping to solve equations

## 

| Sympy  | LaTeX  | maths     |
|--------|--------|------------|
| `x**2` | `x^2` | $x^2$ |
| `sin(x)` | `\sin(x)` | $sin(x)$ |
| `integrate(f, x)` | `\int f dx` | $\int f dx$ |

```python
from sympy import symbols, Function

hbar, t, x, m = symbols('hbar t x m')
Psi = Function('Psi')(t, x)
V = Function('V')(x)

eq = (1j * hbar * Psi.diff(t) - (hbar**2 / (2 * m)) * Psi.diff(x, x) + V * Psi)
```
```latex
i\hbar \frac{{\partial \Psi}}{{\partial t}} = -\frac{{\hbar^2}}{{2m}} \frac{{\partial^2 \Psi}}{{\partial x^2}} + V(x) \Psi
```
Schrödinger equation
$$i\hbar \frac{{\partial \Psi}}{{\partial t}} = -\frac{{\hbar^2}}{{2m}} \frac{{\partial^2 \Psi}}{{\partial x^2}} + V(x) \Psi$$


| Python | LaTeX | Description |
| ------ | ----- | ----------- |
| `from sympy import symbols, Function; hbar, t, x, m = symbols('hbar t x m'); Psi = Function('Psi')(t, x); V = Function('V')(x); eq = (1j * hbar * Psi.diff(t) - (hbar**2 / (2 * m)) * Psi.diff(x, x) + V * Psi)` | `i\hbar \frac{{\partial \Psi}}{{\partial t}} = -\frac{{\hbar^2}}{{2m}} \frac{{\partial^2 \Psi}}{{\partial x^2}} + V(x) \Psi` | Schrödinger equation $i\hbar \frac{{\partial \Psi}}{{\partial t}} = -\frac{{\hbar^2}}{{2m}} \frac{{\partial^2 \Psi}}{{\partial x^2}} + V(x) \Psi$ |




