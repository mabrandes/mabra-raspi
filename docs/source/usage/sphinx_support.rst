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


functions: 

.. function:: pyfunc()

   Describes a Python function.

Reference to :func:`pyfunc`.

.. py:function:: spam(eggs)
                 ham(eggs)

   Spam or ham the foo.

Manually describing function

.. py:function:: lumache.get_random_ingredients(kind=None)

   Return a list of random ingredients as strings.

   :param kind: Optional "kind" of ingredients.
   :type kind: list[str] or None
   :return: The ingredients list.
   :rtype: list[str]

.. .. currentmodule:: test
.. autofunction:: src.test.diff

   you can use the ``src.test.diff()`` function: