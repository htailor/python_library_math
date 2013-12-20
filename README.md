Python Math Library
===================


General Information
-------------------

Portable library of additional math functions and useful constants written for the Extendable Freely Jointed Chain project. Inspiration was taken from BOOST C++ numeric constants. The library inherits math functions from python.


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
`root_pi`  | <img src="http://latex.codecogs.com/gif.latex?\sqrt\pi" border="0"/> 


Functions
---------

Function|
:---------:|
`inverse(x)`|
`squared(x)`|
`cubed(x)`  |
`cubed_root(x)`|
`sgn(x)`|
`heaviside_step(x)`|
`binomial(n,k)`|
`double_binomial(n,k1,k2)`|
`multinomial(*k)`|
`factorial_approx(n)`|

