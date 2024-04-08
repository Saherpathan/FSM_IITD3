# FSM: UNSUPERVISED LEARNING 📊

This repository contains implementations of the K-Means Clustering and Principal Component Analysis (PCA) algorithms from scratch in Python using Numpy and Pandas for the task of unsupervised learning.

## Overview ℹ️

In this project, we implement two classical unsupervised learning algorithms: K-Means Clustering and Principal Component Analysis (PCA). These algorithms are widely used for clustering and dimensionality reduction tasks in machine learning. The purpose of this project is to provide a clear understanding of how these algorithms work and to demonstrate their implementation from scratch using Python.

## Implementation Details 🛠️

### Libraries Used 📚

- [Numpy](https://numpy.org/): For numerical computing.
- [Pandas](https://pandas.pydata.org/): For data manipulation and analysis.
- [Matplotlib](https://matplotlib.org/): For data visualization.

### K-Means Clustering Algorithm 🤝

- The K-Means Clustering algorithm is implemented to cluster the data into k groups.
- It initializes centroids randomly and iteratively assigns each data point to the nearest centroid.
- The algorithm converges when the centroids no longer change.

### Principal Component Analysis (PCA) Algorithm 

- The PCA algorithm is implemented to reduce the dimensionality of the data.
- It computes the covariance matrix of the centered data and then calculates the eigenvalues and eigenvectors.
- The data is transformed into the new coordinate system defined by the eigenvectors.

## Usage 

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/unsupervised-learning.git
    ```

2. Open the Jupyter Notebook file:

    ```bash
    jupyter notebook FSM_UNSUPERVISED.ipynb
    ```

3. Follow the instructions in the notebook to execute the code cells and explore the implementation.

## Files 📁

- `FSM_UNSUPERVISED.ipynb`: Jupyter Notebook containing the implementation of unsupervised learning algorithms.
- `Iris Dataset.csv`: [Iris dataset](Iris%20Dataset.csv).

## Results 📈

Eigenvalues: [1890.78098156    0.97328663]


## Contributing 🤝

Contributions are welcome! If you find any issues or have suggestions, feel free to [open an issue](https://github.com/your_username/unsupervised-learning/issues) or create a [pull request](https://github.com/your_username/unsupervised-learning/pulls).

## License 📝

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.
 
