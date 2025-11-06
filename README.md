Keras example from the structured data section.

The main environemnt should be the tf_2.20 from above. 

$ pip list | grep cuda

nvidia-cuda-cupti-cu12    12.9.79
nvidia-cuda-nvcc-cu12     12.9.86
nvidia-cuda-nvrtc-cu12    12.9.86
nvidia-cuda-runtime-cu12  12.9.79


$ pip list | grep tensorflow

tensorflow                2.20.0


$ pip list | grep keras

keras                     3.12.0


$ pip list | grep nvidia

nvidia-cublas-cu12        12.9.1.4
nvidia-cuda-cupti-cu12    12.9.79
nvidia-cuda-nvcc-cu12     12.9.86
nvidia-cuda-nvrtc-cu12    12.9.86
nvidia-cuda-runtime-cu12  12.9.79
nvidia-cudnn-cu12         9.15.0.57
nvidia-cufft-cu12         11.4.1.4
nvidia-curand-cu12        10.3.10.19
nvidia-cusolver-cu12      11.7.5.82
nvidia-cusparse-cu12      12.5.10.65
nvidia-nccl-cu12          2.28.7
nvidia-nvjitlink-cu12     12.9.86


$ nvcc --version

nvcc: NVIDIA (R) Cuda compiler driver
Copyright (c) 2005-2023 NVIDIA Corporation
Built on Fri_Sep__8_19:17:24_PDT_2023
Cuda compilation tools, release 12.3, V12.3.52
Build cuda_12.3.r12.3/compiler.33281558_0


$ nvidia-smi

Thu Nov  6 15:52:59 2025       
+-----------------------------------------------------------------------------------------+
| NVIDIA-SMI 580.95.05              Driver Version: 580.95.05      CUDA Version: 13.0     |
+-----------------------------------------+------------------------+----------------------+
| GPU  Name                 Persistence-M | Bus-Id          Disp.A | Volatile Uncorr. ECC |
| Fan  Temp   Perf          Pwr:Usage/Cap |           Memory-Usage | GPU-Util  Compute M. |
|                                         |                        |               MIG M. |
|=========================================+========================+======================|
|   0  NVIDIA GeForce RTX 2080 Ti     Off |   00000000:08:00.0  On |                  N/A |
|  0%   27C    P8             20W /  250W |    9773MiB /  11264MiB |      2%      Default |
|                                         |                        |                  N/A |
+-----------------------------------------+------------------------+----------------------+

+-----------------------------------------------------------------------------------------+
| Processes:                                                                              |
|  GPU   GI   CI              PID   Type   Process name                        GPU Memory |
|        ID   ID                                                               Usage      |
|=========================================================================================|
|    0   N/A  N/A            3924      G   /usr/lib/xorg/Xorg                      204MiB |
|    0   N/A  N/A            4812      G   /usr/bin/gnome-shell                     46MiB |
|    0   N/A  N/A            8937      G   .../7177/usr/lib/firefox/firefox        334MiB |
|    0   N/A  N/A           22976      C   ...ml/tf_2.20/tf_2.20/bin/python       9170MiB |
+-----------------------------------------------------------------------------------------+



Unless an example requires a different one. 

