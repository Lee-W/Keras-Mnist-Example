# Learn Deep Learning in One Day - Keras Demo

This is my implementation of demo code in [一天搞懂深度學習](http://www.slideshare.net/tw_dsconf/ss-62245351).  

## Description
In this demo, the nerual network is trained using mnist data to recognize numbers.

The initial model uses MSE as cost function and sigmoid as activation function which would get a bad performance when only 10,000 data was used.

The following methods (taught in the [一天搞懂深度學習](http://www.slideshare.net/tw_dsconf/ss-62245351) lesson) are used to enhance accuracy and avoid overfitting.

- Enhance Accuracy
	- Cross Entropy
	- ReLU
	- Adam

- Avoid Overfitting
	- Dropout

## Usage
You can simply open the Demo.ipynb on [GitHub](https://github.com/Lee-W/Keras-Mnist-Example/blob/master/Demo.ipynb) or through [jupyte nbviewer](http://nbviewer.jupyter.org/github/Lee-W/Keras-Mnist-Example/blob/master/Demo.ipynb)(recommended).

This ipython notebook is also organized as slides that can be used with default jupyter nbcoverter or [RISE](https://github.com/damianavila/RISE).

# AUTHORS
[Lee-W](https://github.com/Lee-W/)



