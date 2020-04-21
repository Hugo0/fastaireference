# Convolution

If we represent an image as a two dimensional array of pixels, then convolutions can be applied to detect edges and other more complex features.

![Example greyscale image](../.gitbook/assets/image%20%2822%29.png)

The image is then transformed from an array of pixels to an array of convolutions, which are then again fed into more and more convolutional layers. This enables the learning of complex shapes that can then be used by the final fully connected layer to classify the image.

![](../.gitbook/assets/image%20%2811%29.png)

Intuitively, one can imagine the process going like this:

1. An image of a car is received
2. Features are extracted with convolutional layers
3. The resulting vector of features is then classified

   i.e. this object has four wheels, windows, a license plate and seat --&gt; it must be a car. 

### Convolutions Mathematically

In mathematical terms, in a convolution a small kernel \(usually 2x2, 3x3 or 4x4\) is applied to an input matrix \(the pixels of an image\). 

![A 3x3 kernel is applied to an 5x5 image](../.gitbook/assets/image%20%2823%29.png)

The 3x3 kernel is applied to every 3x3 square in the input image sequentially, reducing the image dimension and extracting information in the process.

