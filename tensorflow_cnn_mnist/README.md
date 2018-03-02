ELG5378
=====
# TensorFlow-MNIST predict (recognise handwriting)


## Installation & Setup

### Overview
This project uses the MNIST tutorials from the TensorFlow website. 
This projects consists of two scripts: 
1. tensorflow_cnn_mnist.py_ – creates a model model.ckpt file based on the tutorial.
2. predict.py- uses the model.ckpt file to predict the digit form a handwritten number in a .png file.

### Dependencies
The following Python libraries are required.

- sys - should be installed by default
- tensorflow - [TensorFlow](https://www.tensorflow.org/)
- PIL – [Pillow](http://pillow.readthedocs.org)

### Installing TensorFlow
Of course TensorFlow needs to be installed. The [TensorFlow website](https://www.tensorflow.org/versions/master/get_started/index.html) has a good manual .

### Installing Python Image Library (PIL)
The Python Image Library (PIL) is no longer available. Luckily there is a good fork called Pillow. Installing is as easy as:

```sudo pip install Pillow```

Or look at the [Pillow documentation ](http://pillow.readthedocs.org) for other installation options.

### The python scripts
The easiest way the use the scripts is to put all four scripts in the same folder. If TensorFlow is installed correctly the images to train the model are downloaded automatically. 

## Running
Running is based on the steps:

1. create the model file
2. create an image file containing a handwritten number
3. predict the integer 


