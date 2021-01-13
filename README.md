# Label-Smoothing-for-CrossEntropyLoss-PyTorch
add a Arg: label_smoothing for torch.nn.CrossEntropyLoss()

```python
from label_smothing_cross_entropy_loss import LabelSmoothCrossEntropyLoss
loss_function = LabelSmoothCrossEntropyLoss(smoothing=0.3)
loss = loss_function(inputs, targets)
```
