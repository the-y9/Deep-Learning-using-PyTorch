# Deep-Learning-using-PyTorch Notes
Workshop conducted by IIT Madras
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

### Day 3 Summary: CNNs
- **Data Handling**: Loaded FashionMNIST dataset and applied transformations for normalization; utilized `DataLoader` for batching.
- **CNN Model**: Built a custom CNN with two convolutional layers and three fully connected layers for 10-class classification.
- **Training**: Used `nn.CrossEntropyLoss()` and SGD for optimization; implemented a training loop to update parameters and track accuracy.
- **Evaluation**: Tested the model on a separate dataset and calculated accuracy.

### Day 4 Summary: RNNs

1. **RNN Introduction**: Explored RNNs with an example using `nn.RNN`, focusing on sequence length and input dimensions.
2. **Model Definition**: Created a `simplernn` class with RNN and linear layers.
3. **Training**: Implemented training with `CrossEntropyLoss` and Adam optimizer, tracking loss over epochs.
4. **Text Preprocessing**: Worked with the IMDB dataset for tokenization, vocabulary creation, and padding sequences.
5. **Final RNN Model**: Built an RNN model for text classification with embedding and output layers.
