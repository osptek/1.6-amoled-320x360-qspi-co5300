# 1.6" 320×360 AMOLED QSPI module (CO5300) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides **sample projects**, datasheets, specifications, and interface documentation for integration and evaluation.

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
| `docs/` | Datasheets, specifications, adapter-board schematics |
| `examples/` | **Sample projects** by category |

### `examples/` layout

| Location | Description (internal folder name) |
|:--|:--|
| `examples/` root | **esp-lvgl-adapter** **LVGL8 / LVGL9** samples, or bringup project |
| `with-te/` | **屏幕防撕裂代码** (tear-free / TE-aware samples) |

### Sample project paths

#### Baseline & esp-lvgl-adapter

| Description | Path |
|:--|:--|
| CO5300 QSPI bringup (LVGL9) | `examples/esp32s3-1.6-amoled-320x360-qspi-co5300-bringup/` |
| esp-lvgl-adapter + LVGL8 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8/` |
| esp-lvgl-adapter + LVGL9 | `examples/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9/` |

#### Tear-free samples (`with-te/`)

| Description | Path |
|:--|:--|
| esp-lvgl-adapter + LVGL8 + AMOLED, with TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl8_amoled-with-te/` |
| esp-lvgl-adapter + LVGL9 + AMOLED, with TE | `examples/with-te/esp32s3-idf5_co5300-qspi_esp-lvgl-adapter_lvgl9_amoled-with-te/` |
