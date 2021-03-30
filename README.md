# simple_neural_networks
simple_neural_networks


## Pre-requisites

The code was tested with Python 3.6.8 (Anaconda distribution). It requires the following packages (use `pip install` in your virtual environment):

- dataclasses (this should not be required with Python 3.7 and up)
- pickleshare
- numpy
- Pillow

## Notebooks

There are two notebooks in this repository:

- **neural_network.ipynb** -- implements the network from **Chapters [1](http://neuralnetworksanddeeplearning.com/chap1.html) and [2](http://neuralnetworksanddeeplearning.com/chap2.html)**

- **one-fell-swoop.ipynb** -- implements the same network, but with the fully matrix-based approach (there's no looping over the mini-batch). This was given as a [problem](http://neuralnetworksanddeeplearning.com/chap2.html#problem_269962) in **Chapter 2**.

However, I only saw about 10-20% performance increase with the fully matrix-based approach, not 100% as Michael Nielsen stated in the book. So if you find a problem with my implementation, make a pull request!

## Images

There are two sets of images, one is the canonical MNIST digits in **mnist.pkl.gz**, and the other is in the **non-MNIST-digits** directory. 

The latter ones are my own handwriting scanned and scaled to 28x28 pixel size. They are used for "real-life" tests in addition to the validation set from MNIST.
