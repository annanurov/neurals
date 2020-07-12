# neurals
VGG16 with pytorch 


Many tahnks to @sargupta Sarthak Gupta for making the tutorial possible:
https://hackernoon.com/dl05-convolutional-neural-networks-1d3bb7fff586


Prject requires Python 3 and the following imports
import torch
import torch.nn as nn
from torch.autograd import Variable
from torchvision import models
from torchvision import transforms, utils

import numpy as np
import scipy.misc
import matplotlib.pyplot as plt
%matplotlib inline
from PIL import Image
import json
