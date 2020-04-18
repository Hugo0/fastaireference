---
description: Describes how to run the fast.ai code
---

# How to run the code

Machine Learning\(ML\) is extremely computationally intense, and makes heavy use of [Parallelization](https://en.wikipedia.org/wiki/Parallel_computing). Thus, it is strongly advised to make use of a [GPU](https://en.wikipedia.org/wiki/Graphics_processing_unit) \(or a cluster of them\) when training or running ML models.

This can be done locally, if you have a sufficiently equipped machine. If your machine does not have a GPU, or if a single one is not enough for your needs, then [cloud computing](https://en.wikipedia.org/wiki/Cloud_computing) is advisable.

Multiple cloud providers exist:

### [Google Colab](https://colab.research.google.com/)

Google Colaboratory, or Colab for short, is a cloud computing environment that is free of charge. Shared access to [Tesla K80's GPU's](https://www.nvidia.com/en-gb/data-center/tesla-k80/) is more than enough for most basic ML tasks, as well as all of the fast.ai lecture code. 

The development environment of Colab is a [Jupyter Notebook](jupyter-notebook.md).

### [Kaggle Notebooks](https://www.kaggle.com/notebooks)

Similar to Google Colab, [Kaggle ](https://www.kaggle.com/)offers a cloud computing environment with free access to K80's GPU's. Development environment is also Jupyter Notebooks.

### AWS, Google Cloud, Azure & Co

Paid cloud providers. Features vary, but generally they offer higher performance and stability, at a price. Suitable for production needs.

