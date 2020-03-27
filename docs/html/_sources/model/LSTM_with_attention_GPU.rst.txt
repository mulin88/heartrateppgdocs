LSTM with attention (GPU)
=====================================
LSTM + attention layer model and support GPU based training

.. toctree::
   :maxdepth: 2
   :caption: Contents:

This part is about using LSTM with attention model to train and do regression for Heartrate and classificaiton for Activity
by using the same sort of training data.

Another component MTL (multi-tasks-learning) has also been embedded into the this model.

- Codes folder in "/LSTM_attention_gpu/"

- How to run
    - GPU environments

    .. code-block:: python

        python HARgpu2.py


Training logs:
    cuda:0

    total GPU: 4

    Parameters: biLSTM? True, attention? True, MLT? True,  n_layers 2, n_hidden 256, d_a 100, r 10,  dropout 0.5, HR_L1_Loss? True, lr 0.001, epochs 1000

    Training on GPU!

    Epoch: 1/1000.. Train Loss1: 1.6238 Train Loss2: 75.0616

                Val   Loss1: 1.6220... L1loss: 53.0811... Acc: 0.4336... F1: 0.3140...

                Test   Loss1: 1.6250... L1loss: 53.8094... Acc: 0.4357... F1: 0.3094...





