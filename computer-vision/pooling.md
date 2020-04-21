# Pooling

Images contain a multitude of pixels which are expensive to process. But it is not necessary to consider ALL the information to extract information about an image. Oftentimes the relative position of shapes to each other is more important. With pooling, we can downsample \(lessen the complexity of the image\) whilst still maintaining relative positional information

### Max-pooling

The most commonly used pooling algorithm, max pooling is relatively simple:

![](../.gitbook/assets/image%20%2811%29.png)

The features of the input layer are separated into groups, and then a representative feature is chosen for each group. In max-pooling, this is the feature with the highest \(max\) number.

