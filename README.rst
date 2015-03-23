jupytor extension for the IPython notebook
==========================================

IPython magics to embed http://www.pythontutor.com within an IFrame in
the IPython notebook using the code from an IPython code cell.

Install
-------

.. code:: python

    pip install jupytor

or

.. code:: python

    pip install git+https://github.com/kikocorreoso/jupytor.git

Tested on Python 2.7 and Python 3.4 and IPython 3.0.0.

Usage
-----

In a code cell in the notebook type the following:

.. code:: python

    %%jupytor --lang python3
    # some python code
    # ...

Options
-------

The only available option is the ``--lang`` or ``-l`` that allows you to
choose one othe the available languages supported by
`pythontutor <http://www.pythontutor.com>`__

-  ``%%jupytor --lang python3`` or ``%%jupytor -l python3`` or
   ``%%jupytor`` to show a pythontutor IFrame with python3 code.
-  ``%%jupytor --lang python2`` or ``%%jupytor -l python2`` to show a
   pythontutor IFrame with python2 code.
-  ``%%jupytor --lang java`` or ``%%jupytor -l java`` to show a
   pythontutor IFrame with java code.
-  ``%%jupytor --lang javascript`` or ``%%jupytor -l javascript`` to
   show a pythontutor IFrame with javascript code.
