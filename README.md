# HPC
High Performance Computing project
This project is part of the High Performance Computing module that I had the chance to attend in the first semester.

We were asked to choose a problem and parallelize it using OpenMP and Cuda. 

Our choice was mainly motivated by the increasing need to perform very complex matrix operations in very short times, leaded by the evolution of computer vision and graphics. We made the choice to parallelize LU decomposition which has many uses such as : matrix inverse calculation and system resolutions

**Our results** :
For a matrix of order 1000, the openmp program is almost 4 times more performant than the sequential one and the CUDA program is almost 64 times faster than the sequential.
 
**This work is done by :**
MAMMA salima and
AIN GUERAD manel
