# MNIST
Clasificacion del conjunto de datos MNIST con MLP y CNN utilizando Keras

--------------------------------------------------

**Keras-team-mnist_cnn.ipynb**
Conv2D(32@3x3)-Conv2D(64@3x3)-MaxPooling2D(2x2)-Dropout(0.25)-Flatten-Dense(128)-Dropout(0.5)-Dense(num_classes)
CNN del ejemplo de keras-team https://github.com/keras-team/keras/tree/master/examples

**Keras-team-mnist_mlp.ipynb**
Dense(512)-Dropout(0.2)-Dense(512)-Dropout(0.2)-Dense(num_classes)
MLP del ejemplo de keras-team https://github.com/keras-team/keras/tree/master/examples

**MnistCNN.ipynb**
Conv2D(32@3x3)-MaxPool2D(2x2)-Conv2D(64@3x3)-MaxPool2D(2x2)-Flatten-Dense(64)-Dropout(0.2)-Dense(num_classes)
Este es el bueno

**MnistCNNGoogle.ipynb**
Conv2D(32@3x3)-MaxPool2D(2x2)-Conv2D(64@3x3)-MaxPool2D(2x2)-Conv2D(64@3x3)-Flatten-Dense(64)-Dense(num_classes)
ejemplo de la pagina de TensorFlow

**MnistCNNSinNormal.ipynb**
Conv2D(32@3x3)-MaxPool2D(2x2)-Conv2D(64@3x3)-MaxPool2D(2x2)-Conv2D(64@3x3)-Flatten-Dense(64)-Dense(num_classes)
(el de google sin normalizar)

**MnistMLP.ipynb**
Flatten-Dense(512)-Dense(num_classes)

**MnistMLPGoogle.ipynb**
Flatten-Dense(512)-Dropout(0.2)-Dense(num_classes)
ejemplo de la pagina de TensorFlow

**MnistMLPSinNormal.ipynb**
Flatten-Dense(512)-Dropout(0.2)-Dense(num_classes)
(el de google sin normalizar)