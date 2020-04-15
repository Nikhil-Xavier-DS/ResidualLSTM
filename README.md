# ResidualLSTM

The structure of the LSTM allows it to learn on problems with long term dependencies relatively easily. The "long term" memory is stored in a vector of memory cells c. Although many LSTM architectures differ in their connectivity structure and activation functions, all LSTM architectures have memory cells suitable for storing information for long periods of time. Here we implement the ResNet inspired Residual-LSTM.

SELU is chosen as activation function of easier module due to its inherent parameters, 'scale' and 'alpha'. The values of `alpha` and `scale` are chosen so that the mean and variance of the inputs are preserved between two consecutive layers.
