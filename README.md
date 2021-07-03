# TensorFlow 2.0 Tutorial

### Table of contents

1. [Introduction](#intro)
2. [Installation](#installation)
3. [Tutorial usage](#tutorial)
    - [3.1. Basic](#basic)
    - [3.2. Basic models](#basic_models)
    - [3.3. Neural networks](#neural_nets)
    - [3.4. Utilities](#utilities)
    - [3.5. Data management](#data_management)
    - [3.6. Multi-GPU Training](#multi_gpu_training)

## <a name='intro'></a> What is about TensorFlow 2.0

TensorFlow is an open-source, highly flexible, and very extensible machine learning library, maintained mainly by Google, that can be used in a wide variety of applications, from Deep Learning research to high-performance AI services. Version 2.0 of this framework brought a user-friendlier and cleaner API accompanied by higher performance. At IUST, we are creating a set tutorial to be taught in our Deep Learning courses. These tutorials include **comprehensive** and **in-depth** materials on how to use TensorFlow 2 in practice. Our goal is to provide opinionated tutorials in which we point out the best practices for each use case. Moreover, these materials are created to be used in **self-study** or **taught as a mini-course**.

In this tutorial, first, i aim to approach TensorFlow 2.0 from a practical point of view so that you can start using the framework as soon as possible. Secondly, i try to include and use a wide range of information such as TF team talks, API references, and practical experiences in the making of these materials to make it as comprehensive as possible. Thus, the user can enjoy an all-in-one package. Finally, tutorials are organized in a simple-to-complex manner that can benefit many newcomers. Moreover, the assignments that come with these tutorials make them a ready-to-use option in use in special (short) courses.

<p align="center">
  <img src="imgs/tensorflow-2.0.gif" width="500" height="300" align="middle">
</p>

## <a name='installation'></a> Installation

To install TensorFlow 2.0, run:

```js
pip install tensorflow~=2.0.0
```

Or, if you want GPU support, run:

```js
pip install tensorflow_gpu==2.0.0
```

## <a name='tutorial'></a> Tutorial usage

### <a name='basic'></a> 3.1. Basic

- [Basic operators](https://github.com/phanxuanphucnd/TensorFlow-2.0-Tutorial/blob/main/notebooks/3.1%20Basic/3.1.1%20Basic.ipynb): A simple example that cover TensorFlow 2.0 basic operations.

### <a name='basic_models'></a> 3.2. Basic models

- [Linear Regression](https://github.com/phanxuanphucnd/TensorFlow-2.0-Tutorial/blob/main/notebooks/3.2%20Basic%20models/3.2.1%20Linear%20Regression.ipynb): Implement a Linear Regression with TensorFlow 2.0.
- [Logistic Regression](https://github.com/phanxuanphucnd/TensorFlow-2.0-Tutorial/blob/main/notebooks/3.2%20Basic%20models/3.2.2%20Logistic%20Regression.ipynb): Implement a Logistic Regression with TensorFlow 2.0.
- [Word2Vec (Word Embedding)](https://github.com/phanxuanphucnd/TensorFlow-2.0-Tutorial/blob/main/notebooks/3.2%20Basic%20models/3.2.3%20Word2Vec%20(Word%20Embedding).ipynb)Build a Word Embedding Model (Word2Vec) from Wikipedia data, with TensorFlow 2.0.
- [Gradient Boosted Decision Trees (GBDT)](https://github.com/phanxuanphucnd/TensorFlow-2.0-Tutorial/blob/main/notebooks/3.2%20Basic%20models/3.2.4%20Gradient%20Boosted%20Decision%20Trees.ipynb): Implement a Gradient Boosted Decision Trees with TensorFlow 2.0+ to predict house value using Boston Housing dataset.

### <a name='neural_nets'></a> 3.3. Neural networks

- [Simple Neural Networks (CNN)](): Implementation of a simple neural network to classify MNIST digits dataset.
- [Convolutional Neural Network](): Implementation of a convolutional neural network to classify MNIST digits dataset.
- [Recurrent Neural Network (RNN)](): Build a recurrent neural network (LSTM) to classify MNIST digits dataset, using TensorFlow 2.0 'layers' and 'model' API.
- [Bi-directional Recurrent Neural Network (LSTM)](): Build a bi-directional recurrent neural network (LSTM) to classify MNIST digits dataset, using TensorFlow 2.0 'layers' and 'model' API.
- [Dynamic Recurrent Neural Network (LSTM)](): Build a recurrent neural network (LSTM) that performs dynamic calculation to classify sequences of variable length, using TensorFlow 2.0 'layers' and 'model' API.
- [Auto-Encoder](): Build an auto-encoder to encode an image to a lower dimension and re-construct it.
- [Deep Convolutional Generative Adversarial Networks (DCGAN)](): Build a Deep Convolutional Generative Adversarial Network (DCGAN) to generate images from noise.

### <a name='utilities'></a> 3.4. Utilitites

- [Save and Restore a model](): Save and Restore a model with TensorFlow 2.0.
- [Build Custom Layers & Modules](): Learn how to build your own layers / modules and integrate them into TensorFlow 2.0 Models.
- [Tensorboard](): Track and visualize neural network computation graph, metrics, weights and more using TensorFlow 2.0+ tensorboard.

### <a name='data_management'></a> 3.5. Data management

- [Load and Parse data](): Build efficient data pipeline with TensorFlow 2.0 (Numpy arrays, Images, CSV files, custom data, ...).
- [Build and Load TFRecords](): Convert data into TFRecords format, and load them with TensorFlow 2.0.
- [Image Transformation (i.e. Image Augmentation)](): Apply various image augmentation techniques with TensorFlow 2.0, to generate distorted images for training.

### <a name='multi_gpu_training'></a> 3.6. Multi-GPU training

- [Multi-GPU Training](): Train a convolutional neural network with multiple GPUs on CIFAR-10 dataset.


## Author

- Name: Phanxuan Phuc
- Email: phanxuanphucnd@gmail.com