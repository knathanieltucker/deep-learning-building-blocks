# deep learning building blocks

Welcome to deep learning building blocks. This is an intermediate tutorial on deep learning that focuses on how to design neural networks for various data types. 

Because this is intermediate, we are not going to be introducing what a convolution is or backpropagation. We assume that you either already know about them, or more care about solving problems than understanding theory. 

This tutorial progresses by introducing different types of data (often data that is hard for traditional ML to take advantage of). We then present neural network designs that typically work well with that type of data. If you have am exotic type of data that you don't see listed here, let me know and I'd be happy to cover it!

On a final note, because I feel that there are already pretty decent tutorials on working with image and text data out there, I'll start this series by talking about good old fashioned tabular data

The order in which these tutorials go is as follows:

1. [Tabular Data]()
2. [Categorical Data]()
3. [Variable Length Features]()
4. [Ordered Variable Length Features]()
5. [Real World Example]()

## Installing What You'll Need

The first step to get running with these tutorials is to install virtualenv. Fortunately there is a [great tutorial](https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv) on hitchhiker's guide to python. Please follow the steps in the guide.

Once you have installed virtualenv let's make an enviornment with the following command:

`virtualenv env`

You will want to be using python 3.6, so please make sure your enviornment is running it.

Again the tutorial is a great resource on showing you how to do this on both windows and mac:

[Activate your env](https://docs.python-guide.org/dev/virtualenvs/#lower-level-virtualenv)

The next step is that we will need to install all the requirements:

`pip install -r requirements.txt`

Finally the last step is to run an ipython notebook from within the env and then we are ready to go:

`ipython notebook`

