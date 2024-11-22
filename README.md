# 边缘AI（Edge AI）

## 硬件

- [OpenMV](http://docs.openmv.io)：一款支持MicroPython的摄像头，基于ARM Cortex M6/M7，支持丰富的计算机视觉算法，并且现在已支持[TensorFlow Lite](https://openmv.io/blogs/news/tensorflow-lite-and-person-detection)。
- [JeVois](http://jevois.org/)：支持TensorFlow的摄像头模块。
- [Edge TPU](https://cloud.google.com/edge-tpu/)：Google专门为边缘推理设计的ASIC。
- [Movidius](https://www.movidius.com)：Intel的SoC家族，专为低功耗设备的计算机视觉和神经网络应用设计。
  - [UP AI Edge](https://up-shop.org/25-up-ai-edge)：基于Intel Movidius VPU（Myriad 2和Myriad X）和Intel Cyclone FPGA的产品线。
  - [DepthAI](https://www.crowdsupply.com/luxonis/depthai)：基于Myriad X的集深度和AI功能的嵌入式平台。
- [NVIDIA Jetson](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/)：高性能嵌入式模块，适用于深度学习、计算机视觉、GPU计算和图形处理。
  - Jetson TX1
  - Jetson TX2
  - Jetson Nano
- [AIR-T](https://www.crowdsupply.com/deepwave-digital/air-t)：高性能的无线电收发器，集成了深度学习硬件。
- [Kendryte K210](https://canaan.io/product/kendryteai)：双核RISC-V芯片，配有64个卷积神经网络加速单元。
  - [Sipeed M1](http://en.dan.sipeed.com/)：基于K210的模块，增加了WiFi连接和外部闪存。
  - [M5StickV](https://docs.m5stack.com/#/en/core/m5stickv)：AIoT摄像头，基于Kendryte K210。
  - [UNIT-V](https://docs.m5stack.com/#/en/unit/unitv)：AI摄像头，基于K210的低端版。
- [Kendryte K510](https://canaan.io/product/kendryteai)：三核RISC-V处理器，配有AI加速器。
- [GreenWaves GAP8](https://greenwaves-technologies.com/en/gap8-product/)：基于RISC-V的芯片，具有卷积操作硬件加速功能。
- [Ultra96](https://www.96boards.ai/products/ultra96/)：基于Xilinx UltraScale+ MPSoC FPGA的嵌入式开发平台。
- [Apollo3 Blue](https://www.sparkfun.com/products/15170)：由Ambiq Micro的Cortex M4驱动的SparkFun Edge开发板。
- [Google Coral](https://coral.ai/)：基于Google Edge TPU的硬件和软件平台。
  - 开发板
  - USB加速器
  - PCIe / M.2模块
- [Gyrfalcon Lighspeeur](https://www.gyrfalcontech.ai/solutions/)：为边缘计算优化的芯片家族。
- [ARM microNPU](https://www.arm.com/products/silicon-ip-cpu/machine-learning/ethos-u55)：用于加速机器学习推理的处理器（如Ethos-U55）。
- [Espressif ESP32-S3](https://www.espressif.com/en/products/socs/esp32-s3)：类似于ESP32的SoC，支持AI加速。
- [Maxim MAX78000](https://www.maximintegrated.com/en/products/microcontrollers/MAX78000.html)：基于Cortex-M4的SoC，包含CNN加速器。
- [Beagleboard BeagleV](https://beagleboard.org/beaglev)：开源RISC-V Linux板，包含神经网络引擎。
- [Syntiant TinyML](https://www.syntiant.com/tinyml)：基于Syntiant NDP101神经决策处理器和SAMD21 Cortex-M0+的开发套件。

## 软件

- [TensorFlow Lite](https://www.tensorflow.org/lite/)：用于移动和嵌入式设备的轻量级机器学习推理解决方案，具有低延迟和小巧的二进制文件。
- [TensorFlow Lite for Microcontrollers](https://www.tensorflow.org/lite/microcontrollers)：专门为微控制器及其他小内存设备移植的TF Lite版本。
- [Embedded Learning Library (ELL)](https://github.com/Microsoft/ELL)：微软的库，用于将智能机器学习模型部署到小型单板计算机上。
- [uTensor](https://github.com/uTensor/uTensor)：基于mbed（ARM芯片RTOS）和TensorFlow的AI推理库。
- [CMSIS NN](https://arm-software.github.io/CMSIS_5/NN/html/index.html)：高效的神经网络内核，最大化Cortex-M处理器上的性能并最小化内存占用。
- [ARM Compute Library](https://developer.arm.com/technologies/compute-library)：图像处理、计算机视觉和机器学习的优化函数集合。
- [Qualcomm Neural Processing SDK for AI](https://developer.qualcomm.com/software/qualcomm-neural-processing-sdk)：库，供开发者在Snapdragon平台上运行神经网络模型。
- [ST X-CUBE-AI](https://www.st.com/en/embedded-software/x-cube-ai.html)：生成STM32 MCU上优化的神经网络工具包。
- [ST NanoEdgeAIStudio](https://www.st.com/content/st_com/en/campaigns/nanoedgeaistudio.html)：工具生成可加载到STM32 MCU的模型。
- [NNoM](https://github.com/majianjia/nnom)：专为微控制器设计的神经网络库，支持CMSIS-NN。
- [nncase](https://github.com/kendryte/nncase)：用于Kendryte K210的开源深度学习编译器。
- [deepC](https://github.com/ai-techsystems/dnnCompiler)：针对嵌入式平台的深度学习编译器和推理框架。
- [uTVM](https://tvm.apache.org/2020/06/04/tinyml-how-tvm-is-taming-tiny)：开源的工具，用于优化张量程序。
- [Edge Impulse](https://edgeimpulse.com/)：交互式平台，用于生成可运行在微控制器上的模型。
- [Qeexo AutoML](https://qeexo.com/ml-platform/)：生成适用于微控制器的AI模型的平台。
- [mlpack](https://www.mlpack.org)：C++编写的轻量级机器学习库，支持在MPU上进行设备端学习。
- [AIfES](https://github.com/Fraunhofer-IMS/AIfES_for_Arduino)：平台独立的AI软件框架，专为嵌入式系统优化。
- [onnx2c](https://github.com/kraiskil/onnx2c)：将ONNX模型转换为C代码的编译器，适用于TinyML。

## 其他有趣的资源

- [边缘计算基准测试 (2019年5月)](https://medium.com/@aallan/benchmarking-edge-computing-ce3f13942245)
- [用于边缘AI的硬件基准 - 开源立方卫星工作坊2018](https://github.com/crespum/oscw18-edge-ai)
- [为什么在边缘进行机器学习？](https://towardsdatascience.com/why-machine-learning-on-the-edge-92fac32105e6)
- [教程：在OpenMV相机上进行低功耗深度学习](https://community.arm.com/innovation/b/blog/posts/low-power-deep-learning-on-openmv-cam)
- [TinyML：用TensorFlow在Arduino和超低功耗微控制器上进行机器学习](http://shop.oreilly.com/product/0636920254508.do) - Pete Warden、Daniel Situnayake著。
- [tinyML峰会](https://www.tinymlsummit.org/)：每年在美国加州举办的会议。
- [TinyML论文和项目](https://github.com/gigwegbe/tinyml-papers-and-projects)：TinyML/EdgeAI领域最新的论文和项目集。
- [MinUn](https://github.com/ShikharJ/MinUn)：在微控制器上实现精确的ML推理。

## 贡献指南

- 请先检查是否有重复。
- 保持描述简洁、明了且无偏见。
- 每次建议请单独提交。
- 如有必要，请添加新的类别。
