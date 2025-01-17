Installation
============


It is recommended to use **pip** for installation.
Please make sure **the latest version** is installed, as PyGOD is updated frequently:

.. code-block:: bash

   pip install pygod            # normal install
   pip install --upgrade pygod  # or update if needed


Alternatively, you could clone and run setup.py file:

.. code-block:: bash

   git clone https://github.com/pygod-team/pygod.git
   cd pygod
   pip install .

**Required Dependencies**\ :

* Python 3.8+
* numpy>=1.24.3
* scikit-learn>=1.2.2
* scipy>=1.10.1
* networkx>=3.1


**Note on PyG and PyTorch Installation**\ :
PyGOD depends on `PyTorch Geometric (PyG) <https://www.pyg.org/>`_ and `PyTorch <https://pytorch.org/>`_.
To streamline the installation, PyGOD does **NOT** install these libraries for you.
Please install them from the above links for running PyGOD:

* torch>=2.0.0
* pytorch_geometric>=2.3.0