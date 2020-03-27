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

    For GPU version more layers has been added to increase model capacity

    .. code-block:: python

       python PPG_training_HR_GPU.py

    - CPU environment

    For CPU version less layers are used to reduce training time

    .. code-block:: python

       python PPG_training_HR.py


