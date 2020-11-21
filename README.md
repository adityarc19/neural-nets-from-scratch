# Neural nets from scratch!

#### This is a project where I classify images of everyday objects using a neural networks built from scratch. 
#### Dataset: Cifar10 
#### Framework: PyTorch

Here, I have written feed forward neural nets and convolutional neural nets from scratch, in order to classify objects in the CIFAR10 dataset.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

![cifar10][logo]

[logo]: https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/images/cifar10.png?raw=true

[Source](https://www.cs.toronto.edu/~kriz/cifar.html)

**1. Feed Forward Neural Network**

![ffnn][f]

[f]: https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/images/ffnn.png?raw=true

![ffnn_res][fr]

[fr]: https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/images/ffnn_results.png?raw=true

Find the complete implementation [here](https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/cifar10_feed_forward.ipynb).

**2. Convolutional Neural Network**

![cnn][c]

[c]: https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/images/cnn.png?raw=true

![cnn_res][cr]

[cr]: https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/images/cnn_results.png?raw=true

**Clearly, validation accuracy jumped from 57% to 76%, while the validation loss came down from 174% to about 90%.**

Find the complete implementation [here](https://github.com/adityarc19/neural-nets-from-scratch-using-pytorch/blob/master/cifar10_cnn.ipynb).

We could furthermore increase the accuracy and bring down the loss by using transfer learning methods. 
