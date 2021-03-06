# Datascience python toolbox in Docker

Docker environment with python and the following data science packages :
* numpy: support for large, multi-dimensional arrays and matrices
* matplotlib: plotting library for Python and its numerical mathematics extension NumPy.
* scipy: library used for scientific computing and technical computing
* scikit-learn: machine learning library integrates with NumPy and SciPy
* pandas: library providing high-performance, easy-to-use data structures and data analysis tools
* nltk: suite of libraries and programs for symbolic and statistical natural language processing for English

## Build Dockerfile
```python
docker build .
```

## Pull and run from repo
```python
docker run -it cvirginie/pytoolbox:latest python3
```
