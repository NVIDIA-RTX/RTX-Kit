# RTX Kit


## Overview

NVIDIA RTX™ Kit is a suite of neural rendering technologies including NVIDIA’s latest graphics SDKs for realistic path traced lighting and life-like character rendering. This document provides all the necessary supplemental materials to help you learn about RTX Kit and its components, and get started with development.

For more information on RTX Kit, please check our RTX Kit product page over at https://developer.nvidia.com/rtx-kit/.

### System Requirements
To have the best experience with RTX Kit, we recommend the following environment as a baseline:

* Operating System: Win10 20H1 (version 2004 - 10.0.22621.0) or newer
* GPU: DirectX® Raytracing 1.1 API, or higher DXR-Capable GPU
* Graphics Driver: 572.16 or newer
* Vulkan SDK: 1.3.296 or newer
* Visual Studio 2022 or newer
* CMake: v3.24.3 or later

Please note that each SDK within RTX Kit has its own specific system requirements for an optimal experience. Please refer to each SDK's GitHub repository README or the [RTX Kit Getting Started](https://developer.nvidia.com/blog/get-started-with-neural-rendering-using-nvidia-rtx-kit/) blog for more detailed system requirements.

## RTX Kit Components
RTX Kit currently includes the following SDKs:

- DLSS: https://github.com/NVIDIA/DLSS
- RTX Neural Shading: https://github.com/NVIDIA-RTX/RTXNS
- RTX Neural Texture Compression: https://github.com/NVIDIA-RTX/RTXNTC
- RTX Texture Filtering: https://github.com/NVIDIA-RTX/RTXTF
- RTX Texture Streaming: https://github.com/NVIDIA-RTX/RTXTS
- RTX Mega Geometry: https://github.com/NVIDIA-RTX/RTXMG
- RTX Character Rendering: https://github.com/NVIDIA-RTX/RTXCR
- RTX Global Illumination: https://github.com/NVIDIA-RTX/RTXGI
- RTX Dynamic Illumination: https://github.com/NVIDIA-RTX/RTXDI
- RTX Path Tracing: https://github.com/NVIDIA-RTX/RTXPT
- Streamline: https://github.com/NVIDIAGameWorks/Streamline
- Nvidia Realtime Denoisers: https://github.com/NVIDIA-RTX/NRD
- Opacity MicroMap: https://github.com/NVIDIA-RTX/OMM
- RTX Memory Utility: https://github.com/NVIDIA-RTX/RTXMU
- SpatioTemporal Blue Noise: https://github.com/NVIDIA-RTX/STBN



## Getting Started With RTX Kit
For detailed information on how to get started with RTX Kit and its included SDKs, please refer to the [RTX Kit Getting Started](https://developer.nvidia.com/blog/get-started-with-neural-rendering-using-nvidia-rtx-kit/) blog.


### How To Get RTX Kit
To get RTX Kit, clone this repository recursively using the following command:

```
git clone --recursive https://github.com/NVIDIA-RTX/RTX-Kit
```

### How To Update RTX Kit
If you already have a prior clone of RTX Kit and want to update it to the latest version, use the following commands:
```
git pull
git submodule update --init --recursive
```

## Additional Notes
- Please note that the repository locations and URLs for a number of the RTX Kit SDKs have changed with this update. We strongly recommend updating any existing local clones to point to the new repository URL. You can do this by using `git remote` on the command line:
```
git remote set-url origin NEW_URL
```
- This repository serves as an entry point for developer onboarding and provides an overview of RTX Kit and its components. For the latest versions of each SDK, please clone the respective SDK repositories directly.

