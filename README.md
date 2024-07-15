# Gradient Descent and Newton's Method Comparison

This repository contains Python code that demonstrates the implementation and comparison of Gradient Descent and Newton's Method for optimizing functions. The code uses `matplotlib` and `sympy` libraries for visualization and symbolic computation respectively.

## Implementation Details

- `decent(func, x_0, step_size, tolerance, colour)`: Implements Gradient Descent for a given function `func`, starting from initial point `x_0`, with specified `step_size` and `tolerance`. It plots the convergence graph.
- `newton(func, x_0, tolerance, colour)`: Implements Newton's Method for a given function `func`, starting from initial point `x_0`, with specified `tolerance`. It plots the convergence graph.

## Examples

### Gradient Descent Example

![Gradient Descent Example](https://upload.wikimedia.org/wikipedia/commons/thumb/f/ff/Gradient_descent.svg/300px-Gradient_descent.svg.png)

*Caption: Example plot of Gradient Descent. Image source: [Wikipedia](https://en.wikipedia.org/wiki/Gradient_descent)*

### Newton's Method Example

![Newton's Method Example](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/NewtonIteration_Ani.gif/300px-NewtonIteration_Ani.gif)

*Caption: Example animation of Newton's Method. Image source: [Wikipedia](https://en.wikipedia.org/wiki/Newton%27s_method)*

## Requirements

- Python 3.x
- Required Python packages: `matplotlib`, `sympy`, `numpy`

## Usage

1. Clone this repository.
2. Run the Python script `gradient_descent_newton.py`.
3. Observe the plotted graphs comparing Gradient Descent and Newton's Method for various functions and initial conditions.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
