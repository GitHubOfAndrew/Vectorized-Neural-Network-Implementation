# Vectorized-Neural-Network-Implementation

As the title suggests, we will be attempting to vectorize a neural network's training loop. We may end up exploring more implementations of other neural network architectures (CNN, RNN, etc.) but we only have the most simple dense, feedforward neural network for now. 

**Note:** The vectorized implementation utilizes mini-batch gradient descent (an optimization method by which our weight optimization occurs over multiple samples at a time). Stochastic gradient descent can be vectorized to some degree, but the training loop for the SGD optimization is inherently one that looks at individual samples per weight update. We may implement this in another notebook.

**Update 1: The training loop is fully vectorized for any batch size. The validation inferencing at the end of each epoch needs some more work.**

**Update 2: The training loop is batched correctly now. The validation inferencing is also done correctly, and it outputs the correct metrics as well. We will likely extend this work into the general case of multiple hidden layers.**
