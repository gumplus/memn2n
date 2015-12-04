# memn2n
WIP implementation of [End-To-End Memory Networks](http://arxiv.org/abs/1503.08895) with sklearn-like interface using Tensorflow.

It's not 100% ready yet!

Currently doing a bunch of experiments but initial results look nice.

## TODO

* Run a joint model; train on all 20 tasks and then test
* Support multi-word answers
* Linear start - don't do softmax on the probabilities at first
* Adjacent sharing
* Temporal Encoding
* Gradient noise as described [here](http://arxiv.org/abs/1511.06807).
