# OIM_7502_Midterm

## SciPy Documentation
https://docs.scipy.org/doc/scipy/tutorial/index.html#user-guide

## SciPY Installation Instructions
  To install SciPY, you must follow these steps:
  1) Command: initiate the installation process (usually downloads its dependencies)
        !pip install scipy

  2) Depending on the system and configurations, it may be needed to install the additional libraries (NumPy & Matplotlib)
        !pip install numpy matplotlib

  3) Once installations are complete, we import the library, and therefore verifying everything it was properly downloaded
        import scipy

  4) If there are no errors, SciPy is ready to be used

## Library overview (SciPY) Overview
  SciPy is an open-source library for mathematics, science, and engineering that was built on top of NumPy. It provides additional functionality, as it provides tools for a wide range of applications.
  SciPy was designed to be a powerful and efficient toolkit for scientific computing tasks, and it includes modules for optimization, integration, interpolation, eigenvalue problems, signal and image processing, statistics, and others.
  Data Scientists often use SciPy to perform complex numerical operations and analyses efficiently, we can deep dive in the following:

  Statistical Analysis: Hypothesis testing, descriptive statistics, and probability distributions
  Optimization: 
  Signal and Image Processing
  Numerical Integration
  Linear Algebra
  Machine Learning

## SciPY for Data Science
The use of SciPy is important for Data Science as it makes easier the everyday tasks.
Since it expands on the capabilities of NumPy, this library provides an additional set of tools specifically designed for scientific and data science applications (ready to use tools).
      Ready to use tools: scipy.cluster is a good example which provides tools for clustering included in SciPy
      
      Math functions: scipy.stats includes functions for statistical tests like the t-test, and probability distributions
      
      Statistical Distribution:scipy.stats includes probability distributions like the normal, binomial, and exponential

      Optimization: We can fine tune parameters and optimize functions. The use of scipy.optimize offers methods like minimize for finding the minimum of a function, crucial for optimizing parameters in machine learning models

      Integration & Differentiation: Computing definite integrals (quad) and differentiation (derivative), which are common in scientific simulations

      Signal and Image Processing: scipy.signal provides tools for filtering, spectral analysis, and signal processing (convolve, spectrogram), while scipy.ndimage is used for image-related operations (filters, morphology)

      Linear Algebra: matrix operations (relevant to data analysis). scipy.linalg extends NumPy with additional linear algebra operations 

      Sparse Matrices: scipy.sparse provides efficient data structures and algorithms for sparse matrices, which is needed for for handling large datasets.