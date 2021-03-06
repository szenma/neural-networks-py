# Neural Networks Fundamentals in Python

This repository covers code implementations of Neural Networks Fundamentals in Python online course

Course Link: https://www.udemy.com/course/neural-networks-fundamentals-in-python/?referralCode=AC5B6B5834F9ABB4C3FD **(90% OFF over the regular price)**

This project includes core neural networks implementation with python (3.5). Also, no deep learning framework is consumed such as TensorFlow or Theano.

You can run either NN.py or Vectorization.py. First one runs based on for loops whereas second one runs based on matrices and tensors. BTW, vectorized one speeds performance up radically.

# Configuration

Load historical data in the instances variable in the main file. For instance, the following variable states Exclusive OR (XOR) dataset. Last item of an instance states results whereas other items state input features.

```python
#x1, x2, result
instances = [
      [0, 0, 0]
      , [0, 1, 1]
      , [1, 0, 1]
      , [1, 1, 0]
   ] 
```

In other words, 4th item of instances, [1, 1, 0], means x1 = 1, x2 = 1 and result = 0

Moreover, you should tune the following hyper-parameters for different datasets.

```python
dump = True #print messages in the console

epoch = 10000 #learning time

activation_function = 'sigmoid'

learning_rate = 0.1

applyAdaptiveLearning = False

momentum = 0
```

# Support

There are many ways to support a project - starring the GitHub repos is one.

# License

This repository is licensed under the MIT License - see [`LICENSE`](https://github.com/serengil/neural-networks-py/blob/master/LICENSE) for more details.
