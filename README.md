# TOYDIY 4IN1 Ecub 3D Printer

## 项目简介 | Overview

本仓库整理 TOYDIY 4IN1 3D Printer 的中英文说明书、Ecub 软件资料、
驱动程序、测试模型和测试 G-code。

This repository collects the Chinese and English manuals, Ecub software
resources, drivers, test models, and test G-code for the TOYDIY 4IN1 3D
Printer.

TOYDIY 4IN1 是一款支持 FDM 3D 打印、双色 3D 打印、激光雕刻和 CNC
雕刻等功能的多功能设备。仓库中的资料来自配套打印机资料包。

The TOYDIY 4IN1 is a multifunctional device supporting FDM 3D printing,
dual-color 3D printing, laser engraving, and CNC carving. The materials in
this repository come from the printer's accompanying documentation package.

## 资料范围 | Contents

仓库保留了原始资料包中的 `中文版/` 和 `English/` 目录结构，包含：

The original `中文版/` and `English/` directory structure is preserved. The
repository includes:

- 中文版和英文版用户手册 / Chinese and English user manuals
- EcubWare 和 EcubMakerLaser 软件 / EcubWare and EcubMakerLaser software
- TOYDIY 驱动程序 / TOYDIY drivers
- XLoader 固件烧录工具及相关文件 / XLoader firmware flashing tool and files
- FDM、双色打印、激光雕刻和 CNC 测试 G-code / Test G-code for FDM, dual-color printing, laser engraving, and CNC carving
- FDM 和双色打印测试 STL 模型 / FDM and dual-color printing test STL models
- 激光和 CNC 测试模型预览图片 / Preview images for laser and CNC test models
- 联系方式和软件使用说明 / Contact information and software instructions

## 目录结构 | Directory Structure

```text
中文版/
  驱动程序/
  切片软件/
  说明书/
  样品模型/
  指导视频/                 # 原始资料中的目录，视频未上传
  联系我们/
English/
  Driver/
  Software/
  Manual/
  Models/
  Video Demo/               # Original directory, videos excluded
  Contact Us/
```

仓库中保留了上述目录中除视频以外的文件。部分视频目录可能因为其中的
文件全部被排除而未出现在 Git 中。

The repository keeps all non-video files from these directories. A video
directory may be absent from Git if all of its files were excluded.

## 视频排除说明 | Video Exclusion

本次上传仅排除视频文件，不排除软件、驱动程序或其他可执行文件。共上传
40 个文件，排除 20 个视频文件：19 个 `.mp4` 文件和 1 个 `.MOV` 文件。

Only video files were excluded from this upload. Software, drivers, and other
executable files were not excluded. The repository contains 40 uploaded files
and excludes 20 videos: 19 `.mp4` files and one `.MOV` file.

## 使用提示 | Usage Notes

1. 请先阅读对应语言的用户手册，再安装驱动或使用设备。
2. 根据使用功能选择对应的软件：FDM/双色打印使用 EcubWare，激光功能
   使用 EcubMakerLaser，固件升级使用 XLoader。
3. 测试 G-code 和模型应根据设备当前安装的功能模块、材料和刀具情况使用。
4. 安装程序和驱动程序来自原始资料包，使用前请确认文件来源和运行环境。

1. Read the user manual in the appropriate language before installing drivers
   or operating the device.
2. Use the corresponding software for each function: EcubWare for FDM and
   dual-color printing, EcubMakerLaser for laser functions, and XLoader for
   firmware upgrades.
3. Use the test G-code and models according to the currently installed module,
   material, and tool configuration.
4. The installers and drivers are preserved from the original package. Verify
   their source and runtime environment before use.

## 许可证 | License

文件保留其上游许可证、版权声明和软件许可条款（如果有）。本仓库不对
上游资料重新授权，也不声明拥有第三方软件或文档的版权。

The files retain their upstream licenses, copyright notices, and software
license terms, if any. This repository does not relicense upstream materials
or claim ownership of third-party software or documentation.
