# KernelPack
Radial Basis Function-Finite Difference (RBF-FD) methods for solving PDEs on arbitrary 2D and 3D domains.

This header-only C/C++ library implements modern RBF-FD methods for solving PDEs, and RBF methods for geometric modeling. 

1. It uses polyharmonic splines with high-degree polynomials, and therefore is free of saturation errors and shape parameters. 
2. The library does its own automatic node generation on parametric domains given only a small set of seed nodes on the domain boundary.
3. The library generates a high-order boundary representation for any parametric irregular domain in 2D or 3D, provided it is closed. 
4. The library also implements RBF-FD methods for solving PDEs on arbitrary closed surfaces embedded in 2D and 3D domains.

