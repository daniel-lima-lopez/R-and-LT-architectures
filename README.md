# R-and-LT-architectures
This repository contains the code for the experiments described in the article **"On the building of efficient Fourier Convolutional Neural Networks"** authored by [Daniel Lima-López](https://scholar.google.com/citations?user=x9tSGgIAAAAJ&hl=es) and [Pilar Gómez-Gil](https://scholar.google.com/citations?user=M3yVI1oAAAAJ&hl=es). The repository incldes the TensorFlow implementation of all the architectures presented in the article.

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

Notebooks [EF-R_LT_EF_CNN.ipynb](/R_LT_EF_CNN.ipynb) and [SB-CNN](/R_LT_EF_CNN.ipynb) present examples of the R and LT-architectures of EF-CNN and SB-CNN, respectively.
