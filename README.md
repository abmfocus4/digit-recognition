#  Digit Recognition

> ### This program identifies hand-written numbers using two learning agorithms
> - multi-class classification (regularized one-vs-all logistic regression)
> - neural networks (feed-forward propagation algorithm)

![nn_forward_prop](/nn_layers.png)

## Steps to run the application
1. clone the git repo on your local
2. install MATLAB/Octave
3. cd in the **<em>code</em>** dir
4. run one_vs_all.m to use regularized one-vs-all logistic regression or run nn.m to use neural networks with feed-forward propagation algorithm 

## Motivation
### Handwritten digit recognition is widely used around the globe across several industries for identifying postal codes, catalog bank checks etc.

## Characteristics of dataset
1. Contains 5000 training examples of hand-written digits imported from MNIST handwritten digit dataset (http://yann.lecun.com/exdb/mnist/).
2. Each individual training example is 20x20 pixel grayscale image of the digit.
3. Since MATLAB does not have a '0' index, the dataset is prepared to map it to '10'

## Accuracy
1. multi-class classification (regularized one-vs-all logistic regression) - 95.02%
2. neural networks with feed-forward propagation algorithm - 97.52%




