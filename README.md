# res2net-pytorch
This is pytorch type of paper《Res2Net: A New Multi-scale Backbone Architecture》，including Res2net-50, Res2Next-29。

Experiment Dataset:CIFAR 100

TRAIN--

In terminal:$python train.py --dataset cifar100 --arch XXX.model

TABLE 4 Reproducibility results: ResNext-29-8c×64w, top-1.err 19.38%, Params 34.52M; Re2sNext-29-6c×24w×4scale, top-1.err 19.26%, Params 23.71M; Re2sNext-29-8c×25w×4scale, top-1.err 18.67%, Params 32.96M; Re2sNext-29-6c×24w×6scale, top-1.err 18.57%, Params 36.15M 。

According to the original paper，reproducibility results is about 1-2% higher,welcome to contact!  
models	                    Params	 FLOPs	  Top-1 acc
Resnext29      8c*64w	      34.52M	 5.40G	   80.62%
Res2next29  6c*24w*4scale	  23.71M	 3.88G	   82.85%
Res2next29  8c*25w*4scale	  32.96M	 5.40G	   83.27%
Res2next29  6c*24w*6scale	  36.15M	 5.92G	   82.48%
