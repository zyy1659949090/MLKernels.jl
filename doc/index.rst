========================
Machine Learning Kernels
========================

`MLKernels.jl`_ is a Julia package for Mercer kernel functions (or the 
covariance functions of Gaussian processes) that are used in the kernel 
methods of machine learning. This package provides a collection of kernel
datatypes for representing kernel functions as well as an efficient set of 
methods to compute or approximate kernel matrices. The package has no 
dependencies beyond base Julia.

------------
Installation
------------

The package may be added by running one of the following lines of code:

.. code-block:: julia

    # Latest stable release in Metadata:
    Pkg.add("MLKernels")

    # Most up-to-date (not stable):
    Pkg.checkout("MLKernels")

    # Development (bleeding edge):
    Pkg.checkout("MLKernels", "dev")


---------------
Getting Started
---------------

Documentation on the interface implemented by `MLKernels.jl`_ is available under
the interface section listed in the table of contents below or on the sidebar:

.. toctree::
    :maxdepth: 1

    interface
    kernels
    kerneltheory

A listing of the implemented kernel functions and their properties is available
on the kernels page and documentation on the theory surrounding kernel functions
and the kernel trick is available in the kernel theory section.

.. _MLKernels.jl: https://github.com/trthatcher/MLKernels.jl
