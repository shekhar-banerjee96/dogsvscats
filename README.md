# Dogs Vs Cats Classifier

The dataset imported from Kaggle https://www.kaggle.com/c/dogs-vs-cats

Its  properties are :

1. 20000 training images - 10000 for for each class of Cat and Dog
2. 5000 test images


* [Cnn_Classification_project.ipynb](https://github.com/shekhar-banerjee96/dogsvscats/blob/master/Cnn_Classification_project.ipynb)
    * Imports this dataset in Colab and trains a classfier made from scratch.
    * Accuracy of the trained classfier is 84%.

* [transfer_learning_data_augmentation.ipynb](https://github.com/shekhar-banerjee96/dogsvscats/blob/master/transfer_learning_data_augmentation.ipynb)
    * VGG 16 model is imported from Keras and we customize it to for this task.
    * We re-purpose the Dense layers and Convolutional Layers.
    * We get an accuracy of 94%.


