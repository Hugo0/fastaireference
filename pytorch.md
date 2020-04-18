# PyTorch

[PyTorch ](https://pytorch.org/)is one of the two main frameworks in which Neural Networks are built, the other one being [Tensorflow](https://www.tensorflow.org/).

The fast.ai course uses PyTorch.

### PyTorch vs Tensorflow

| PyTorch | Tensorflow |
| :--- | :--- |
| Open Source | Open Source |
| Backed by Facebook | Backed by Google |
| slightly less popular, but growing quickly | slightly more popular, but growing less quick |
| Dynamic Graph | Static Graph |

The main difference between PyTorch and Tensorflow is that PyTorch builds and evaluates a [dynamic graph](https://medium.com/intuitionmachine/pytorch-dynamic-computational-graphs-and-modular-deep-learning-7e7f89f18d1), whilst Tensorflow builds a static graph. A dynamic graph is especially useful in Recurrent Neural Networks \(RNN's\).

There are some other additional cosmetic differences \(naming conventions and such are generally regarded to be better in PyTorch\), but the performance of both frameworks is nearly identical; they both use [Numpy](https://numpy.org/) to perform the underlying calculations.

