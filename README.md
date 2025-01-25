# Bivariate Matrix-Valued Linear Regression (BMLR)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![arXiv](https://img.shields.io/badge/arXiv-2412.17749-b31b1b.svg)](https://arxiv.org/abs/2412.17749)

This repository provides implementations and experiments for [**Bivariate Matrix-Valued Linear Regression (BMLR)**](https://arxiv.org/abs/2412.17749), a statistical framework for estimating parameters in matrix-valued regression models under identifiability and sparsity assumptions.

## Key Features
1. **Optimization-Free Estimators**  
   Explicit estimators avoiding iterative optimization procedures.

2. **Theoretical Guarantees**  
   Non-asymptotic performance bounds validated on synthetic and real-world data.

3. **Sparse Recovery**  
   Exact support recovery algorithms for sparse parameters.

4. **Numerical Simulations**  
   Evaluation using Frobenius, operator, and max-norms.

5. **Real-World Applications**  
   Image denoising experiments on CIFAR-10.

## Model Overview

The BMLR model assumes:  
$$Y_t = A^* X_t B^* + E_t \quad \text{for } t = 1, \ldots, T$$
where:
- $Y_t \in \mathbb{R}^{n \times p}$: Response matrices
- $X_t \in \mathbb{R}^{m \times q}$: Predictor matrices
- $A^* \in \mathbb{R}_+^{n \times m}$: Row-normalized parameter matrix
- $B^* \in \mathbb{R}^{q \times p}$: Unconstrained parameter matrix
- $E_t$: Independent matrix Gaussian noise

## Contributing

1. Fork the repository
2. Create your feature branch
3. Submit a pull request with documentation

## Citation

```bibtex
@article{bettache2024bmlr,
  title   = {Bivariate Matrix-Valued Linear Regression (BMLR): Finite-sample performance under Identifiability and Sparsity Assumptions},
  author  = {Bettache, Nayel},
  journal = {arXiv preprint arXiv:2412.17749},
  year    = {2024}
}
```

---
**Contact**  
- 📧 Email: [nbb45 [at] cornell [dot] edu]  
- 💻 GitHub: [@nayelbettache](https://github.com/nayelbettache)  
- 🌐 Website: [https://nayelbettache.github.io](https://nayelbettache.github.io)  
