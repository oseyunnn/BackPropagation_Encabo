# Backpropagation Applications

## Project Structure

- The `src` directory contains the C# source files (`.cs`).
- The `bin` directory contains the compiled executable files (`.exe`).

## Learning Summary

The document introduced forward propagation, backpropagation, learning rates, and methods for measuring training error. This project contains two applications that demonstrate different backpropagation approaches.

## Applications

- **Regularized backpropagation:** Uses mean squared error with weight decay. Weight decay penalizes large weights, which helps reduce overfitting and encourages a simpler model.
- **Cross-entropy backpropagation:** Uses softmax output probabilities and cross-entropy error for the three-class classification problem. The output error signal is calculated directly from the target and predicted probabilities.

The source files are in `src`, and the compiled applications are in `bin`.
