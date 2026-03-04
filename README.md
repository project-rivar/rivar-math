# rivar-math

Numerical foundations for Rivar, including linear algebra utilities, matrix operations, and precision-focused mathematical helpers.

## Overview

`rivar-math` is a core mathematics library for the Rivar project. It provides a reliable, high-precision set of numerical primitives that other Rivar components build upon. The library focuses on correctness and numerical stability, offering tools for working with vectors, matrices, and common mathematical operations required in data-intensive or scientific computing contexts.

## Features

- **Linear Algebra Utilities** — Vector operations (dot product, cross product, normalization, magnitude), space transformations, and decompositions.
- **Matrix Operations** — Creation, multiplication, transposition, inversion, determinant computation, and factorization of matrices of arbitrary size.
- **Precision-Focused Helpers** — Compensated summation, epsilon comparisons, rounding utilities, and guard against common floating-point pitfalls.

## Installation

### From Source

```bash
git clone https://github.com/project-rivar/rivar-math.git
cd rivar-math
```

Build instructions will be added once the package structure is finalized. Refer to the project's build tooling documentation for language-specific setup steps.

## Usage

Usage examples will be provided here as the API stabilizes. The following illustrates the intended style:

```python
# Example (Python — adjust for actual language/API)
from rivar_math import Matrix, Vector

# Create a 3x3 identity matrix
m = Matrix.identity(3)

# Create a vector and normalize it
v = Vector([3.0, 4.0, 0.0])
unit_v = v.normalize()  # [0.6, 0.8, 0.0]

# Matrix-vector multiplication
result = m @ unit_v
```

## API Reference

Full API documentation will be published alongside the first stable release. Key modules planned:

| Module | Description |
|---|---|
| `linalg` | Vector and matrix linear algebra operations |
| `matrix` | Matrix construction, decomposition, and factorization |
| `precision` | Floating-point utilities and numerical stability helpers |
| `transform` | Coordinate and space transformation utilities |

## Contributing

Contributions are welcome! Please open an issue to discuss proposed changes before submitting a pull request. Make sure any new functionality is accompanied by appropriate tests and documentation.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
