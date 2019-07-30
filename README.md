# Assignment-12

Used **ResNet-18**, pytorch on cifar10 dataset. 
Applied different Learning Rate Schedulers:

1. Learning rate change on Platue.
2. **Cyclical LR**, with small step size(2000).
3. **Cyclical LR**, with large step size(10000 iterations = 25 epochs).

In the second case, it was possible to train the model to get **90% accuracy on validation dataset in 410 sec or 6.8 Min.**

The aim eventually is to attain 94% which is human benchmark on cifar10, in under **2 min**.
