Sphinx
=======

.. _ref_install:

Installation
------------

Update html build files to review changes in windows (/docs)::
   
   ./make.bat html

or::
   
   sphinx-build -b html source/ build/html


.. code:: bash

   echo "This is rendered with the docutils' code directive"


Adding line numbers :<setting>:

.. code-block:: python
   :linenos: 

   a = b
   c > a

.. math::

   d = 1\frac{s}{2}

