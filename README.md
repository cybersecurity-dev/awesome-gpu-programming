<div align="center">
    <p align="center">
        <a href="https://wikipedia.org/wiki/CUDA">
          <img width="35%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/NVIDIA.svg" />
        </a>
    </p>

```mermaid
timeline
    title GPU Programming Evolution

    1970s : Graphics Accelerators
    1981 : IBM Display Adapter
    1993 : 3D Graphics Acceleration

    1999 : NVIDIA Introduces GPU Term
         : GeForce 256

    2001 : Programmable Vertex Shaders

    2004 : GPGPU Research Growth

    2006 : CUDA Released
         : General Purpose GPU Computing

    2008 : OpenCL Standard

    2010 : CUDA Ecosystem Expansion

    2012 : Deep Learning Revolution
         : AlexNet on GPUs

    2015 : TensorFlow GPU Support

    2017 : AI Boom
         : Volta Tensor Cores

    2020 : Ampere Architecture
         : Large-scale AI Training

    2022 : Hopper Architecture
         : Transformer Optimization

    2024+ : Generative AI
          : LLM Training
          : Multi-GPU Supercomputing
```

# **`Awesome`** [GPU](https://wikipedia.org/wiki/Graphics_processing_unit) [Programming](https://developers.redhat.com/articles/2024/08/07/what-gpu-programming) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/playlist?list=PL9V4Zu3RroiWMN2G3kXw1IMPQ-fUf-3CQ&si=Xg63QDf04tlsbfRJ)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/GraphicsProgramming/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
mindmap
  root((GPU<br/>Programming))

    Languages
      CUDA C++
      OpenCL C
      SYCL
      HIP
      OpenACC

    Vendors
      NVIDIA
      AMD
      Intel
      Apple

    APIs
      CUDA
      OpenCL
      Vulkan Compute
      DirectCompute
      Metal

    AI_Frameworks
      PyTorch
      TensorFlow
      JAX
      MXNet

    HPC
      MPI
      OpenMP
      CUDA MPI
      NCCL

    Visualization
      OpenGL
      Vulkan
      DirectX

    Profiling
      Nsight
      nvprof
      rocProf
      VTune
```

## 📖 Contents
- [Frameworks](#frameworks)
- [Tools](#tools)
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


### Frameworks

#### [Pytorch](https://pytorch.org/get-started/locally/)
* Linux
    ```bash
    pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu132
    ```
* Windows
    ```powershell
    pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu132
    ```
Test
```shell
python -c "import torch; print(torch.__version__)"
```

### Tools
- [nvitop](https://github.com/XuehaiPan/nvitop) - An interactive NVIDIA-GPU [process viewer](https://nvitop.readthedocs.io/en/latest/) and beyond, the one-stop solution for GPU process management.


##
### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-gpu-programming/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-gpu-programming-)
