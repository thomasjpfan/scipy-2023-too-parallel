# Can There Be Too Much Parallelism? @ SciPy 2023

[Link to slides](https://thomasjpfan.github.io/scipy-2023-too-parallel/)

Numerical Python libraries can run computations on many CPU cores with various parallel interfaces. When we simultaneously use multiple levels of parallelism, it may result in oversubscription and degraded performance. This talk explores the programming interfaces used to control parallelism exposed by libraries such as NumPy, SciPy, and scikit-learn. We will learn about parallel primitives used in these libraries, such as OpenMP and Python's multiprocessing module. We will see how to control parallelism in these libraries to avoid oversubscription. Finally, we will look at the overall landscape for configuring parallelism and highlight paths for improving the user experience.

## License

This repo is under the [MIT License](LICENSE).
