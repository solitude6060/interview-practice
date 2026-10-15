# Day 1｜Loss、梯度、MLP 訓練

NumPy 先手寫 softmax cross-entropy，再用 PyTorch 走完一步訓練，最後接到 Dataset、DataLoader 和 val accuracy。

## 順序

1. [`01_loss_and_gradients.ipynb`](01_loss_and_gradients.ipynb)：NumPy。只改 `# TODO`。
2. [`02_examples.ipynb`](02_examples.ipynb)：PyTorch 範例。`CrossEntropyLoss`、`backward` / `step`、`class MLP`、`Dataset` / `DataLoader` / eval。
3. [`03_mlp_training.ipynb`](03_mlp_training.ipynb)：蓋住範例再做。只改 `# TODO`。

## 環境

在 repo 根目錄：

```bash
uv sync
```

Notebook 核心選這個資料夾的 `.venv`。
