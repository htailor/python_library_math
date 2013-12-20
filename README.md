Python Math Library
===================


General Information
-------------------

Portable library of additional math functions and useful constants written for the Extendable Freely Jointed Chain projects. Inspiration was taken from BOOST C++ numeric constants. The library inherits math functions from python.


Installation
------------

Place `libmath.py` in the current working directory of your project and import functions by normal methods. 

```python
from libmath import *
```

Constants
---------

Constant | Value |
---------|:-----:| 
half     | 1/2  |
third    | 1/3 |
twothirds| 2/3 |
quarter  | 1/4 |
root_pi  | <img src="http://latex.codecogs.com/svg.latex?\sqrt\pi" border="0"/> |


Functions
---------

<table align="center">
  <tr>
    <th>Function</th><th>Equation</th>
  </tr>
  <tr>
    <td>inverse(x)</td><td><img src="http://latex.codecogs.com/svg.latex?\frac{1}{x}" border="0"/></td>
  </tr>
  <tr>
    <td>squared(x)</td><td><img src="http://latex.codecogs.com/svg.latex?x^2" border="0"/></td>
  </tr>
  <tr>
    <td>cubed(x)</td><td><img src="http://latex.codecogs.com/svg.latex?x^3" border="0"/></td>
  </tr>
  <tr>
    <td>cubed_root(x)</td><td><img src="http://latex.codecogs.com/svg.latex?x^\frac{1}{3}" border="0"/></td>
  </tr>
  <tr>
    <td>sqn(x)</td><td><img src="http://latex.codecogs.com/svg.latex?\frac{x}{|x|}" border="0"/></td>
  </tr>
</table>
