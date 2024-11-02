# KonaBess GRANULATED

[![Android CI](https://github.com/peternmuller/KonaBess-Granulated/actions/workflows/android.yml/badge.svg)](https://github.com/peternmuller/KonaBess-Granulated/actions/workflows/android.yml)
[![GitHub License](https://img.shields.io/github/license/peternmuller/KonaBess-Granulated?logo=gnu&label=License&link=https%3A%2F%2Fgithub.com%2Fpeternmuller%2FKonaBess-Granulated)](https://github.com/peternmuller/KonaBess-Granulated/blob/master/LICENSE)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/peternmuller/KonaBess-Granulated/total?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0Ij48cGF0aCBkPSJNNC43NSAxNy4yNWEuNzUuNzUgMCAwIDEgLjc1Ljc1djIuMjVjMCAuMTM4LjExMi4yNS4yNS4yNWgxMi41YS4yNS4yNSAwIDAgMCAuMjUtLjI1VjE4YS43NS43NSAwIDAgMSAxLjUgMHYyLjI1QTEuNzUgMS43NSAwIDAgMSAxOC4yNSAyMkg1Ljc1QTEuNzUgMS43NSAwIDAgMSA0IDIwLjI1VjE4YS43NS43NSAwIDAgMSAuNzUtLjc1WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjxwYXRoIGQ9Ik01LjIyIDkuOTdhLjc0OS43NDkgMCAwIDEgMS4wNiAwbDQuOTcgNC45NjlWMi43NWEuNzUuNzUgMCAwIDEgMS41IDB2MTIuMTg5bDQuOTctNC45NjlhLjc0OS43NDkgMCAxIDEgMS4wNiAxLjA2bC02LjI1IDYuMjVhLjc0OS43NDkgMCAwIDEtMS4wNiAwbC02LjI1LTYuMjVhLjc0OS43NDkgMCAwIDEgMC0xLjA2WiIgZmlsbD0iI0ZGRkZGRiI+PC9wYXRoPjwvc3ZnPg==&label=Downloads&link=https%3A%2F%2Fgithub.com%2Fpeternmuller%2FKonaBess-Granulated%2Freleases)](https://github.com/peternmuller/KonaBess-Granulated/releases)

### Supported Devices

* Snapdragon 6 series:
  * Snapdragon 690

* Snapdragon 7 series:
  * Snapdragon 750
  * Snapdragon 765
  * Snapdragon 778G
  * Snapdragon 780G
  * Snapdragon 7 Gen 1
  * Snapdragon 7+ Gen 2
  * Snapdragon 7+ Gen 3

* Snapdragon 8 series:
  * Snapdragon 855
  * Snapdragon 865
  * Snapdragon 888
  * Snapdragon 8 Gen 1
  * Snapdragon 8+ Gen 1
  * Snapdragon 8 Gen 2
  * Snapdragon 8 Gen 3
  * Snapdragon 8s Gen 3

### Overview

KonaBess GRANULATED is a straightforward application designed to customize GPU frequency and voltage tables without the need for kernel recompilation.

### Why "GRANULATED" ?

In the [original KonaBess](https://github.com/libxzr/KonaBess), only Qualcomm's predefined steps can be set, which means that voltage tuning is restricted to a limited set of predefined levels, which are:

`RETENTION`, `MIN_SVS`, `LOW_SVS_D1`, `LOW_SVS`, `LOW_SVS_L1`, `LOW_SVS_L2`, `SVS`, `SVS_L0`, `SVS_L1`, `SVS_L2`, `NOM`, `NOM_L1`, `NOM_L2`, `NOM_L3`, `TURBO`, `TURBO_L0`, `TURBO_L1`, `TURBO_L2`, `SUPER_TURBO`, `SUPER_TURBO_NO_CPR`

KonaBess GRANULATED, on the other hand, breaks away from this limitation. It allows users to fine-tune voltages over a much wider and more precise spectrum, from 1 to 480. This is akin to making the voltage control more granular, hence the name "granulated."

By enabling such precise adjustments, it gives users the ability to optimize their GPU's performance and power consumption much more effectively.

### How it Operates

The application achieves customization by unpacking the Boot/Vendor Boot image, decompiling and editing relevant dtb (device tree binary) files, and finally repacking and flashing the modified image.

### Usage Instructions

Refer to the "help" section for detailed instructions on usage.

### Why "KonaBess"?

- The name "Kona" corresponds to the code name of the Snapdragon 865 series.
- Given that the GPU of the Snapdragon 888 exhibits a decrease in energy efficiency, KonaBess allows users to overclock the Snapdragon 865 and surpass the performance of the Snapdragon 888. This is the motivation behind the app's creation.
- Despite the compatibility with Snapdragon 888, the app retains its original name.

### Performance Enhancement

The extent of improvement varies, with some users reporting a 25% reduction in power consumption in the graphics benchmark (4.2w->3.2w) after undervolting the Snapdragon 865. Actual improvement is chip-specific and contingent on stability requirements.

### Prebuilt Binaries

- [magiskboot](https://github.com/topjohnwu/Magisk)
- [dtc](https://github.com/xzr467706992/dtc-aosp/tree/standalone)

### Screenshots

<img src="https://raw.githubusercontent.com/peternmuller/KonaBess-Granulated/master/screenshots/ss1.jpg" width="180" height="400"> <img src="https://raw.githubusercontent.com/peternmuller/KonaBess-Granulated/master/screenshots/ss2.jpg" width="180" height="400"> <img src="https://raw.githubusercontent.com/peternmuller/KonaBess-Granulated/master/screenshots/ss3.jpg" width="180" height="400">
