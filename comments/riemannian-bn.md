# Riemannian approach to batch normalization

This paper is published at [here](https://arxiv.org/abs/1709.09603)

This paper gives batch normalization (BN) a Riemannian explanation.
Two training algorithms for momentum SGD and Adam are proposed.
The formulation of BN is not changed from the conventional BN.
The network will gain advantage in training if it adapts the training algorithms.

From result, although it constantly has higher performance than conventional
network, but the training cost is higher. As paper indicated, between
2.5x-3x. Note that this burden is luckily linear. So better hardware, less
training time.

__Note:__ The mathematical proof is too hard for me, I need to get some training
in Riemannian mathematics.
