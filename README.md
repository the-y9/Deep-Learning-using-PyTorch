# Deep-Learning-using-PyTorch Notes
Conducted by IIT Madras
### Day 1 Summary

- **Tensor Basics**: Creation (`torch.tensor()`, `torch.ones()`, `torch.rand()`), attributes (dimensions, data types), and device management (CPU/GPU).
- **Operations**: Element access, slicing, broadcasting, basic operations (`sum()`, `max()`, `mul()`, `matmul`), and saving/loading tensors (`torch.save()`, `torch.load()`).
- **Autograd**: Gradient computation (`.backward()`), leaf vs. intermediate tensors.
- **Activation Functions**: Use functions like `torch.relu()` and `torch.sigmoid()`.
- **Loss Functions**: Implement `nn.MSELoss()`, `nn.CrossEntropyLoss()`, ...

### Day 2 Summary

- **Optimization Algorithms**: SGD, Adagrad, RMSProp, Adam for model training.
- **ANN Basics**: Layers (`nn.Linear`), model creation (`nn.Module`), and sequential models (`nn.Sequential`).
- **Training Steps**: Forward pass, loss computation, backward pass, and parameter update.
- **Example**: Train a model with California housing data using PyTorch.
