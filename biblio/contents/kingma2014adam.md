# Adam: A method for stochastic optimization

> Author: Kingma, Diederik P and Ba, Jimmy
> Year: 2014
> Main topic: ANN Optimization Technique

###### TL;DR: Paper proposes a new algorithm for Gradient Descent optimization. It basically combines momentum and RMSprop. [Paper and notes](../papers/kingma2014adam.pdf).

## Abstract

> _We introduce Adam, an algorithm for first-order gradient-based optimization of stochastic objective functions, based on adaptive estimates of lower-order moments. The method is straightforward to implement, is computationally efficient, has little memory requirements, is invariant to diagonal rescaling of the gradients, and is well suited for problems that are large in terms of data and/or parameters. The method is also appropriate for non-stationary objectives and problems with very noisy and/or sparse gradients. The hyper-parameters have intuitive interpretations and typically require little tuning. Some connections to related algorithms, on which Adam was inspired, are discussed. We also analyze the theoretical convergence properties of the algorithm and rovide a regret bound on the convergence rate that is comparable to the best known results under the online convex optimization framework. Empirical results demonstrate that Adam works well in practice and compares favorably to other stochastic optimization methods. Finally, we discuss AdaMax, a variant of Adam based on the infinity norm._

## Highlights

The paper introduces Adam, which is short for **ADA**ptive **M**oment estimation.
This is one of the most famous and used optimizers for Deep Learning today.
**_Must read_**.

## BibiTeX

```
@article{kingma2014adam,
  title={Adam: A method for stochastic optimization},
  author={Kingma, Diederik P and Ba, Jimmy},
  journal={arXiv preprint arXiv:1412.6980},
  year={2014}
}
```

[Back](../README.md)
