# Pointer Networks with Reinforcement Learning

This is an implementation of [Pointer Networks](https://arxiv.org/abs/1506.03134) to solve the [Convex Hull](https://en.wikipedia.org/wiki/Convex_hull) problem. 

![](README/arch.png)

## Environments

IPython 5.8.0

numpy 1.16.3

tqdm 4.31.1

matplotlib 2.2.4

torch 1.1.0

scipy 1.2.1

pillow 6.0.0

libomp 8.0.0

pip3 install IPython

pip3 install numpy

pip3 install tqdm

pip3 install matplotlib

pip3 install torch

pip3 install scipy

pip3 install pillow

## Usage

example:

python3 main.py --problem_name CH_20 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

python3 main.py --problem_name CH_50 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

python3 main.py --problem_name CH_100 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

