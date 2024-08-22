# Singular Value Decomposition (SVD)

<img src="svd_equation.png" alt="SVD equation" height="100px">

<img src="svd_graph.png" alt="SVD graph" height="350px">

This figure illustrates the relationship between the Data Space (U) and Feature Space ($V^T$) derived from the Singular Value Decomposition (SVD) of matrix A. 


This repository provides an implementation and exploration of Singular Value Decomposition (SVD) in Python. SVD is a powerful matrix factorization technique used in numerous applications such as data reduction, noise filtering, and latent semantic analysis.

## Overview

Singular Value Decomposition (SVD) decomposes a matrix `A` into three matrices:

$$
A = U \Sigma V^T
$$

- `U` is an orthogonal matrix containing the left singular vectors.
- `\Sigma` is a diagonal matrix with singular values.
- `V^T` is the transpose of an orthogonal matrix containing the right singular vectors.

## Features

- Implementation of SVD from scratch in Python.
- Example scripts demonstrating practical uses of SVD.
- Visualization tools for understanding the decomposition results.

## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/galenwilkerson/singular-value-decomposition-SVD.git
cd singular-value-decomposition-SVD
pip install -r requirements.txt
```

## Usage

To utilize the SVD implementation:

1. Review the `svd.py` file for the core SVD functions.
2. Refer to `example_usage.py` for practical examples and applications of SVD.


## Contributing

Contributions are encouraged! To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes and push them to your fork.
4. Open a pull request to merge your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
