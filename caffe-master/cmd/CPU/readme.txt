CPU模式下，需要更改以下几个文件：
1.lenet_solver.prototxt中
  solver_mode: CPU
  net:lenet_train_test.prototxt路径
  snapshot_prefix:路径

2.CommonSettings.props中
  <CpuOnlyBuild>true</CpuOnlyBuild>
        
  <UseCuDNN>false</UseCuDNN>
3.lenet_train_test.prototxt中
  mnist_train_lmdb的路径
  mnist_test_lmdb的路径
