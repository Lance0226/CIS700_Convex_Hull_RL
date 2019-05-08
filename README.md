# Pointer Networks in Tensorflow

This is an implementation of [Pointer Networks](https://arxiv.org/abs/1506.03134) to solve the [Convex Hull](https://en.wikipedia.org/wiki/Convex_hull) problem. Stacking RNN layers is supported.

![](README/arch.png)

## Environments

* Python 2.x
* TensorFlow 1.0.1
* scipy 1.2.1

## Usage

example:

python main.py --problem_name CH_20 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

python main.py --problem_name CH_50 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

python main.py --problem_name CH_100 --train_size 12800 --val_size 1280 --n_epoch 4 --ebd_size 32 --beta  0.7

