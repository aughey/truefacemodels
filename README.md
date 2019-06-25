# A collection of trueface models

# Install Order

- Install CUDA 10.1 drivers
- Install Anaconda (python 3)
- Install git
- Create sandbox directory and project directory
- Checkout this repository using git into your project directory
- Setup anaconda project
- install trueface from this project using pip
- conda install jupyter
- pip install --user mxnet-cu101
- pip install matplotlib
- pip install keras_retinanet
- pip install tensorflow_gpu

~~~~
from trueface.recognition import FaceRecognizer
from trueface.video import VideoStream
import cv2
import sys
from matplotlib.pyplot import imshow
import matplotlib.pyplot as plt
%matplotlib inline
import numpy as np
~~~~

