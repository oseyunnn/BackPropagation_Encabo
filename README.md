# Backpropagation with Weight Decay

## Project Structure

- The `src` directory contains the C# source files (`.cs`).
- The `bin` directory contains the compiled executable files (`.exe`).

## Learning Summary

Throught the presented document I learned about the fundamental process by which a neural network learns. Forward propagation generates a prediction from the input data, while backpropagation calculates the error gradient used to adjust the network's weights. The learning rate determines the size of each update.

Weight decay was selected as the regularization method because it penalizes excessively large weights during training. This encourages a simpler model, reduces the risk of overfitting, and can improve the model's performance on previously unseen data.

## Cross-Entropy Extension

The cross-entropy implementation uses softmax output probabilities for the three-class classification problem. For a one-hot target vector, the derivative of the cross-entropy loss combined with softmax simplifies to the target probability minus the predicted probability. This produces a direct output error signal and avoids multiplying by the additional softmax derivative used with mean squared error.

The implementation is provided in `src/BackPropProgram for CS345 IS 1_Encabo_CrossEntropy.cs`, with its compiled executable in `bin/BackPropProgram-cross-entropy.exe`.
