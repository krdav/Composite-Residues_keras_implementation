# Composite Residues keras implementation

Implementation of the "Composite Residues" neural network architecture used in [Toward machine-guided design of proteins](https://www.biorxiv.org/content/early/2018/06/02/337154.full.pdf).
The article does show a diagram of the network architecture but provides no implementation.
Here I implement it in keras.

To make the parameter count match I figured that they didn't use bias nodes on the five node dense layer but did use a bias node for the output layer.
This may be incorrect, but honestly I don't know why they would not use these bias nodes in the first place....



### Network architecture diagram from article:
![alt text](https://github.com/krdav/Composite-Residues_keras_implementation/blob/master/article_diagram.png "article diagram")


### Network architecture diagram of this implementation:
![alt text](https://github.com/krdav/Composite-Residues_keras_implementation/blob/master/keras_model.png "keras diagram")

![alt text](https://github.com/krdav/Composite-Residues_keras_implementation/blob/master/keras_model_summary.png "keras model summary")



