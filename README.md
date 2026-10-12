# ISCAS 2027 Live Demonstration

**Live Demonstration: 3-s Time to First Token for a Vision-Language Model on a 7-W Robot FPGA**

Chuqi Zhao, Yuqi Guo, Ruiqi Tang, Yucheng Sun.

[Watch the 2:03 video](https://vackyzhao.github.io/iscas2027-live-demo/) · [Download the MP4](https://raw.githubusercontent.com/vackyzhao/iscas2027-live-demo/main/iscas2027_demo_a53_cuda.mp4)

The reviewed video combines recorded robot-camera scenes with saved measurements. CPU comparison uses the KV260's own Cortex-A53 cores; the GPU comparison uses Jetson Nano CUDA. The base-model input set is identical, while arithmetic differs (A53 Q8_0, FPGA INT8 GEMM, Nano CUDA F16). Nano power and energy were not measured. The h2 cat comparison is separate.

Only the reviewed final video and this viewer are published here.
