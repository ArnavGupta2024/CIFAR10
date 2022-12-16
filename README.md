## CIFAR10

Canadian Institute for Advanced Research, 10 classes

Various CNN architectures applied on the dataset

### How to import - 
import tensorflow as tf

from tensorflow import keras

cifar10 = tf.keras.datasets.cifar10

(x_train,y_train),(x_test,y_test) = cifar10.load_data()
