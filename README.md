# Hand-written-digit-recognition-using-CNN
Model accuracy is more than 99 percent using this model with CNN
Handwritten Digit Recognition using Convolutional Neural Networks in Python with Keras
<h1>MNIST dataset:</h1>

MNIST is a collection of handwritten digits from 0-9. Image of size 28 X 28

<h2>Code Requirements</h2>

python 3.x with following modules installed

   1.numpy
   2.seaborn
   3.tensorflow
   3.keras
   4.opencv2

<h3>Description :</h3>

This is a 5 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I choosed to build it with keras API (Tensorflow backend) which is very intuitive.

It achieved 99.51% of accuracy with this CNN trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation.
