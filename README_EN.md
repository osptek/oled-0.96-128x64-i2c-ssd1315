<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 0.96″ OLED 128×64 (SSD1315 · I2C)</h1>

<p align="center"><b>Monochrome OLED module · I2C · compact status display</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English</p>

<p align="center">
  <img alt="Size: 0.96 inch" src="https://img.shields.io/badge/Size-0.96%22-3498DB?style=flat-square" />
  <img alt="Resolution: 128x64" src="https://img.shields.io/badge/Resolution-128%C3%9764-8E44AD?style=flat-square" />
  <img alt="Interface: I2C" src="https://img.shields.io/badge/Interface-I2C-27AE60?style=flat-square" />
  <img alt="Driver: SSD1315" src="https://img.shields.io/badge/Driver-SSD1315-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 0.96&quot; OLED 128×64 module (SSD1315) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Sample projects](#sample-projects)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **0.96″ 128×64 OLED** is an **I2C** monochrome display module driven by **SSD1315**. Compact wiring and size suit status bars, menu hints, debug text, and simple animations.

Spec ID (repository name): `0.96-oled-128x64-i2c-ssd1315`

Current module version: **ODM096-12864W009-P4**. Electrical and mechanical details follow [`docs/ODM096-12864W009-P4.pdf`](./docs/ODM096-12864W009-P4.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 0.96 inch |
| Type | OLED (monochrome) |
| Resolution | 128×64 |
| Interface | I2C |
| Driver IC | SSD1315 |

> Full outline, pinout, power, and electrical ratings follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-S3 · SSD1315 I2C bringup (face animation demo) | [`examples/esp32s3-0.96-oled-128x64-i2c-ssd1315-bringup/`](./examples/esp32s3-0.96-oled-128x64-i2c-ssd1315-bringup/) |

## Repository layout

```text
0.96-oled-128x64-i2c-ssd1315/
├── README.md
├── README_EN.md
├── MODULE_VERSION.md
├── LICENSE
├── images/          # README assets
├── docs/            # datasheets
└── examples/        # sample projects
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (ODM096-12864W009-P4) | [`docs/ODM096-12864W009-P4.pdf`](./docs/ODM096-12864W009-P4.pdf) |

### Samples

- [ESP32-S3 SSD1315 I2C bringup](./examples/esp32s3-0.96-oled-128x64-i2c-ssd1315-bringup/)

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group (China): **985881096**
- Website: <https://osptek.com/>
- For questions or problems, you can also open a GitHub [Issue](https://github.com/osptek/0.96-oled-128x64-i2c-ssd1315/issues)

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
