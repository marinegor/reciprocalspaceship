# reciprocalspaceship
![Build](https://github.com/Hekstra-Lab/reciprocalspaceship/workflows/Build/badge.svg)
![Documentation](https://github.com/Hekstra-Lab/reciprocalspaceship/workflows/Documentation/badge.svg)
[![codecov](https://codecov.io/gh/Hekstra-Lab/reciprocalspaceship/branch/master/graph/badge.svg?token=4XxNesZmXB)](https://codecov.io/gh/Hekstra-Lab/reciprocalspaceship)
[![apm](https://img.shields.io/apm/l/vim-mode.svg)](https://github.com/Hekstra-Lab/reciprocalspaceship/blob/master/LICENSE)  

Tools for exploring reciprocal space.

`reciprocalspaceship` provides a `pandas`-style interface for
analyzing and manipulating reflection data from crystallography
experiments. Using this library, it is possible to interactively
work with crystallographic data in Python, enabling easy
integration with modern scientific computing libraries. `reciprocalspaceship`
is intended to support the rapid prototyping of new crystallographic methods and
custom analyses while maintaining clear and performant code.

Features of this library include:

- Crystallographically-aware `pandas` objects, datatypes, and syntax that are familiar to Python users.
- Convenient integration with [GEMMI](https://gemmi.readthedocs.io/en/latest/) to provide built-in methods and
  support for developing functions that use space groups, unit cell parameters, and crystallographic
  symmetry operations.
- Support for reading and writing MTZ reflection files.

## Quickstart

To get started with `reciprocalspaceship`, see our [quickstart guide](https://hekstra-lab.github.io/reciprocalspaceship/userguide/quickstart.html)

## Documentation

For more details on the use of `reciprocalspaceship`, check out our [documentation](https://hekstra-lab.github.io/reciprocalspaceship).
