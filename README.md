# Backpropagation with Weight Decay

## Project Structure

- The `src` directory contains the C# source files (`.cs`).
- The `bin` directory contains the compiled executable (`.exe`).

## Learning Summary

The slides presented the fundamental process by which a neural network learns. Forward propagation generates a prediction from the input data, while backpropagation calculates the error gradient used to adjust the network's weights. The learning rate determines the size of each update.

Weight decay was selected as the regularization method because it penalizes excessively large weights during training. This encourages a simpler model, reduces the risk of overfitting, and can improve the model's performance on previously unseen data.
