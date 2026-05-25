# 1.6" 320×360 AMOLED QSPI module (CO5300) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides an **ESP-IDF sample project**. Datasheets and specifications will be added to `docs/` when available.

## Product overview

| Item | Description |
|:--|:--|
| Module | 1.6-inch **AMOLED** panel, **320×360** resolution |
| Interface | **QSPI** |
| Driver IC | **CO5300** |
| Spec ID | **`1.6-amoled-320x360-qspi-co5300`** is the common product designation in documentation |
| Other 1.6″ variants | **480×480** modules: **`1.6-amoled-480x480-qspi-ch13613`** (CH13613 QSPI), **`1.6-amoled-480x480-mipi-st7802`** (ST7802 MIPI) — separate repos |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `assets/` | Demo screenshots for sample projects (when available) |
| `docs/` | Datasheets and specifications (**to be added**) |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description |
|:--|:--|
| `examples/` root | ESP32-S3 + IDF5: CO5300 QSPI + LVGL9 + CST820 touch |

### Sample project paths

| Description | Path |
|:--|:--|
| CO5300 QSPI bringup (LVGL9) | `examples/esp32s3-1.6-amoled-320x360-qspi-co5300-bringup/` |
