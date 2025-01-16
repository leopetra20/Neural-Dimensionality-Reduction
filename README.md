# Neural-Dimensionality-Reduction
We are already familiar with two common techniques for dimensionality reduction: PCA and t-SNE. But what about neural networks? In this project, we implement a small autoencoder and test it on two well-known datasets

## Overview
This project explores the use of **neural networks** for dimensionality reduction, focusing on implementing and testing a small **autoencoder**. While traditional techniques like **PCA** (Principal Component Analysis) and **t-SNE** (t-Distributed Stochastic Neighbor Embedding) are widely used, neural networks provide a flexible and powerful alternative that supports non-linear transformations, out-of-sample projections, and inverse mapping.

The autoencoder is tested on two well-known datasets:
- **MNIST**: Handwritten digits.
- **Fashion MNIST**: Clothing and accessory images.

## Features
- Implementation of a small **autoencoder** for dimensionality reduction.
- Testing and evaluation on **MNIST** and **Fashion MNIST** datasets.
- Comparison of the 2D and 3D embeddings with traditional dimensionality reduction techniques.
- Use of **reconstruction loss** and **pseudo-label classification** to improve cluster separation.

## Technologies Used
- **Python**: Programming language for implementation.
- **PyTorch**: Deep learning framework for building and training the autoencoder.
- **Matplotlib**: Visualization library for embedding visualizations.
- **Pandas**: Data manipulation library for organizing and handling embeddings.

## Getting Started

* If you are running **locally**:
   1. Clone the repository.
   2. Create a virtual environment.
   3. Install in the venv all the packages listed in `requirements.txt`.
   4. Open the notebook `dim_reduction.ipynb`.
   5. Run the notebook.


* If you are using **Colab**(reccomended):
   1. Download the notebook `dim_reduction.ipynb`.
   2. Open the notebook in your Google Colab.
   3. Run the notebook.
