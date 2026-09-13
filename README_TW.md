- [简体中文版](./README.md)
- 繁體中文版
- [English version](./README_EN.md)

# Many Stars Client Code Repository - 繁星計劃客戶端代碼倉庫
## 壹、簡介
本倉庫為大型 Minecraft 伺服器企劃「繁星計劃」的官方代碼倉庫，用於存放屬下各類客戶端的代碼以及資源。

## 貳、項目組成員
- **涅槃**
  - 職位：專案負責人、核心組件負責人、服主
  - Java 版遊戲 ID：MC_Nirvana
  - 基岩版遊戲 ID：MCNirvana
- **傻猫不让撸（猫猫）**
  - 職位：數值策劃、魔改組件負責人、接待
  - Java 版遊戲 ID：free_cat_eating
  - 基岩版遊戲 ID：none
- **似曾相识魇归来（归来）**
  - 職位：數值策劃、魔改組件負責人
  - Java 版遊戲 ID：SCXSYGL
  - 基岩版遊戲 ID：none

## 參、倉庫分支介紹
- **main**
  - 介紹：主分支，存放倉庫自述文件和版本號設計方案
- **starfield-full**
  - 介紹：星空神域全量版客戶端分支
- **starfield-lite**
  - 介紹：星空神域輕量版客戶端分支
- **starfield-full-aero**
  - 介紹：星空神域全量版客戶端分支（機械動力：航空學測試分支）

## 肆、客戶端安裝指南
### 4-1: 環境要求
#### 模組服客戶端（全量版）
- **Windows**
  - 平台版本：Windows 10 1607 或更高版本
  - JDK 版本：21
  - 處理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 顯示卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 記憶體要求：至少預留 12G 可用空間
  - 儲存空間要求：至少預留 32G 可用空間

- **macOS**
  - 平台版本
    - Intel：macOS 10.15 Catalina 或更高版本
    - Apple Silicon：macOS 11 Big Sur 或更高版本
  - JDK 版本：21
  - 處理器要求
    - Intel：i7-8750H 或更高
    - Apple Silicon：M1 或更高
  - 顯示卡要求：
    - AMD：Radeon Pro 555X 或更高
    - Apple Silicon：M1 或更高
  - 記憶體要求：至少預留 12G 可用空間
  - 儲存空間要求：至少預留 32G 可用空間

- **Linux**
  - 平台版本
    - 系統版本：Ubuntu 14.04 或更高版本
    - Glibc 版本：glibc 2.17 或更高版本
  - JDK 版本：21
  - 處理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 顯示卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 記憶體要求：至少預留 12G 可用空間
  - 儲存空間要求：至少預留 32G 可用空間

#### 插件服客戶端（輕量版）
- **Windows**
  - 平台版本：Windows 10 1809 或更高版本
  - JDK 版本：25
  - 處理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 顯示卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 記憶體要求：至少預留 8G 可用空間
  - 儲存空間要求：至少預留 32G 可用空間

- **macOS**
  - 平台版本：
    - Intel：macOS 11 Big Sur 或更高版本
    - Apple Silicon：macOS 11 Big Sur 或更高版本
  - JDK 版本：25
  - 處理器要求
    - Intel：i7-8750H 或更高
    - Apple Silicon：M1 或更高
  - 顯示卡要求：
    - AMD：Radeon Pro 555X 或更高
    - Apple Silicon：M1 或更高
  - 記憶體要求：至少預留 8G 可用空間
  - 儲存空間要求：至少預留 32G 可用空間

- **Linux**
  - 平台版本：
    - 系統版本：Ubuntu 20.04 或更高版本
    - Glibc 版本：glibc 2.28 或更高版本
  - JDK 版本：25
  - 處理器要求
    - Intel：i5-8300H 或更高
    - AMD：Ryzen 5 2500U 或更高
  - 顯示卡要求：
    - Intel：UHD Graphics 630 或更高
    - NVIDIA：GTX 1050 或更高
    - AMD：Radeon RX 560 或更高
  - 記憶體要求：至少預留 8G 可用空間
  - 儲存空間要求：至少預留 32G 可用空間

### 4-2: 軟體要求
- 啟動器
  - [Prism Launcher](https://prismlauncher.org/)
    - 支援平台：Windows / macOS / Linux
  - [Hello Minecraft! Launcher](https://hmcl.huangyuhui.net/)
    - 支援平台：Windows / macOS / Linux
  - [Plain Craft Launcher Community Edition](https://www.pclc.cc/projects/pcl-ce/)
    - 支援平台：Windows

### 4-3: 客戶端安裝教學（以 Prism Launcher 為例）
1. 首先從 [Github Release](https://github.com/StarRiverStudios/many-stars-client/releases/latest) 下載客戶端整合包文件
2. 打開啟動器，點擊 `新增實例`
3. 在新增實例介面中，選擇左側導航欄的 `匯入` 選項
4. 在匯入介面，點擊下方的 `瀏覽` 按鈕，選擇你下載的整合包文件
5. 之後點擊 `確定`，開始匯入
6. 等待匯入完成（期間會自動下載所需的模組、材質、光影等資源）
7. 啟動遊戲

## 伍、玩家社群
- [QQ](https://qm.qq.com/q/RgessVyPC0)
- [Discord](#)

## 陸、贊助支持
如果你希望支持本伺服器的持續開發和維護，可以透過以下方式贊助：

- [愛發電](https://ifdian.net/a/MC-Nirvana) - 透過愛發電贊助（適用於中國大陸地區使用者）
- [Ko-fi](https://ko-fi.com/mcnirvana) - 透過 Ko-fi 贊助（適用於海外使用者）

您的贊助將用於：
- 維護伺服器基礎設施
- 請作者去碼頭整點薯條^_^