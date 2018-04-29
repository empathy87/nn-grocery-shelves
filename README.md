# nn-grocery-shelves
Recognition of product positions on shelf images using neural networks

![](docs/images/planogram.jpg)

## Introduction

### What is a planogram?
- Visual description of the retail products' placement on shelves.

The solution is based on [Toward Retail Product Recognition on Grocery Shelves](https://pdfs.semanticscholar.org/280e/57ea3e882f82a60065fedde058ce00769c06.pdf).

Few years ago a planogram reconstruction from shelves photos was not an easy task in both products detection and brands recognition. The work mentioned above
proposes the following combination of algorithms.

![](docs/images/process.png)

It was hard to implement, hard to maintain, hard to expand to include new brands and products.

Nowdays neural networks change the way of thinking of such tasks. This work shows that all these algorithms could be easily replaced
by only 2 neural networks with increase of recognition quality without losing performance.

## Steps

All steps are implemented as jupyter notebooks and could be read without execution:
*   [Step 1 - Initial Data Preparation](https://github.com/empathy87/nn-grocery-shelves/blob/master/Step%201%20-%20Initial%20Data%20Preparation.ipynb)
*   [Step 2 - Brands Recognition with CNN]()
*   [Step 3 - Training SSD for Products Detection]()
*   [Step 4 - Implementing Products Detection]()

## Dependencies

Solution depends on the following main libraries:
*   Tensorlfow
*   Keras
*   Tensorflow Object Detection API
*   OpenCV

Even though Windows and Mac OS are pretty acceptable for Tensorflow I recommend 
Ubuntu 16.04. It will save you a huge amount of time. Tensorflow for CPU installation
is easy, but is not as straightforward for GPU. For detailed steps to install Tensorflow 
on Ubuntu 16.04 with an Nvidia GPU, follow this [paper](https://www.quantstart.com/articles/installing-tensorflow-on-ubuntu-1604-with-an-nvidia-gpu)

Tensorflow Object Detection API installation instructions located [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/installation.md).

Keras can be installed using pip:
``` bash
pip install keras
```


