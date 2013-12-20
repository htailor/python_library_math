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

Constant   | Value 
-----------|:-----: 
`half`     | 1/2  
`third`    | 1/3 
`twothirds`| 2/3 
`quarter`  | 1/4 
`root_pi`  | <img src="http://latex.codecogs.com/svg.latex?\sqrt\pi" border="0"/> 


Functions
---------

Function | Equation
---------:|:--------:
`inverse(x)` | <img src="http://latex.codecogs.com/svg.latex?\frac{1}{x}" border="0"/>
`squared(x)` | <img src="http://latex.codecogs.com/svg.latex?x^2" border="0"/>
`cubed(x)`  | <img src="http://latex.codecogs.com/svg.latex?x^3" border="0"/>
`cubed_root(x)` | <img src="http://latex.codecogs.com/svg.latex?x^\frac{1}{3}" border="0"/>
`sgn(x)` | <img src="http://latex.codecogs.com/svg.latex?\frac{x}{x}" border="0"/>
