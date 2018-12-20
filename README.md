# Caffe2
This version of Caffe2 is serving vending api provided by Haishen Tech. 

## Requirements
- CUDA 8.0
- CUDNN 7.1.2

## Installation
```
$ cd root/dir/of/caffe2
$ mkdir build && cd build
$ cmake .. \
-DUSE_MPI=OFF \
-DCUDNN_INCLUDE_DIR=/some/where/cudnn_7_1_2/include \
-DCUDNN_LIBRARY=/some/where/cudnn_7_1_2/lib/libcudnn.so \
-DUSECUDA=ON
$ make -j8
```
