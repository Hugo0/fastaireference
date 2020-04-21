# Computer Vision

Computer Vision \(CV\) is the field of Machine Learning in which visual data is processed \(images, videos\) and labeled. 

![Classifying dog breeds is CV](../.gitbook/assets/image%20%289%29.png)

## Architecture

Models that attempt to solve CV problems usually present the following architecture:

![Typical CV model architecture](../.gitbook/assets/image%20%288%29.png)

A series of [convolutions ](convolution.md)and [poolings ](pooling.md)are done one the input image to detect features, edges, shapes and to reduce the dimensionality. This greatly simplified object is then fed into a [fully connected layer](../tabular-data/fully-connected-layer.md) that attempts to classify it.

