# keras_distinguish_own_cat_from_others_model
This Keras model is designed to distinguish between your cat (in this case, Flaekli) and other cats. It uses images of cats to recognize and correctly classify Flaekli from all other cats.

## Installation

To use this model, you need to install the following dependencies:

```bash
import os
import numpy as np
from tensorflow import keras
from keras import layers, callbacks
import tensorflow as tf
from tensorflow import data as tf_data
import matplotlib.pyplot as plt
import cv2
from ultralytics import YOLO
import cv2
from google.colab.patches import cv2_imshow
```

## Authors

- [luegl](https://github.com/luegl)
