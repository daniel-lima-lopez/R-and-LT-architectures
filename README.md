# R-and-LT-architectures

**Submission ID:** 9912

**Authors:** 
 - Daniel Lima López
 - Pilar Gómez Gil

**Affiliations:** Daniel Lima López was with the National Institute of Astrophysics, Optics and Electronics during the development of this work; Pilar Gómez Gil is with the National Institute of Astrophysics, Optics and Electronics.

This repository contains the code for the experiments described in the article **"On the building of efficient Fourier Convolutional Neural Networks"** authored by [Daniel Lima-López](https://scholar.google.com/citations?user=x9tSGgIAAAAJ&hl=es) and [Pilar Gómez-Gil](https://scholar.google.com/citations?user=M3yVI1oAAAAJ&hl=es). The repository incldes the TensorFlow implementation of all the architectures presented in the article.

## Included Scripts
This repository includes the scripts with the implementation of all the architectures presented in this article along with an example run on each notebook.

| SCRIPT | DESCRIPTION |
|--------|-------------|
| [requierements.txt](requierements.txt) | This file includes the versions of each python library used on the scripts |
| [R_LT_EF_CNN.ipynb](R_LT_EF_CNN.ipynb) | This notebook contains the definition of all tensorflo clases used to implement each layer in the EF-CNN architectures. Moreover, it also includes the definition of each architecture and an example run. |
| [R_LT_SB_CNN.ipynb](R_LT_SB_CNN.ipynb) | This notebook contains the definition of all tensorflo clases used to implement each layer in the SB-CNN architectures. Moreover, it also includes the definition of each architecture and an example run. |

## Data Availability
The datasets used in this article are available on the TensorFlow library. The image processing procedures to work with the frequency representation are included on each notebook.

| DATASET | SOURCE | LIBRARY REFERENCE |
|---------|--------|---------|
| MNIST | [https://www.tensorflow.org/api_docs/python/tf/keras/datasets/mnist](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/mnist) | from tensorflow.keras.datasets import mnist |
| Fashion-MNIST | [https://www.tensorflow.org/api_docs/python/tf/keras/datasets/fashion_mnist](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/fashion_mnist) | from tensorflow.keras.datasets import fashion_mnist |
| CIFAR-10 | [https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar10](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar10) | from tensorflow.keras.datasets import cifar10 |
| CIFAR-100 | [https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar100](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar100) | from tensorflow.keras.datasets import cifar100 |

## Installation
The implementation was carried out using Keras with Python version 3.9.19 (newer versions does not allow GPU usage on Windows).

As for the installation, the project should be cloned as follows:
```bash
git clone git@github.com:daniel-lima-lopez/R-and-LT-architectures.git
```

Then, you may want to install the requiered libraries using the [requirements.txt](/requirements.txt) file:
```bash
pip install -r requirements.txt
```

Afterwards, you can try the code in the downloaded folder:
```bash
cd R-and-LT-architectures
```

## Usage
The notebooks [R_LT_EF_CNN.ipynb](/R_LT_EF_CNN.ipynb) and [R_LT_SB_CNN](/R_LT_SB_CNN.ipynb) provide examples of the R and LT architectures for EF-CNN and SB-CNN, respectively.

To run the experiments, only the first cell needs to be executed initially, as it loads all required libraries and defines the necessary classes and auxiliary functions. After that, you can selectively run the cells corresponding to the section of interest, where each section represents a specific architecture and its associated experiments.


