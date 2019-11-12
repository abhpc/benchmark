# benchmark
GPU并行计算测试标准程序
```
in.eam:
mpirun -np 12 lammps-gpu -in in.eam -pk gpu N -l gpuN.log
```
