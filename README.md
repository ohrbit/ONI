# ONI 002 Transmutative Mask — Hardware Repository
Powered by **Ohrbit Industries**

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![System: m3z-compatible](https://img.shields.io/badge/System-m3z%20Compatible-blue)](https://github.com/ohrbit/m3z)
[![Method: VibeCoding & Hi3D](https://img.shields.io/badge/Method-VibeCoding%20%2526%20Hi3D-purple)]()

Welcome to the official hardware and development repository for the **ONI 002 Transmutative Mask**. Developed under the Ohrbit Industries Scientific Research Project (Codename: ONI), this project is a fully open-source, multi-material, modular cyber-samurai half-mask engineered for human-machine fusion interface benchmarking, active filtration, and modular sensor integration.

This project is entirely **Open Source (CC BY-SA 4.0)**, allowing you to print, resize, customize, hack, and evolve the design.

---

## ⚡ Quick Specifications

* **Version:** 002 (Base Frame `v0001102-rev3`)
* **Design Framework:** Created using **Hi3D** asset pipelines and optimized via **VibeCoding** iteration loops.
* **Modular Ecosystem:** Native integration with **m3z by ohrbit** (the 3mm modular building and structural connection system).
* **Customizable Nodes:** **30 discrete, independent component parts** for multi-material, multitool, or multicolor configurations.
* **Target Integration:** Neural Link Gen2 Sensory emulation, Tensor Processing Unit (TPU) node housings, and reactive ambient sensory modules.

---

## 🛠️ 3D Printing & Slicing Specifications

The current physical alpha-prototype was successfully sliced and fabricated on an **Elegoo Centum / Neptune series (CC2 setup)** using standard baseline parameters with organic tree/lightning support structures optimized for quick release and minimized surface scarring.

### 📋 Slicer Profile (Elegoo CC2 Baseline)

| Parameter | Configuration Setting | Notes |
| :--- | :--- | :--- |
| **Printer Engine** | Elegoo CC2 / Direct Drive | Baseline hardware profile |
| **Layer Height** | `0.20 mm` | Optimized balance between print speed and mechanical snap-fit tolerances |
| **Infill Density** | `12.4%` | Sparse infill structure (Internal solid infill applied selectively to load-bearing walls) |
| **Infill Pattern** | Gyroid or Grid | Provides uniform structural resilience against torsion |
| **Wall Count** | `3 Loops` (Inner/Outer split) | Ensures rigid perimeter definition for snap-fit joints |
| **Material Usage (Est.)**| **Total Filament:** ~35.41 g (`11.78 m`) <br>**Model Weight:** ~24.20 g (`8.05 m`) | Remaining mass allocated to support structures |
| **Estimated Print Time**| **2 hours 38 minutes** | High-speed structural prototyping speed layout |

### 🌳 Support Strategy (Tree / Lightning Configuration)
Due to the intense cantilever design of the chin plate and the sharp forward projection of the primary tusks, **organic tree supports** are highly recommended.
* **Support Overhang Threshold:** `32°` to `38°`
* **Support Interface:** `22s` layer curing or dense layer interfaces depending on material (PLA/PETG).
* **Placement:** Baseplate-only contact configuration wherever possible to preserve the high-detail surface of the inner and outer lip lines.

---

## 🗂️ The 30 Modular Features & Access Points

The ONI 002 design file is split into exactly **30 component IDs**, allowing for massive multicolor variance, distinct material properties (e.g., rigid structural polymers vs. flexible TPU gaskets), or dedicated electronic component routing:

```
00 Respiratory System Bottom-Right Access Point
01 [ACCESS DENIED / RESERVED]
02 [ACCESS DENIED / RESERVED]
03 [ACCESS DENIED / RESERVED]
04 Upper Lip
05 LED Top-Right Glow Diffuser
06 Bottom Lip
07 LED Top-Left Glow Diffuser
08 Ambient Sensor Right (LED housing, Fussy Automatic AirGate, Sensor channels)
09 Ambient Sensor Left (LED housing, Fussy Automatic AirGate, Deep sensor arrays)
10 Touch Sensor below Bottom-Lip
11 Screw Mount Connector Bottom-Left
12 Ohrbit Communications System Cover Left
13 Screw Mount Connector Bottom-Right
14 Access Point Left
15 Access Point Right
16 Ear Piece Connector Left
17 Central Processing Unit Center Enclosure
18 Respiratory System Bottom-Right Housing
19 Respiratory System Bottom-Left Housing
20 Ohrbit Neuralink Gen2 Sensory System Right Emulation Plate
21 Ohrbit Neuralink Gen2 Structural Connector Right
22 Nose Bridge Left Alignment Notch
23 Tensor Processing Unit (TPU) Multi-Node Housing
24 Hardware Activation Button Base Right
25 Teeth Component Set Bottom-Center
26 Molekular-Teeth System Gen .5c High-Detail Inset
27 Hardware Activation Button Base Left
28 [ACCESS DENIED / RESERVED Right Node]
29 [ACCESS DENIED / RESERVED Left Node]
30 ONI Base Frame v0001102-rev3 (Core Chassis)
```

---

## 🔧 Assembly & m3z Integration

1.  **Chassis Prep:** Clean any residual tree support interfaces from the **Base Frame (ID 30)**.
2.  **Modular Fastening:** All structural screw channels (e.g., **ID 11, ID 13**) are pre-tapped to accept standard **m3z 3mm hardware connection accessories**. Do not over-torque if printed in standard PLA.
3.  **Electronics Integration:** Access channels behind the **Ambient Sensor Gates (IDs 08, 09)** and the **CPU Center (ID 17)** are routed with internal wire-guides to support custom microcontrollers, status LEDs, and active fan micro-gates.

---

## 📄 License & Open Source Attribution

This repository and all included structural models, STL files, and configurations are distributed under the **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** license. 

**You are free to:**
* **Share** — copy and redistribute the material in any medium or format.
* **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

**Under the following terms:**
* **Attribution** — You must give appropriate credit to **Ohrbit Industries**, provide a link to the license, and indicate if changes were made.
* **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

---
*Disclaimer: "Ohrbit Industries Scientific Research Project - Codename ONI" is a futuristic conceptual design ecosystem. Always ensure proper filter materials are utilized if adapting the frame for physical ventilation filters.*
