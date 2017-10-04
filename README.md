# pytorchnet

This is a framework built on top of PyTorch and use Visdom for visualization.



```{r, engine='bash', sample run}
python main.py --manual-seed 0 --dataset-train cifar10 --dataset-test cifar10 --dataroot ../ --nthreads 20 --optim-method SGD --batch-size 4 --nclasses 10 --nchannels 3 --resolution-high 32 --resolution-wide 32 --nepochs 100 --learning-rate 1e-3 --momentum 0.9 --weight-decay 0.0 --port 8097
```
