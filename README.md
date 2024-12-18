# diffusion2D

## Instructions for students

Please follow the instructions in [pypi_exercise.md](https://github.com/Simulation-Software-Engineering/Lecture-Material/blob/main/03_building_and_packaging/pypi_exercise.md).

The code used in this exercise is based on [Chapter 7 of the book "Learning Scientific Programming with Python"](https://scipython.com/book/chapter-7-matplotlib/examples/the-two-dimensional-diffusion-equation/).

## Project description
This project solves the two-dimensional diffusion equation using finite difference methods. The diffusion equation is an important partial differential equation that describes the distribution of a quantity (such as temperature) over space and time. This package includes functions to simulate the diffusion process on a 2D grid and visualize the results.

## Installing the package

### Using pip3 to install from PyPI
To install the package directly from PyPI, you can use pip3:

```sh
pip install -i https://test.pypi.org/simple/ mullamm_diffusion2d==0.0.1
```

### Required dependencies

The following dependencies are required to run this package:
	•	numpy
	•	matplotlib

These dependencies will be installed automatically when you install the package using pip3.

## Running this package
## Running this package

To run the diffusion simulation, you can use the `solve` function provided in the package. Below is an example script that demonstrates how to use the package:

```python
from mullamm_diffusion2d import diffusion2d
diffusion2d.solve()
```

# Run the simulation with default parameters
solve()

# Run the simulation with custom parameters
solve(dx=0.05, dy=0.05, D=2.0)

## Citing
Mahek Mulla (2024). mullamm_diffusion2d: A Python package for solving the 2D diffusion equation. Available at: https://github.com/mahek-mulla/diffusion2D.git
