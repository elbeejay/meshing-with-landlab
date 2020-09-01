.. _dependencies:

============================
Installation of Dependencies
============================

To run the examples, there are a handful of Python libraries that must be installed.
Here we will try to summarize the libraries and how they can be installed.
Links and references to more detailed installation instructions from the source libraries themselves will be provided as well.

numpy
-----
This is a pretty standard computational library, it can be `pip` installed if needed:

::

   pip install numpy

For additional information, see the `numpy <https://numpy.org/>`_ website.

matplotlib
----------
For basic visualizations, this is also a commonly used library.
If needed, it can be `pip` installed as well:

::

   pip install matplotlib

For additional information, see the `matplotlib <https://matplotlib.org/>`_ website.

landlab
-------
`Landlab <https://landlab.readthedocs.io/en/latest/index.html>`_ is a modular set of tools for landscape evolution modeling.
`Installation instructions <https://landlab.readthedocs.io/en/latest/install/index.html#installation-instructions>`_ are provided for both `conda` and `pip` installation of this package.
These commands are:

::

   conda install landlab -c conda-forge

and

::

   pip install landlab

Refer to their `documentation <https://landlab.readthedocs.io/en/latest/index.html>`_ for more information about landlab.

dmsh
----
`dmsh <https://github.com/nschloe/dmsh>`_ is a fully Pythonic mesh generator.
It can be `pip` installed:

::

   pip install dmsh

For more information, visit the project `repository <https://github.com/nschloe/dmsh>`_.

Anuga
-----
`Anuga <https://github.com/GeoscienceAustralia/anuga_core>`_ is a Python package developed for simulating the shallow water equations.
Installation of Anuga can be a bit challenging as it interfaces with C under the hood.
In addition to dependencies created by non-Python programming langauges, Anuga also uses popular geospatial libraries.
Geospatial libraries are notorious for causing dependency clashes.
To further complicate matters, Anuga is currently (as of Sept, 2020) still in Python 2.7.
Fear not, for a Python 3.x branch exists, and that is what the examples shown here will be based on.

Installation of Anuga is described in the project `wiki <https://github.com/GeoscienceAustralia/anuga_core/wiki>`_.
We suggest installation via `Miniconda` or `Anaconda` to help manage the dependencies.

.. note::
   After running `git clone` to get a local copy of the Anuga repository prior to installation, you should be sure to **checkout** the `anuga_py3 <https://github.com/GeoscienceAustralia/anuga_core/tree/anuga_py3>`_ branch to ensure the version of Anuga you install is Python 3.x compatible.

itkwidgets
----------
`itkwidgets <https://github.com/InsightSoftwareConsortium/itkwidgets>`_ is a nifty package for creating interactive visualizations within Jupyter Notebooks.
The package can be both `conda` and `pip` installed:

::

   conda install -c conda-forge itkwidgets

and

::

   pip install itkwidgets

Visit the project `repository <https://github.com/InsightSoftwareConsortium/itkwidgets>`_ for more information about this library.

PyVista
-------
`PyVista <https://github.com/pyvista/pyvista>`_ brings the power of VTK visualizations to Python.
It can be `pip` installed:

::

   pip install pyvista

For more information about the installation process and the project, visit the `PyVista documentation <https://docs.pyvista.org/>`_.
