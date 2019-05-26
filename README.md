# res2net-pytorch
This is pytorch type of paper《Res2Net: A New Multi-scale Backbone Architecture》，including Res2net-50, Res2Next-29。

Experiment Dataset:CIFAR 100

TRAIN--

In terminal:$python train.py --dataset cifar100 --arch XXX.model

TABLE 4 Reproducibility results:
models                        top-1.err     Params
ResNext-29,8c×64w               19.38       34.52M
Re2sNext-29,6c×24w×4scale       19.26       23.71M
Re2sNext-29,8c×25w×4scale       18.67       32.96M
Re2sNext-29,6c×24w×6scale       18.57       36.15M

According to the original paper，reproducibility results is about 1-2% higher,welcome to contact!  
