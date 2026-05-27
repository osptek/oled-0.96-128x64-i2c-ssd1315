# 0.96" 128×64 OLED I2C module (SSD1315) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides an **ESP-IDF sample project**. Datasheets and specifications will be added to `docs/` when available.

## Product overview

| Item | Description |
|:--|:--|
| Module | 0.96-inch **OLED** (monochrome), **128×64** resolution |
| Interface | **I2C** |
| Driver IC | **SSD1315** |
| Spec ID | **`0.96-oled-128x64-i2c-ssd1315`** is the common product designation in documentation |
| Related size | **0.95″ AMOLED SPI** is in **`0.95-amoled-120x240-spi-sh8501`** — different panel and interface |

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
| `examples/` root | ESP32-S3 bringup: SSD1315 I2C display and face animation demo |

### Sample project paths

| Description | Path |
|:--|:--|
| SSD1315 I2C bringup | `examples/esp32s3-0.96-oled-128x64-i2c-ssd1315-bringup/` |
