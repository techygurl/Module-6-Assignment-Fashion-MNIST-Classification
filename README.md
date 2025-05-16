#  Fashion MNIST Classification Using Keras CNN

This project implements a **Convolutional Neural Network (CNN)** using **Keras (standalone)** in **Python** to classify grayscale images from the **Fashion MNIST** dataset.

It includes:
- A CNN with **six layers**
- Training and evaluation on Fashion MNIST
- Predictions on **two test images** (numbered and visualized)

---

## 📁 Files

- `fashion_mnist_cnn.py` – Python code to build, train, and test the CNN.
- `README.md` – This file.
- *(Optional)* `requirements.txt` – Python dependencies.

---

##  Requirements

Make sure you have **Python 3.6 or higher** installed.

### 🔧 Install Required Packages

Open a terminal and run:

import numpy as np
import matplotlib.pyplot as plt
from keras.datasets import fashion_mnist
from keras.models import Sequential
from keras.layers import Conv2D, MaxPooling2D, Flatten, Dense, Dropout
from keras.utils import to_categorical


--- 
## clone the repository
https://github.com/techygurl/Module-6-Assignment-Fashion-MNIST-Classification



## Fashion MNIST Classes
Each image is classified into one of these categories

0 - T-shirt/top
1 - Trouser
2 - Pullover
3 - Dress
4 - Coat
5 - Sandal
6 - Shirt
7 - Sneaker
8 - Bag
9 - Ankle boot

