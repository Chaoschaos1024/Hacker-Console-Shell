<!--
 * @Author: 无序熵增
 * @Date: 2025-12-17 12:30:18
 * @LastEditors: 无序熵增
 * @LastEditTime: 2025-12-17 12:40:17
 * @Description: 
 * 
 * Copyright (c) 2025 by 无序熵增, All Rights Reserved. 
-->
# Hacker Console 开源项目

## 项目介绍
**Hacker Console** 是一款由本人设计的手持终端，采用树莓派 B 系列作为主板。  
如果你对我的设计感兴趣，请在 **Bilibili** 上搜索 **"Hacker Console"**。

![Hacker Console 正面视图](image/front.jpg)

作为一款拓展性极强的手持终端，它具有以下特性：
- **免驱动的 HDMI 屏幕**，支持触摸功能
- 键盘采用 **HID 协议**，通过 **USB 通信**，即插即用
- 键盘为独立 PCB 设计，可替换
- 配备一块**副屏**，用于显示设备状态
- 提供 **GPIO 引脚引出**
- **外壳设计开源**

## 设备视图
<div align="center">
<table>
<tr>
<td align="center"><img src="image/right.jpg" alt="右侧视图" width="90%"><br>右侧视图</td>
<td align="center"><img src="image/left.jpg" alt="左侧视图" width="90%"><br>左侧视图</td>
</tr>
<tr>
<td align="center"><img src="image/up.jpg" alt="顶部视图" width="90%"><br>顶部视图</td>
<td align="center"><img src="image/inside.jpg" alt="内部结构" width="90%"><br>内部结构</td>
</tr>
</table>
</div>

## 结构件版本选择指南

### 📌 版本对应关系
| 您的设备版本 | 推荐结构件文件 | 适用说明 |
|--------------|----------------|----------|
| **老版本**（初版键盘 + 初版主板） | `HackerConsle结构件-适用于初版键盘和初版主板.3mf` | 兼容最早的硬件设计 |
| **新版本**（改进版键盘 + 改进版主板） | `HackerConsole结构件-适用于改进后的键盘以及改进后的主板.3mf` | 包含最新的优化设计 |

### 🔧 通用物料说明
> **重要提示**：两个版本使用**相同的通用物料**，包括：
> - 各类螺丝
> - 转轴机构
> - 标准连接件

**请务必参考物料清单文件**：📁 `物料清单.csv`


### 🛠️ 如何选择正确版本
#### 1. 识别您的硬件版本
- **老版本特征**：键盘有突起的黑色摇杆，扬声器模块为单独的pcb
- **新版本特征**：小的金属摇杆，新主板扬声器为带金属触点的器件，没有接线

#### 2. 下载对应文件
```markdown
✅ **如果您是老版本用户：**
   下载 → [HackerConsle结构件-适用于初版键盘和初版主板.3mf]

✅ **如果您是新版本用户：**
   下载 → [HackerConsole结构件-适用于改进后的键盘以及改进后的主板.3mf]
```

#### 3. 打印前检查
1. **核对尺寸**：使用3D打印软件预览，确保与您的硬件匹配
2. **参考物料表**：对照`物料清单.csv`准备所需螺丝和配件

### ⚠️ 注意事项
- ❗ **不要混用版本**：新旧版本结构件**不兼容**
- 🔍 **仔细核对**：打印前请确认文件名称完全匹配
- 📋 **准备物料**：根据`物料清单.csv`提前准备所有螺丝和标准件
- 🖨️ **打印设置**：建议使用PLA材料

### 💡 需要帮助？
如果您无法确定自己的硬件版本，请加入群聊：867028792


*两个版本的设计都经过充分测试，选择正确的结构件可确保最佳装配效果。*

## 许可证
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
