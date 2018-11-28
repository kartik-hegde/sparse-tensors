Tensor Algebra is an important and quickly growing field. The real world tensors are extremely sparse! 
To give an example from [1], The Amazon Reviews tensor would need 107 exabytes of data if stored dense, while only 13 gigabytes is non-zero.

Hence, it is extremely important to develop better sparse representations of the data. In this repository, I will add useful compression-decompression functions for tensors.

Compressed Sparse Fiber is a generalization of CSR/CSC formats for tensors. Hyper-sparse tensors can highly benefit from such a format. Below file can be used to generate any such CSF data (note that CSR/CSC are subsets of CSF).

- generateCSF.py : This gives a simple and efficient recursive implementation of the CSF [2] compression technique on sparse tensors. You can input a tensor of any dimensionality and can choose to have any of the dimensions as sparse/dense.



[1] Kjolstad, Fredrik, et al. "The tensor algebra compiler." Proceedings of the ACM on Programming Languages 1.OOPSLA (2017): 77.

[2] Shaden Smith and George Karypis. 2015. Tensor-matrix products with a compressed sparse tensor. In Proceedings of the 5th Workshop on Irregular Applications: Architectures and Algorithms. ACM, 
