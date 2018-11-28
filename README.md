Tensor Algebra is an important and quickly growing field. The real world tensors are extremely sparse! 
To give an example from [1], The Amazon Reviews tensor would need 107 exabytes of data if stored dense, while only 13 gigabytes is non-zero.

Hence, it is extremely important to develop better sparse representations of the data. In this repository, I will add useful compression-decompression functions for tensors.

- generateCSF.py : This gives a simple and efficient recursive implementation of the CSF [2] compression technique on sparse tensors. You can input a tensor of any dimensionality and can choose to have any of the dimensions as sparse/dense.
