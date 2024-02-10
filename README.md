# pyTorch_Learning
  PyTorch is an optimized tensor library for deep learning using GPUs and CPUs.
# Tensor Manipulation Operations:
# Reshaping:
Reshaping involves changing the arrangement of elements in a tensor to a new shape without altering the data.
Useful for preparing data for specific operations or models. For example, converting a 1D tensor to a 2D tensor.
# Stacking:
Stacking combines tensors along a new axis.
Useful for joining tensors along a new dimension, creating higher-dimensional tensors. For example, stacking multiple vectors to form a matrix.
# Squeezing:
Squeezing removes dimensions with size 1 from the tensor.
Reduces the rank of the tensor. Helpful when dealing with singleton dimensions, making the tensor more compact.
# Unsqueezing:
Unsqueezing adds dimensions with size 1 to the tensor.
Increases the rank of the tensor. Useful when an additional dimension is needed for broadcasting or compatibility with certain operations.
# Permute:
Permute changes the order of dimensions in a tensor.
Reorders dimensions, providing flexibility in how data is organized. Useful for preparing data for specific models or operations.
