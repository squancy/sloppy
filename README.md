# sloppy
A basic neural network for recognizing handwritten numbers.

## General
Sloppy, when trained with 60,000 and tested on 10.000 images, is able to recognize handwritten numbers by humans with an accuracy of ~96%.<br>
This correctness may not be the same when using different training or testing data.<br>

It is a simple, 3 layer neural network with 784 input and 10 output nodes. The number of hidden nodes may vary but use around 400-600 nodes for the best performance. Sigmoid is used as an activation function.<br>

Sloppy can also recognize your handwriting but make sure you convert the image to 28x28 PNG and with a high contrast ratio between the backgroun and foreground. This image will later be converted to a 1D array of 784 greyscale pixels.<br>

A sample of training and testing data can be found in <i>data</i>. <br>
If you want to train with more numbers download the <a href="http://www.pjreddie.com/media/files/mnist_train.csv">training data</a> with 60,000 sets and the <a href="http://www.pjreddie.com/media/files/mnist_test.csv">testing data</a> with 10,000 sets.<br>

## Contribute
If you have any questions or suggestions drop me with an email at <a href="mailto:mark@pearscom.com">mark@pearscom.com</a>.
