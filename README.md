# PyTorch-101

### Deep learning: 

Subset of ML that use several layers sof non-linear transformation to progressively extract features from the input data. Uses multiple Neural Network layers, where every layer takes its inputs from the previous layer and progressively refines them to minimise their errors and improve accuracy. Uses high dimensional large data. Widely used in Speech Recognition, Computer Vision applications etc.

### Pytorch: 

Python library, developed by facebook, that facilitates DL projects. Supported by major cloud platforms; supports CPU,GPU,TPU training; supports distributed training.

### Tensors:

PyTorch uses data structure called Tensor to store data (I/P, O/P, intermediate representations). Tensors are a generalization for vectors, matrices or any n-dimensional data structure containing elements of the same datatype (like numpy arrays).

### Tensor attributes

.dtype, .shape, .device, .ndim

torch.dtype = int8/ float32/ 

Cast one datatype to other : Call function by name -->   .to(dtype=int8)

rand, randn, randint(lowint, highint, size)   .manual_seed()

rand_like(), ones_like(), zeros_like()

