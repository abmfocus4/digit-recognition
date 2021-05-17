#  Digit Recognition

> ### This program identifies hand-written numbers using two learning agorithms
> - multi-class classification using regularized one-vs-all logistic regression
> - neural network learning algorithm using feed-forward/backward propagation

![nn_layers](/pics/nn_layers.png)

## Steps to run the application
1. clone the git repo on your local
2. install MATLAB/Octave
3. cd in the **<em>code</em>** dir
4. run one_vs_all.m to use regularized one-vs-all logistic regression or run nn.m to use neural network learning algorithm with feed-forward/backward propagation 

## Motivation
### Handwritten digit recognition is widely used around the globe across several industries for identifying postal codes, catalog bank checks etc.

## Characteristics of dataset
1. Contains 5000 training examples of hand-written digits imported from MNIST handwritten digit dataset (http://yann.lecun.com/exdb/mnist/).
2. Each individual training example is 20x20 pixel grayscale image of the digit.
3. Since MATLAB does not have a '0' index, the dataset is prepared to map it to '10'

![dataset](/pics/dataset.png)

- Number 5
![5](/pics/5.png)

- Number 7
![7](/pics/7.png)

- Number 8
![8](/pics/8.png)


## Accuracy
1. multi-class classification using regularized one-vs-all logistic regression - 95.02%
2. neural network learning algorithm with feed-forward/backward propagation - 97.52%




