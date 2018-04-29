# nn-grocery-shelves
Recognition of product positions on shelf images using neural networks

## Introduction

The solution is based on [Toward Retail Product Recognition on Grocery Shelves](https://pdfs.semanticscholar.org/280e/57ea3e882f82a60065fedde058ce00769c06.pdf).

![](docs/images/process.png)


## Dependencies

Solution depends on the following main libraries:
*   Tensorlfow
*   Keras
*   Tensorflow Object Detection API
*   OpenCV

Even though Windows and Mac OS are pretty acceptable for Tensorflow I recommend 
Ubuntu 16.04. This choise will save a damn amount of time. Tensorflow for CPU installation
is easy, but is not as straightforward for GPU. For detailed steps to install Tensorflow 
on Ubuntu 16.04 with an Nvidia GPU, follow this [paper](https://www.quantstart.com/articles/installing-tensorflow-on-ubuntu-1604-with-an-nvidia-gpu)

Tensorflow Object Detection API installation instructions located [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md).

Keras can be installed using pip:
``` bash
pip install keras
```


