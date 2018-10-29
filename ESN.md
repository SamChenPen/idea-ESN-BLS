# Machine Learning

- Learning is especially important because it does not only investigate this particular aspect of an existing intelligent system, but also mechanisms of how intelligence comes to be.
## workflow applying to machine learning

```
graph TB
A[Manually choose a parameterizable computational model ]-->B[Manually choose a training algorithm and its parameters for the model.]
B-->C[Train the model to perform a desired task by adapting its free parameter using the algorithm]
```
==The workflow requires many subjective choices and a lot of human supervisiong==
## For optimal metaparameters
- There are typically no good
meta-parameter optimization strategies that would effectively reduce the number
of iterations: often simple grid search or genetic strategies are utilized.


- for a fixed computational time the meta-parameter optimization is done at an expense of training a single much more
powerful model.

- This can be seen as a non-tractable optimization problem.

# Neural NetWork
### Neural NetWork
- FNN approximate any function 
- RNN approximate dynamical system


### Classes of RNN
 1. Hopfield networks [Hopfield, 2007, 1982], Boltzmann machines [Hinton, 2007;
Ackley et al., 1985], and the recently emerging Deep Belief Networks.  
    1. These networks are mostly trained in some unsupervised learning scheme. 
    2. The mathematical background is rooted in statistical physics.
 2. ESN
    1. The standard training mode is supervised.
    2. The mathematical background here is nonlinear dynamical systems. 
