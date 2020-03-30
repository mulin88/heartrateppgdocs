ONNX deployment
=====================================
convert Pytorch model to ONNX, then deploy on top of ONNX runtime

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Convert Pytorch model to ONNX Model
-----------------------------------
.. code-block:: python

   python HAR_export_ONNX.py

ONNX runtime inferences
-----------------------

.. code-block:: python

   python app_onnx_v6.py