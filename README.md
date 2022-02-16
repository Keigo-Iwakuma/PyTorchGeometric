# PyTorchGeometric

Workspace for PyG

## *Environment*
- docker image : nvcr.io/nvidia/pytorch:21.06-py3

## "Setup"

```shell
# update pip and torch
pip3 install --upgrade pip
pip3 install torch==1.10.2+cu113 torchvision==0.11.3+cu113 torchaudio==0.10.2+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html

# install pytorch_geometric
pip install torch-scatter torch-sparse torch-cluster torch-spline-conv torch-geometric -f https://data.pyg.org/whl/torch-1.10.0+cu113.html
```

for details, refer to https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html
