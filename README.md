# Label-Smoothing-for-CrossEntropyLoss-PyTorch
add a Arg: label_smoothing for torch.nn.CrossEntropyLoss()

```python
import torch

inputs = torch.randn(3, 5, requires_grad=True)
targets = torch.empty(3, dtype=torch.long).random_(5)

from label_smothing_cross_entropy_loss import LabelSmoothCrossEntropyLoss
loss_function = LabelSmoothCrossEntropyLoss(smoothing=0.3)
loss = loss_function(inputs, targets)
```
