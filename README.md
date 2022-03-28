# oneNeuron_pypi
oneNeuron_pypi >>> This python package is a implimentation of single neuron neural network(Perceptron)

## How to use this 
### Installation of this package...

#### Try any one of them  in terminal...

```bash

pip install oneNeuron-pypi-tripathimanoj

pip install oneNeuron-pypi-tripathimanoj==0.0.1

```

```python
from oneNeuron.perceptron import Perceptron

## Get X and y and then use following code.
model=Perceptron(eta=eta,epochs=epochs)
model.fit(X,y)
```
## PERCEPTRON >>>

Perceptron(A single neuron neural network) were developed in the 1950s and 1960s by the scientist Frank Rosenblatt, inspired by earlier work by Warren McCulloch and Walter Pitts.  It is  the initial basic algorithm for supervised learning of binary classifier, i.e. a classification algorithm that makes its predictions based on a linear predictor function combining a set of weights with the feature vector.

![Perceptron Basic structure](https://www.researchgate.net/profile/Brian-Mwandau/publication/325870973/figure/fig4/AS:639531594297345@1529487622181/Biological-Neuron-versus-Artificial-Neural-Network.png)

### working of Perceptron >>>

Perceptons takes several inputs x1,x2,x3....xn and produces a single binary output.Then weights were introduced expressing importance of respective inputs to the outputs. The neuron outputs either 0 or 1 ,which is determined by the weighted sum ∑wjxj is less than or greater than threshold value(this is hyperparameter).

![Perceptron rule/working](https://static.javatpoint.com/tutorial/machine-learning/images/perceptron-in-machine-learning4.png)

Based on the given no of epochs it will try to reduce the error as close to zero by adjusting the weights in every epochs. If the error is constant(can't reduce more) or zero within a given no of epochs those will be the final best weights for each feature. And then it will try to train itself by those final weights and give prediction.

![](https://miro.medium.com/max/1400/1*uzm-62Wq3J1JF1HwTMY4mg.png)


## references
[guide for creating python package ] (https://packaging.python.org/en/latest/tutorials/packaging-projects/)

[github docs for github actions] (https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python#publishing-to-package-registries)