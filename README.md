# marray
library for linear algebra operations with built in auto differentiation 

resources:

https://en.wikipedia.org/wiki/LU_decomposition

http://blog.ezyang.com/2019/05/pytorch-internals/

https://towardsdatascience.com/recreating-pytorch-from-scratch-with-gpu-support-and-automatic-differentiation-8f565122a3cc

https://medium.com/sfu-cspmp/diy-deep-learning-crafting-your-own-autograd-engine-from-scratch-for-effortless-backpropagation-ddab167faaf5

Matrix Differentiation ( and some other stuff ), Randal J. Barnes, Department of Civil Engineering, University of Minnesota Minneapolis, Minnesota, USA

Set Up:

to build c library, use Makefile by running:
% make clean && make

then you can try your code out by importing Marray from marray like in tests
#from marray import *