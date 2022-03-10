|License|  |Documentation|

NVIDIA DALI DEMO
================

This repository contains demo of NVIDIA DALI usage with PyTorch.

Usage
=====

1. Install GIT LFS:

https://git-lfs.github.com/

2. Clone this repository:

``git clone https://github.com/awolant/dali_demo``

3. Build Docker container with the demo:

``docker build -t nvidia/dali_demo .``

4. Run the demo:

``docker run --rm --gpus all nvidia/dali_demo python dali_demo.py``

Resources
=========

* Homepage: https://github.com/NVIDIA/DALI
* Docs: https://docs.nvidia.com/deeplearning/sdk/dali-developer-guide/docs/index.html

Licence
=======

Unless stated otherwise DALI Demo is licenced under Apache 2.0

* MNIST dataset contained within DALI Demo is licenced under Creative Commons Attribution-ShareAlike 3.0 Unported

.. |License| image:: https://img.shields.io/badge/License-Apache%202.0-blue.svg
   :target: https://opensource.org/licenses/Apache-2.0

.. |Documentation| image:: https://img.shields.io/badge/Nvidia%20DALI-documentation-brightgreen.svg?longCache=true
   :target: https://docs.nvidia.com/deeplearning/sdk/dali-developer-guide/
