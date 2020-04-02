C deployment
=====================================
Convert Pytorch model to C code then deploy

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Compile python code to C
------------------------

.. code-block::

   ./buildC.sh

Copy to so module file
----------------------

   mv har.cpython-37m-darwin.so har.so

Run python code with import C module
------------------------------------

.. code-block:: Python

   python run.py