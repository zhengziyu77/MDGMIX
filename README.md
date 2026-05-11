<<<<<<< HEAD
# MDGMIX
=======
# MDMIX
<h1 align="center"> MDGMIX: Boundary-Aware Subgraph Mixing for Multi-Domain Graph Pre-Training </a></h2>



## Setup Environment

- python 3.12.11
- pytorch 2.8.0+cu128
- torch_cluster 1.6.3+pt28cu128
- torch_geometric 2.6.1
- torch_scatter 2.1.2+pt28cu128
- torch_sparse 0.6.18+pt28cu128
- torch_spline_conv 1.2.2+pt28cu128
- cuda 12.8
  
## Running experiments

### For different datasets, please run the following code：

python runexp.py --dataset Pubmed --lr 0.0001 --downstreamlr 0.001 --epochs 500 --shot_num 1

python runexp.py --dataset Citeseer --lr 0.0001 --downstreamlr 0.001 --epochs 500 --shot_num 1

python runexp.py --dataset Cora  --lr 0.0001 --downstreamlr 0.001 --epochs 500 --shot_num 1



>>>>>>> eae333f (Initial commit)
