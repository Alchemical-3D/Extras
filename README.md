<div align="center">

# 🧊 Alchemical 20mm Calibration Cube (`Extras`)

[![Status](https://img.shields.io/badge/Status-Active-FF3985.svg?labelColor=1E1E24)](#)
[![Category](https://img.shields.io/badge/Category-Calibration-595959.svg?labelColor=1E1E24)](#)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-Alchemical--3D-FF3985.svg?labelColor=1E1E24)](#)
[![Printables](https://img.shields.io/badge/Printables-Model%20%23318865-FA6831.svg?labelColor=1E1E24)](https://www.printables.com/model/318865-alchemical_20mm_cube)

*A detailed, multi-purpose `20mm` calibration cube for evaluating overall 3D printer tuning before printing tight-tolerance Alchemical-3D hardware.*

**[View on Printables](https://www.printables.com/model/318865-alchemical_20mm_cube)** &nbsp;•&nbsp; **[Join the Discord](https://discord.gg/aE49DW2xXe)**

</div>

<br>

---

## 🎯 Overview

Inspired by the **Voron** Calibration Cube, the **Alchemical 20mm Calibration Cube** (`20.00 × 20.00 × 20.00 mm`) goes beyond a basic single-purpose XYZ block to give you a fast snapshot of your printer and filament profile in one print:

- **Dimensional Accuracy:** Verify X, Y, and Z outer dimensions against the `20.00 mm` nominal cube envelope.
- **Overhangs:** Inspect surface quality on angled overhangs.
- **Bridging:** Check span cleanliness across unsupported horizontal bridges.
- **Pressure Advance:** Evaluate corner crispness and seam/extrusion transitions.
- **Circular Accuracy:** Check roundness on curved/cylindrical test features.

---

## 📦 Included STL Files

| File | Outer Envelope (`X × Y × Z`) | Solid Volume | Notes |
| :--- | :---: | :---: | :--- |
| `Alch_Cube_20mm_V4.stl` | `20.00 × 20.00 × 20.00 mm` | `4.40 cm³` | Calibration cube mesh (`V4`) |
| `Alchemical_20mm_Cube.stl` | `20.00 × 20.00 × 20.00 mm` | `4.35 cm³` | Calibration cube mesh ([Printables #318865](https://www.printables.com/model/318865-alchemical_20mm_cube)) |

---

## 📏 Dimensional & Shrinkage Verification

High-temperature polymers such as **ABS**, **ASA**, and **PC** contract as they cool. Dialing flow and shrinkage before starting structural builds ensures bearings, O-ring grooves, and heat-set insert bores fit cleanly:

1. Slice and print the calibration cube using the exact filament, chamber temperature, and `Print_Settings.md` profile intended for your build.
2. Let the part cool to room temperature, then measure the **X**, **Y**, and **Z** faces with calipers (avoiding first-layer elephant's foot).
3. Compute the per-axis slicer scale multiplier as `scale_factor = 20.00 / measured_mm`, and apply that compensation in your slicer's shrinkage / XY-Z scaling settings before printing functional parts.

---

## 🔗 Companion Alchemical-3D Hardware

- **[Alembic Toolhead](https://github.com/Alchemical-3D/Alembic_Toolhead)** — Ultra-lightweight remote-air CoreXY toolhead with tight-tolerance pneumatic seals and tube seats.
- **[Pneuma Part Cooling](https://github.com/Alchemical-3D/Pneuma_Remote_Air)** — Stationary dual-pump pneumatic air supply.
- **[A3DP Gantry Assembly](https://github.com/Alchemical-3D/A3DP_Gantry_Assembly)** — Milled-aluminum CoreXY gantry kit.
- **[Pestle Rotational Bowden](https://github.com/Alchemical-3D/Pestle_Rotational_Bowden)** — Swiveling gantry-mounted Bowden extruder.

---

## ⚖️ License

Licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** per the [Printables Model #318865](https://www.printables.com/model/318865-alchemical_20mm_cube) release.

***

> ☕ **Did you find this helpful?**
>
> My projects are open-source and free for the community. If you've enjoyed my designs and want to support my work, consider [leaving me a tip on Ko-fi](https://ko-fi.com/alchemical3d)!
>
> [![Ko-Fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/alchemical3d)

***
*Documentation prepared with AI editorial assistance • Engineered & maintained by Alchemical-3D.*
