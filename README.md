# Pointer Networks with Reinforcement Learning

This is an implementation of [Pointer Networks](https://arxiv.org/abs/1506.03134) to solve the [Convex Hull](https://en.wikipedia.org/wiki/Convex_hull) problem. 

![](README/arch.png)

## Environments

Name                Version                   Install          

IPython             5.8.0                     pip install IPython

numpy               1.16.3                    pip install numpy

tqdm                4.31.1                    pip install tqdm

matplotlib          2.2.4                     pip install matplotlib

torch               1.1.0                     pip install torch

scipy               1.2.1                     pip install scipy

libomp              8.0.0

## Usage

example:

python main.py --problem_name CH_20 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

python main.py --problem_name CH_50 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

python main.py --problem_name CH_100 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

