# neurals
There is a valid question coming from medical researchers: 
 - How to use AI in order to assess the difficulty of diagnosis.

This project is an example of how to address a larger problem: classification

The aims is to compare the difficulty of classification against outcomes of a neural network (NN).
An example of a NN used here is VGG16.

Technically, VGG16, as many other NNs, computes a vector with K values,  enumerating the chance of the sample being in a particular class.
K is the number of predefined classes

The highest valuie (winner) is selected as the "output" of the network.
The second, third, etc values are usually neglected.


Intiution is:  as such values grow closer and closer to the winner, human scepticism should also grow: 
 - Is the winner actually the final, strongest, concrete classification?
 
 The analysis of the runner-up classes may be used to reflect the difficulty of classification, and as a subproblem, difficulty of diagnosis.

The project impleemnts VGG16 with pytorch.


Many tahnks to @sargupta Sarthak Gupta for making the tutorial possible:
https://hackernoon.com/dl05-convolutional-neural-networks-1d3bb7fff586


Requirements: Python 3 and the following imports

torch, torch.nn, torch.autograd.Variable, torchvision.models, torchvision.transforms, torchvision.utils, numpy, scipy.misc, PIL.Image, json, matplotlib.pyplot

