# Neural Network from Scratch

A deep learning implementation from first principles using NumPy.

## Features
- Dense layers with various activation functions
- Backpropagation algorithm
- Optimisation methods (SGD, Adam)
- Loss functions (MSE, Cross-entropy)

## Usage
```python
from neural_net import NeuralNetwork
nn = NeuralNetwork([784, 128, 64, 10])
nn.fit(X_train, y_train, epochs=100)
```
