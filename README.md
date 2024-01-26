# deepin 对 RISC-V 板载 GPU 的支持

## 项目名称

deepin 对 RISC-V 板载 GPU 的支持

## 项目描述

本项目旨在于 deepin 平台上为大多数基于 RISC-V 的开发板上的板载 GPU（Imagination PVR）驱动程序提供支持，并尝试将相关补丁合并到 deepin 主线仓库中。

Imagination PVR 是 RISC-V 平台上的主要 GPU 厂商，大多数 RISC-V 开发板都使用其解决方案。然而，Imagination 的 GPU 驱动程序尚未被主线化，大多数主线 linux 发行版仍在 RISC-V 开发板上使用基于 llvmpipe/swrast 的软件渲染。

## 所属赛道

2024全国大学生操作系统比赛的“OS功能设计”赛道

## 项目导师

Github: YukariChiba
Email: yangchang@deepin.org

## 难度

较高

## 参赛要求

以下是选择本题目的必备技能:

- 有使用 Linux 及其桌面环境的经验（有日常使用经验者优先）
- 能够用英语交流，主要是书面交流
- 对开源软件和 linux 桌面操作系统感兴趣
- 熟悉至少一种编程语言

以下是对完成赛题有帮助的可选技能：

- 为 linux 发行版（尤其是基于 debian 的发行版）打包，或为任何 linux 发行版做出贡献
- 了解 Linux 图形栈，如 OpenGL ES 和 Vulkan
- 具有将 RISC-V 及其开发板适配到 linux 操作系统（尤其是桌面环境）的经验

## 预期目标

> [!TIP]
> 选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标。

可能的成果包括

- 提交到 deepin 主仓库的软件包或补丁
- 非主线软件包的独立软件仓库
- 可在 RISC-V 设备上运行并展示、具备 GPU 支持的 deepin v23 镜像，其中的软件包尽可能遵循 deepin 主线
- 社区分享、博客文章、报告或与项目相关的其它内容

推荐 RISC-V 设备：

- Sipeed LicheePi 4A (TH1520)
- StarFive VisionFive 2 (JH7110)

## 从题目中能学到什么

- 熟悉基于 debian 的发行版的打包，掌握如何调试打包问题，成为 deepin 社区的贡献者
- 了解 Linux 发行版开发板的驱动适配过程，并为 RISC-V 生态系统做出贡献
- Linux 图形栈和 RISC-V 架构

## 涉及领域

- C/C++
- Linux 图形栈

## 参考文档

请自行调研当前 Linux 发行版对 RISC-V 开发板 GPU 的支持状况。

与本项目相关的可能有：
- mesa 文档： https://docs.mesa3d.org

## License

GPL-v2
