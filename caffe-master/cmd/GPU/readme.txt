GPUģʽ�£���Ҫ�������¼����ļ���
1.lenet_solver.prototxt��
  solver_mode: GPU
  net:lenet_train_test.prototxt·��
  snapshot_prefix:·��

2.CommonSettings.props��
  <CpuOnlyBuild>false</CpuOnlyBuild>
        
  <UseCuDNN>false</UseCuDNN>
3.lenet_train_test.prototxt��
  mnist_train_lmdb��·��
  mnist_test_lmdb��·��
4.cuda7.5���������ص�ַ��https://developer.nvidia.com/cuda-downloads