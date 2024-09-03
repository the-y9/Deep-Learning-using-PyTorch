# Deep-Learning-using-PyTorch
### Day 1
1. **Tensor Basics**:
   - Creation: `torch.tensor()`, `torch.ones()`, `torch.rand()`.
   - Attributes: Check dimensions (`ndim`, `shape`), data types (`dtype`).
   - Device Management: Move tensors between CPU and GPU.

2. **Operations**:
   - Element access, slicing, broadcasting.
   - Basic operations: `sum()`, `max()`, `mul()`, `matmul()`.
   - Save/Load tensors: `torch.save()`, `torch.load()`.

3. **Autograd**:
   - Compute gradients with `.backward()`.
   - Leaf vs. intermediate tensors.

4. **Activation Functions**:
   - Use `torch.relu()`, `torch.sigmoid()`, and others from `torch.nn`.

5. **Loss Functions**:
   - Implement `nn.MSELoss()`, `nn.CrossEntropyLoss()`, etc. for calculating loss.
