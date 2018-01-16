# keras-stock-rnn
Using Keras to build popular RNN structures to predict stock prices.

## Original Blog post source:
https://github.com/lilianweng/stock-rnn Lilian provides a great blog post with code repo based on Tensorflow. It provides a lot useful background readings. Do check it out!

## Structure of the Flow
### Basic Review - Why RNN?
![alt text](RNN_Structure.jpg "A simplified version of RNN")


The network structure commonly used is "multi-layer perceptron," or densely-connected network. The densely connected neural network gives no _assumption_ of the input data. However, we'd like to model the dependence of the data (i.e., stock data). How could we design the model so the order of data input affects the output of the model? The answer is Recurrent Neural Network (RNN).

In the RNN, each neural unit not only receives data from input but also receives previous unit's input.
Special RNN network structure.
## Model Buildup

## Experiment Setup
### Data Source
### Proposed Workflow
### Data Preparation
### Model Set-up
## Conclusion
