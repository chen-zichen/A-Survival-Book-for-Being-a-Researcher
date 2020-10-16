# Python to latex math equation

Generates LaTeX math description from Python functions.

```bash
pip install latexify-py
```

## Usage

```python
import math
import latexify
```

```python
@latexify.with_latex
def solve(a, b, c):
  return (-b + math.sqrt(b**2 - 4*a*c)) / (2*a)

solve
```

$$
solve(a,b,c)≜\frac{−b+\sqrt{b^2−4ac}}{2a}
$$



Ref: https://github.com/odashi/latexify_py