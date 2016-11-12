.. _installing_windows:

Installing PySide on a Windows System
=====================================

Installing prerequisites
------------------------

Install latest ``pip`` distribution: download `get-pip.py
<https://bootstrap.pypa.io/get-pip.py>`_ and run it using
the ``python`` interpreter.

Installing PySide
-----------------

To install PySide on Windows you can choose from the following options:

#. Use pip to install the ``wheel`` binary packages:

   ::

      pip install -U PySide
   
   **Note**: There are only selected versions of binary package in pip. Please check out `this page
   <https://pypi.python.org/pypi/PySide#id41>`_ to see the list of supported python version 
   (including 32/64 bit). If your python version does not correspond to one of the labels, pip
   will not install the wheel. Instead, it will try to compile PySide, which would require more
   tools.

#. Use setuptools to install the ``egg`` binary packages (deprecated):

   ::

      easy_install -U PySide

.. note::

   Provided binaries are without any other external dependencies.
   All required Qt libraries, development tools and examples are included.
