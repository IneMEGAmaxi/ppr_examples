This file documents a python module built from C++ code with pybind11.
You should document the Python interfaces, *NOT* the C++ interfaces.

Module ppr_examples.ex_in_cpp
**************************

Module :py:mod:`ex_in_cpp` built from C++ code in ppr_examples.ex_in_cpp
cpp`.

.. function:: add(x,y,z)
   :module: ppr_examples.ex_in_cpp
   
   Compute the sum of *x* and *y* and store the result in *z* (overwrite).

   :param x: 1D Numpy array with ``dtype=numpy.float64`` (input)
   :param y: 1D Numpy array with ``dtype=numpy.float64`` (input)
   :param z: 1D Numpy array with ``dtype=numpy.float64`` (output)
   