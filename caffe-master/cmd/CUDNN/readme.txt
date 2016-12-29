GPU模式下，需要更改以下几个文件：
1.lenet_solver.prototxt中
  solver_mode: GPU
  net:lenet_train_test.prototxt路径
  snapshot_prefix:路径

2.CommonSettings.props中
  <CpuOnlyBuild>false</CpuOnlyBuild>
        
  <UseCuDNN>true</UseCuDNN>
<CuDnnPath>D:\OpenCVProject\WindowsCaffeProject\WindowsCaffeProject-2016-12-01\</CuDnnPath> //相应版本的cudnn库路径
3.lenet_train_test.prototxt中
  mnist_train_lmdb的路径
  mnist_test_lmdb的路径
4.cuda7.5工具箱下载地址：https://developer.nvidia.com/cuda-downloads
