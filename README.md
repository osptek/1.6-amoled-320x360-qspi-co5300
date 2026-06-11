# 1.6 寸 320×360 AMOLED QSPI 模组（CO5300）资料与示例

**English：** [`README_EN.md`](README_EN.md)

---

> 本仓库提供该模组的 **示例工程**，以及数据手册、规格与接口说明等资料，便于选型参考与集成开发。

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
| `docs/` | 数据手册、规格说明、转接板原理图 |
| `examples/` | 按功能分类的 **示例工程** |

### `examples/` 分类

| 分类 | 说明（对应内部资料目录） |
|:--|:--|
| `examples/` 根目录 | **esp-lvgl-adapter** 的 **LVGL8 / LVGL9** 示例，或 bringup 工程 |
| `with-te/` | **屏幕防撕裂代码** |

### 示例工程路径

#### 基础与 esp-lvgl-adapter

| 说明 | 路径 |
|:--|:--|
| CO5300 QSPI bringup（LVGL9） | `examples/esp32s3-1.6-amoled-320x360-qspi-co5300-bringup/` |
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/` |

#### 屏幕防撕裂代码（`with-te/`）

| 说明 | 路径 |
|:--|:--|
| esp-lvgl-adapter + LVGL8 + AMOLED，含 TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| esp-lvgl-adapter + LVGL9 + AMOLED，含 TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |
