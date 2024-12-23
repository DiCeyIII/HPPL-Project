This project explores methods to accelerate the k-means clustering algorithm, a computationally intensive task. We implemented optimized versions of k-means using Numba for just-in-time compilation and CUDA for GPU acceleration. These custom implementations are directly compared against the scikit-learn's standard k-means in terms of runtime performance. Our results demonstrate significant speedups achieved by leveraging both Numba and CUDA, especially with larger datasets.

The repository contains the source code, performance benchmark results, and instructions for reproducing our findings.
