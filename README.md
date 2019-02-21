# Quadratic Equations Solver

This module allows you to solve [quadratic equations](https://en.wikipedia.org/wiki/Quadratic_equation).

# How to use

Before module using need to install Python 3.5.

The program interface of the module is represented by the **get_roots** function:

```py
get_roots(a, b, c)

```

Function arguments:

* **a** - the quadratic coefficient (must be non-zero)
* **b** - the linear coefficient
* **c** - the constant

The function returns a tuple of two elements. The content of the tuple depends on the value of the discriminant:

* **(None, None)** - when the discriminant is less than zero
* **(root1, None)** - when the discriminant is zero
* **(root1, root2)** - when the discriminant is greater than zero


An example of using the module to solve quadratic equations:

```py
>>> import quadratic_equation
>>>
>>> root1, root2 = quadratic_equation.get_roots(1, 2, -24)
>>> print('Roots of quadratic equation: {} {}'.format(root1, root2))
Roots of quadratic equation: -6.0 4.0
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
