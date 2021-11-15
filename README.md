# direct3d12-benchmark

A simple implementation of a graphics engine that can load 3d models with textures written using [Direct3D12](https://github.com/microsoft/DirectX-Graphics-Samples). It is used to generate benchmark results for my final year dissertation project in which I compared the performance of [wgpu](https://github.com/gfx-rs/wgpu), [Vulkan](https://github.com/KhronosGroup/Vulkan-Hpp) and [Direct3D12](https://github.com/microsoft/DirectX-Graphics-Samples).

# To build
1. Check you have Windows 10 SDK (19041 is recommended)
2. Check you have Windows 10 (May 2020 Update a.k.a. Version 2004 is recommended)
3. Check you have a Dx12 compatible GPU
4. Open Visual studio sln file as admin
5. Check paths to sdkmesh files (approx line 300 in Game.cpp)
6. Run as release for best performance
