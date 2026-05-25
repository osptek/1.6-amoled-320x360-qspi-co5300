# 1.6 寸 320×360 AMOLED QSPI 模组（CO5300）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **ESP-IDF 示例工程**。数据手册与规格书待后续补充至 `docs/`。

## 产品概要

| 项目 | 说明 |
|:--|:--|
| 模组规格 | 1.6 英寸 **AMOLED**，分辨率 **320×360** |
| 接口 | **QSPI** |
| 驱动芯片 | **CO5300** |
| 规格标识 | 产品资料中常用 **`1.6-amoled-320x360-qspi-co5300`** 表示本规格 |
| 同尺寸其他规格 | 1.6″ **480×480** 见 **`1.6-amoled-480x480-qspi-ch13613`**（CH13613 QSPI）、**`1.6-amoled-480x480-mipi-st7802`**（ST7802 MIPI），分辨率与驱动不同、独立维护 |

---

## 仓库结构

### 顶层目录

| 路径 | 说明 |
|:--|:--|
| `assets/` | 示例工程 Demo 效果图片（有则放置） |
| `docs/` | 数据手册、规格说明（**待补充**） |
| `examples/` | **示例工程** |

### `examples/` 分类

| 分类 | 说明 |
|:--|:--|
| `examples/` 根目录 | ESP32-S3 + IDF5：CO5300 QSPI + LVGL9 + CST820 触摸 |

### 示例工程路径

| 说明 | 路径 |
|:--|:--|
| CO5300 QSPI bringup（LVGL9） | `examples/esp32s3-1.6-amoled-320x360-qspi-co5300-bringup/` |
