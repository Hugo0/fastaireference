# Convolution

If we represent an image as a two dimensional array of pixels, then convolutions can be applied to detect edges and other more complex features.

![Example greyscale image](../.gitbook/assets/image%20%2810%29.png)

The image is then transformed from an array of pixels to an array of convolutions, which are then again fed into more and more convolutional layers. This enables the learning of complex shapes that can then be used by the final fully connected layer to classify the image.

![](../.gitbook/assets/image%20%283%29.png)

Intuitively, one can imagine the process going like this:

1. An image of a car is received
2. Features are extracted with convolutional layers
3. The resulting vector of features is then classified

   i.e. this object has four wheels, windows, a license plate and seat --&gt; it must be a car. 

### Convolutions Mathematically

In mathematical terms, a convolution is a small matrix \(usually 2x2, 3x3 or 4x4\) that is applied \(

