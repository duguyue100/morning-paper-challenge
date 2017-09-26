# EraseReLU: A Simple Way to Ease the Training of Deep Convolution Neural Networks

This paper is published at [here](https://arxiv.org/abs/1709.07634)

The paper proposed an interesting idea where one can uniformly remove ReLU
operation in a network. It removes the ReLU operation at the end of each module,
e.g. `conv-bn-relu` block.

This method can increase the classification accuracy on various benchmark
datasets. This observation matches unrolled iterative estimation.
The condition of UIE might be easier to achieve if each component in the
network is zero-mean.
