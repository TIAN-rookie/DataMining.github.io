# OGBN-arxiv Node Prediction by GCN-res and GAT-res
This is an improvement of baesline on the ogbn-arxiv dataset.
## Model
![image](https://github.com/TIAN-rookie/DataMining.github.io/blob/main/IMG.jpg)
## Experiment Setup：
Hyperparameter:
```bash
dropout = 0.5
runs = 10
epochs = 500
alpha = 0.2
beta = 0.7
```
### GCN-res
Hyperparameter:
```bash
num_layers = 8
hidden_dim = 128
```
### GAT-res
```bash
num_layers = 3
hidden_dim = 256
```
## Results

| Model	     | Test Accuracy	     | Valid Accuracy	   |
| ---------- | :-----------:  | :-----------: |
| GCN-res    | 73.89 ± 0.17   | 73.63 ± 0.19  |
| GAT-res    | 73.53 ± 0.19   | 73.11 ± 0.31 |
