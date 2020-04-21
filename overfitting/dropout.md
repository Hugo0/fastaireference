---
description: Crippling your model to make it better
---

# Dropout

Dropout attempts to deal with overfitting by randomly disabling small parts of the model during training runs.

![A model before and after dropout is applied to it](../.gitbook/assets/image%20%287%29.png)

An overfitting model has a very large number of weights and parameters compared to its training dataset. Practically, this means that it can "remember" individual examples by effectively creating extremely weighted neural pathways. However, we don't want the model to remember, we want it to _think._ 

By randomly disabling nodes and paths we force the model to not overly rely on individual neural pathways, and thus force the need to create more complex associations.

