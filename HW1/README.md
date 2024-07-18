# Matrix Operations and Determinants

This repository contains Python code for performing and timing two matrix operations and for determining the singularity of a triangular matrix using numpy.

## Links

||Google Drive <br />(including the <br /> LaTeX report file)|Google Colab|
|---|---|---|
| Links | [![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/drive/folders/1rCjhaq3HmOCN6Dbk9RsoH3KxrtYfMG6I?usp=sharing) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1IELeB6DIhU7UsWqWyqJv2AYvPXrwGk72) |

## Requirements
To run the code, ensure you have the following installed:
- Python 3.x
- numpy

## Setup
Run the code in any Python environment that supports interactive sessions, such as Jupyter Notebook or a standard Python interpreter.

## Overview

### Operation 1
The function `operation1` performs a matrix-vector multiplication manually by iterating over columns of the matrix and summing the results.

### Operation 2
The function `operation2` performs the same matrix-vector multiplication using numpy's built-in `np.matmul` function.

### Determinant Calculation
The code also includes a section for generating a random upper triangular matrix and calculating its determinant to determine if the matrix is singular or non-singular.

## Code Organization

### Operation Functions
| Function | Description |
|---|---|
| `operation1(m, n, A, k)` | Performs matrix-vector multiplication manually. |
| `operation2(A, k)` | Performs matrix-vector multiplication using numpy's `np.matmul`. |

### Determinant Calculation
| Section | Description |
|---|---|
| Determinant Calculation | Generates a random upper triangular matrix, calculates its determinant, and checks if it is singular or non-singular. |

## Running Examples
Example usage can be found in HW1_ML.ipynb

## License
This project is licensed under the MIT License - see the LICENSE file for details.
