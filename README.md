# PyOpenJTalk 0.4.1 Pre-compiled Wheel for Windows (Python 3.12) 🚀

[English](#english) | [中文说明](#中文)

---

<h2 id="english">🇬🇧 English</h2>

### What is this?
This repository provides a pre-compiled `.whl` (wheel) file for `pyopenjtalk` (v0.4.1), specifically built for **Windows (x86_64 / AMD64)** users running **Python 3.12**.

### Why does this exist?
If you try to install `pyopenjtalk` on Python 3.12 via standard `pip install`, it will likely fail with a massive `Failed to build wheel` or `CMake Error: CMAKE_C_COMPILER not set` error. This is because official pre-compiled wheels for Python 3.12 are currently missing, forcing pip to build it from source—which requires downloading and installing several gigabytes of Microsoft Visual Studio C++ Build Tools.

I compiled this manually using MSVC so you don't have to suffer through the installation hell. Just download and install!

### 🌟 Highly Recommended Use Case: GPT-SoVITS on AMD ROCm 7.2
This wheel is an absolute lifesaver if you are trying to deploy the open-source voice cloning project **[GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)** locally using an **AMD GPU**. 
To get native hardware acceleration on AMD cards via **ROCm 7.2 on Windows**, you are forced to use Python 3.12. This pre-compiled wheel acts as the perfect missing puzzle piece to help you bypass the compiler errors and complete your GPT-SoVITS AMD setup painlessly.

### How to use
1. Download the `.whl` file from this repository.
2. Open your terminal/command prompt (ensure your Python 3.12 environment is activated).
3. Run the following command:
```bash
pip install pyopenjtalk-0.4.1-cp312-cp312-win_amd64.whl
```bash
<h2 id="中文">🇨🇳 中文说明</h2>

这是个什么玩意？
本仓库提供了一个专为 Windows 系统 和 Python 3.12 环境预先编译好的 pyopenjtalk (版本 0.4.1) 安装包（.whl 文件）。

为什么需要它？
当你在 Python 3.12 环境下直接运行 pip install pyopenjtalk 时，系统通常会无情地给你扔出一大堆红色的报错信息（比如 Failed to build wheel 或者缺少 C++ 编译器）。这是因为官方目前还没有为 Python 3.12 提供打包好的 Windows 现成文件。如果你想自己解决，就不得不去微软官网下载并安装好几个 G 的 C++ 生成工具来“现场手搓”。

为了拯救大家的硬盘和头发，我已经用 C++ 编译器把它熬夜编译好了！大家直接拿去用，跳过环境报错的无尽折磨。

🌟 强烈推荐场景：在 AMD 显卡 (ROCm 7.2) 上部署 GPT-SoVITS
如果你正在尝试使用 AMD 显卡 在本地部署强大的开源语音克隆项目 GPT-SoVITS，那么这个包绝对是你的“救命神药”。
因为要想在 Windows 下调用 AMD 的 ROCm 7.2 原生算力，你必须使用 Python 3.12。有了这个预编译包，你就能完美闭环，无痛打通 GPT-SoVITS 的所有依赖！

如何安装使用
把本仓库里的 .whl 文件下载到你的电脑上。

打开你的命令行窗口（请确保已经激活了你的 Conda 或 Python 3.12 虚拟环境）。

定位到文件所在的目录，直接运行以下命令秒杀报错：
pip install pyopenjtalk-0.4.1-cp312-cp312-win_amd64.whl
