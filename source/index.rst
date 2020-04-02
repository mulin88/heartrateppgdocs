.. HeartratePPG documentation master file, created by
   sphinx-quickstart on Fri Mar 13 10:01:51 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

HeartratePPG
============
Data analytics for time series
   - Photoplethysmography
   - Accelerometer (x, y, z)

Use cases includes
   - heartrate predictions
   - Human Activity Recognition
   - change detection for PPG

Frameworks includes
   - Pytorch
   - CNN
   - LSTM
   - with attention layer
   - with multi-tasks layer
   - singular-spectrum analysis (SSA)

Repository
   - https://gitlabe2.ext.net.nokia.com/mulin/heartrateppg2

Quick Demo
   - http://10.139.35.126:8888/

Youtube recording
   - https://youtu.be/vM-QRfYCyh0


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   data/raw_data_process
   data/FFT_normalization
   model/CNN
   model/LSTM
   model/LSTM_with_attention
   model/LSTM_with_attention_GPU
   model/change_detection
   deploy/ONNX_deployment
   deploy/Kubeflow_deployment
   deploy/C_deployment
   references


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
