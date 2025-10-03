# MLib: Linear Algebra Library with Built-in Automatic Differentiation

MLib is a performant linear algebra library implemented in C with a Python interface, featuring key matrix operations and automatic differentiation capabilities. It’s designed for numerical computing and machine learning tasks, providing matrix functions optimized for speed and an intuitive Python API.

---

## Features

- Essential matrix operations: addition, subtraction, multiplication, division, exponentiation, logarithm, exponentials, transpose, reshape, and more.
- Optimized matrix multiplication for 2D arrays.
- Matrix inversion for square positive semi-definite matrices.
- Views and slicing with shared memory support.
- Random vector/matrix generation with flexible bounds.
- Built-in automatic differentiation (autograd) for gradient computation.
- High-performance C backend with Python bindings.

---

## Installation & Setup

To build the C library, use the provided Makefile:

```bash
make
```

Clean build artifacts with:


```bash
make clean
```


---

## Tutorial and Usage

MLib’s [tutorial.ipynb](tutorial.ipynb) notebook contains a comprehensive, step-by-step tutorial with examples on basic operations, benchmarking performance, and practical use cases like linear regression. It is highly recommended to start there for a guided introduction.

If you don’t have it installed, you may need to install `matplotlib` for plotting in the tutorial:

```bash
pip3 install matplotlib
```


---

## Performance

MLib significantly outperforms vanilla Python list operations in element-wise matrix computations, making it suitable for large scale numerical tasks.

---

## Testing

Run the unit tests to verify the installation:

```bash
python3 -m unittest discover -s tests
```

---

## Credits & Resources

The project draws from foundational and practical resources including:

- [LU Decomposition - Wikipedia](https://en.wikipedia.org/wiki/LU_decomposition)
- [PyTorch Internals - E. Z. Yang](http://blog.ezyang.com/2019/05/pytorch-internals/)
- [Recreating PyTorch from Scratch - Towards Data Science](https://towardsdatascience.com/recreating-pytorch-from-scratch-with-gpu-support-axand-automatic-differentiation-8f565122a3cc)
- [DIY Autograd Engine - Medium](https://medium.com/sfu-cspmp/diy-deep-learning-crafting-your-own-autograd-engine-from-scratch-for-effortless-backpropagation-ddab167faaf5)
- Matrix differentiation notes by Randal J. Barnes, University of Minnesota
- [NumPy Internals](https://numpy.org/devdocs/dev/internals.html)

---

For an in-depth introduction, code examples, and use cases, please see the `tutorial.ipynb` included in this repository. It provides a clearer, interactive walkthrough of MLib’s capabilities.

---

## License

This project is licensed under the MIT License. See LICENSE for details.

---

Thank you for exploring MLib!  
Happy computing.
