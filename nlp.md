---
description: Natural Language Processing
---

# NLP

Natural Language Processing \(NLP\) is the field in which **information** is extracted from spoken or written language.

NLP is special because the meaning of a word is heavily context dependent:

* The bird is a **crane**.
*  A **crane** is used in industry to lift heavy objects.
* I have to **crane** my neck to look at him.

## Preserving the context

In images, context is also important for classifying shapes, but there the context is preserved with [convolutions ](computer-vision/convolution.md)and [pooling](computer-vision/pooling.md). With text, we cannot do this.

A possible alternative is preserving the context words for each target word:

![](.gitbook/assets/image%20%283%29.png)

This naive approach works, but is more computationally intensive. Additionally, for questions of content, a few words of context is not sufficient. In the above example if asked the question "_What_ is fun?", the model would have no way of knowing that the answer is "Deep Learning", because "fun" does not include that context.

## Recurrent Neural Networks

[Recurrent Neural Networks](https://en.wikipedia.org/wiki/Recurrent_neural_network) \(RNN's\) attempt to solve the problem of storing context by having their own output fed back into them. This can take various forms, but [LSTM's](https://en.wikipedia.org/wiki/Long_short-term_memory) are the most popular right now.

![A very simple NN that feeds the output of its middle layer to a &quot;recurrent&quot; layer](.gitbook/assets/image%20%2811%29.png)



