- 简体中文版
- [繁體中文版](./README_TW.md)
- [English version](./README_EN.md)

# Many Stars Client Code Repository - 繁星计划客户端代码仓库
## 一、简介
本仓库为大型Minecraft服务器企划“繁星计划”的官方代码仓库，用于存放下属各类客户端的代码以及资源。

## 二、项目组成员
- **涅槃**
  - 职位：项目负责人、核心组件负责人、服主
  - Java版游戏ID：MC_Nirvana
  - 基岩版游戏ID：MCNirvana
- **傻猫不让撸（猫猫）**
  - 职位：数值策划、魔改组件负责人、接待
  - Java版游戏ID：free_cat_eating
  - 基岩版游戏ID：none
- **似曾相识魇归来（归来）**
  - 职位：数值策划、魔改组件负责人
  - Java版游戏ID：SCXSYGL
  - 基岩版游戏ID：none

## 三、仓库分支介绍
- **main**
  - 介绍：主分支，存放仓库自述文件和版本号设计方案
- **starfield-full**
  - 介绍：星空神域全量版客户端分支
- **starfield-lite**
  - 介绍：星空神域轻量版客户端分支
- **starfield-full-aero**
  - 介绍：星空神域全量版客户端分支（机械动力：航空学测试分支）

## 四、客户端安装指南
### 4-1: 环境要求
#### 模组服客户端（全量版）
- **Windows**
  - 平台版本：Windows 10 1607 或更高版本
  - JDK版本：21
  - 处理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 显卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 内存要求：至少预留 12G 可用空间
  - 存储空间要求：至少预留 32G 可用空间

- **macOS**
  - 平台版本
    - Intel：macOS 10.15 Catalina 或更高版本
    - Apple Silicon：macOS 11 Big Sur 或更高版本
  - JDK版本：21
  - 处理器要求
    - Intel：i7-8750H 或更高
    - Apple Silicon：M1 或更高
  - 显卡要求：
    - AMD：Radeon Pro 555X 或更高
    - Apple Silicon：M1 或更高
  - 内存要求：至少预留 12G 可用空间
  - 存储空间要求：至少预留 32G 可用空间

- **Linux**
  - 平台版本
    - 系统版本：Ubuntu 14.04 或更高版本
    - Glibc版本：glibc 2.17 或更高版本
  - JDK版本：21
  - 处理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 显卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 内存要求：至少预留 12G 可用空间
  - 存储空间要求：至少预留 32G 可用空间

#### 插件服客户端（轻量版）
- **Windows**
  - 平台版本：Windows 10 1809 或更高版本
  - JDK版本：25
  - 处理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 显卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 内存要求：至少预留 8G 可用空间
  - 存储空间要求：至少预留 32G 可用空间

- **macOS**
  - 平台版本：
    - Intel：macOS 11 Big Sur 或更高版本
    - Apple Silicon：macOS 11 Big Sur 或更高版本
  - JDK版本：25
  - 处理器要求
    - Intel：i7-8750H 或更高
    - Apple Silicon：M1 或更高
  - 显卡要求：
    - AMD：Radeon Pro 555X 或更高
    - Apple Silicon：M1 或更高
  - 内存要求：至少预留 8G 可用空间
  - 存储空间要求：至少预留 32G 可用空间

- **Linux**
  - 平台版本：
    - 系统版本：Ubuntu 20.04 或更高版本
    - Glibc版本：glibc 2.28 或更高版本
  - JDK版本：25
  - 处理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 显卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 内存要求：至少预留 8G 可用空间
  - 存储空间要求：至少预留 32G 可用空间

### 4-2: 软件要求
- 启动器
  - [Prism Launcher](https://prismlauncher.org/)
    - 支持平台：Windows / macOS / Linux
  - [Hello Minecraft! Launcher](https://hmcl.huangyuhui.net/)
    - 支持平台：Windows / macOS / Linux
  - [Plain Craft Launcher Community Edition](https://www.pclc.cc/projects/pcl-ce/)
    - 支持平台：Windows

### 4-3: 客户端安装教程（以Prism Launcher为例）
1. 首先从[Github Release](https://github.com/StarRiverStudios/many-stars-client/releases/latest)下载客户端整合包文件
2. 打开启动器，点击`添加实例`
3. 在新增实例界面中，选择左侧导航栏的`导入`选项
4. 在导入界面，点击下方的`浏览`按钮，选择你下载的整合包文件
5. 之后点击`确定`，开始导入
6. 等待导入完成（期间会自动下载所需的模组、材质、光影等资源）
7. 启动游戏

## 五、玩家社区
- [QQ](https://qm.qq.com/q/RgessVyPC0)
- [Discord](#)

## 六、赞助支持
如果你希望支持本服务器的持续开发和维护，可以通过以下方式赞助：

- [爱发电](https://ifdian.net/a/MC-Nirvana) - 通过爱发电赞助（适用于中国大陆地区用户）
- [Ko-fi](https://ko-fi.com/mcnirvana) - 通过 Ko-fi 赞助（适用于海外用户）

您的赞助将用于：
- 维护服务器基础设施
- 请作者去码头整点薯条^_^