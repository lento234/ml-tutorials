<div align="center">

# ML Tutorials

**A collection of machine learning tutorials with PyTorch / PyTorch-lightning**

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/index.ipynb)
[![CC BY 4.0][cc-by-shield]][cc-by]
<a href="https://pytorch.org/">
    <img src="https://raw.githubusercontent.com/pytorch/pytorch/master/docs/source/_static/img/pytorch-logo-dark.png" alt="PyTorch" height="15"/>
</a>
<a href="https://www.pytorchlightning.ai">
    <img src="https://raw.githubusercontent.com/PyTorchLightning/pytorch-lightning/master/docs/source/_images/logos/lightning_logo-name.png" alt="PyTorch-lightning" height="20"/>
</a>

</div>

## Table of Contents

### 1. Basics

- [Linear regression](01-basics/01-linear_regression.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/01-basics/01-linear_regression.ipynb) 
- [Image classification: CIFAR10](01-basics/02-CIFAR10.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/01-basics/02-CIFAR10.ipynb)
- [Image classification: CIFAR10 (**pytorch-lightning**)](01-basics/03-CIFAR10_pl.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/01-basics/03-CIFAR10_pl.ipynb)

### 2. Advanced

- [Image segmentation: PASCAL VOC dataset](02-advanced/image_segmentation.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/02-advanced/image_segmentation.ipynb)
- [Basic GAN](02-advanced/basic_gan.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/02-advanced/basic_gan.ipynb)
- [TPU Training: MNIST](02-advanced/tpu_training_mnist.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lento234/ml-tutorials/blob/main/02-advanced/tpu_training_mnist.ipynb)

## Local installation

1. Download the github project locally:

    ```bash
    $ git clone https://github.com/lento234/ml-tutorials.git
    $ cd ml-tutorials
    ```
    
2. Setup the [python environment](environment.yml) using [conda](https://docs.conda.io/en/latest/miniconda.html):

    ```bash
    $ conda env create -f environment.yml
    $ conda activate ml-tutorials
    ```

3. Start [jupyterlab](https://jupyterlab.readthedocs.io/en/stable/) and run the notebooks:

    ```bash
    $ jupyter lab
    ```

## References

### Web 

1. [PyTorch](https://pytorch.org): PyTorch is an open source machine learning library with functionality similar to NumPy with strong acceleration via graphics processing units (GPU).
2. [PyTorch Lightning](https://www.pytorchlightning.ai): PyTorch Lightning is an open-source Python library that provides a high-level interface for PyTorch.
3. [Awesome-pytorch-list](https://github.com/bharathgs/Awesome-pytorch-list): A collection of PyTorch references, literature, tutorials.
4. [the-incredible-pytorch](https://github.com/ritchieng/the-incredible-pytorch): A curated list of tutorials, projects, libraries, videos, papers, books and anything related to the incredible PyTorch.
5. [PyTorch on Google TPU](https://github.com/pytorch/xla): Github examples for PyTorch on Google TPU.
6. [PyTorch for Numpy users](https://github.com/wkentaro/pytorch-for-numpy-users): PyTorch and NumPy API comparison.
7. [PyTorch Cheat Sheet](https://pytorch.org/tutorials/beginner/ptcheat.html)

### Books

1. [Deep learning with PyTorch](https://www.manning.com/books/deep-learning-with-pytorch)

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-brightgreen.svg
