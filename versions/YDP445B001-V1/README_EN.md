<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 4.45″ TFT 480×854 (GC9503CV · MIPI)</h1>

<p align="center"><b>TFT / IPS module · MIPI · GC9503CV</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 4.45 inch" src="https://img.shields.io/badge/Size-4.45%22-3498DB?style=flat-square" />
  <img alt="Resolution: 480x854" src="https://img.shields.io/badge/Resolution-480%C3%97854-8E44AD?style=flat-square" />
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: GC9503CV" src="https://img.shields.io/badge/Driver-GC9503CV-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 4.45″ 480×854 TFT MIPI module (GC9503CV) product image" src="./images/product.png" width="640" /></p>

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

OSPTEK **4.45″ 480×854 TFT / IPS** is a **MIPI** color display module driven by **GC9503CV**. Suited to handheld terminals, portrait instruments, and compact HMI.

Spec ID (repository name): `tft-4.45-480x854-mipi-gc9503`

Current module version: **YDP445B001-V1**. Electrical and mechanical details follow [`docs/YDP445B001-V1.pdf`](./docs/YDP445B001-V1.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 4.45 inch |
| Type | TFT / IPS (color) |
| Resolution | 480×854 |
| Interface | MIPI |
| Driver IC | GC9503CV |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Sample projects

| Description | Path |
| ---- | ---- |
| ESP32-P4 · GC9503 MIPI DSI + LVGL9 | [`examples/esp32p4-idf5_gc9503-mipi_lvgl9/`](./examples/esp32p4-idf5_gc9503-mipi_lvgl9/) |

## Repository layout

```text
tft-4.45-480x854-mipi-gc9503/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP445B001-V1/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        ├── docs/
        └── examples/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP445B001-V1) | [`docs/YDP445B001-V1.pdf`](./docs/YDP445B001-V1.pdf) |
| Driver IC datasheet (GC9503CV) | [`docs/GC_9503_CV_Data_Sheet_V1_0_1_bf6521995e.pdf`](./docs/GC_9503_CV_Data_Sheet_V1_0_1_bf6521995e.pdf) |
| Init sequence (text) | [`docs/GC9503CV+BOE4.45IPS(PV044WVQ-N80)-20220810-karry-V1.txt`](./docs/GC9503CV%2BBOE4.45IPS%28PV044WVQ-N80%29-20220810-karry-V1.txt) |

### Samples

- [ESP32-P4 GC9503 MIPI DSI + LVGL9](./examples/esp32p4-idf5_gc9503-mipi_lvgl9/)

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
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository with any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
