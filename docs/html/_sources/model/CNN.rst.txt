CNN
=====================================
CNN based model and training for heartrate predictions

.. toctree::
   :maxdepth: 2
   :caption: Contents:

This part is about using CNN model to train and do regression for Heartrate and classificaiton for Activity
by using the same sort of training data.

- Codes folder in "/deepCNN/"

- How to run
    - GPU environment

    For GPU version more layers has been added to increase model capacity, we can select to train HR or ACT based on the same data

    .. code-block:: python

       python PPG_training_HR_ACT_GPU.py

    - CPU environment

    For CPU version less layers are used to reduce training time

    .. code-block:: python

       python PPG_training_HR.py


- GPU Train Activity logs

(4603, 1024, 4)
unique classes size 9
cuda:0
total GPU: 4
train size: 3222, valid size 1381, lr: 0.00100, Adam, beta1: 0.900, beta2: 0.999, step_size: 5, gamma: 0.950

Epoch [0/99] train loss: 0.0376 acc: 31.5022% valid loss: 0.0228 acc: 42.0710% Time: 9s train corr: 1015  valid corr: 581
Best val Acc: 42.070963

Epoch [1/99] train loss: 0.0242 acc: 50.0621% valid loss: 0.0169 acc: 64.4461% Time: 9s train corr: 1613  valid corr: 890
Best val Acc: 64.446054

Epoch [2/99] train loss: 0.0176 acc: 59.9628% valid loss: 0.0143 acc: 69.5873% Time: 9s train corr: 1932  valid corr: 961
Best val Acc: 69.587256

- GPU Train Heartrate logs

unique classes size 1
cuda:0
total GPU: 4
train size: 3222, valid size 1381, lr: 0.00100, Adam, beta1: 0.900, beta2: 0.999, step_size: 5, gamma: 0.950

Epoch [0/99] train loss: 0.2402 valid loss: 0.1911  Time: 6s
Best val loss: 0.191076

Epoch [1/99] train loss: 0.1374 valid loss: 0.2055  Time: 10s
Best val loss: 0.191076

Epoch [2/99] train loss: 0.1043 valid loss: 0.1023  Time: 6s
Best val loss: 0.102312

Epoch [3/99] train loss: 0.0903 valid loss: 0.0987  Time: 11s
Best val loss: 0.098749

Epoch [4/99] train loss: 0.0864 valid loss: 0.0977  Time: 11s
Best val loss: 0.097724
