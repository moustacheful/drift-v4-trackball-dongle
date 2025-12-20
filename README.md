# Drift Keyboard V4 — Trackball Edition  
by **Timception**

Welcome to the **Drift Keyboard V4 — Trackball Edition**.  
This version keeps the familiar shape of previous Drift models while introducing some interesting additional features:

<p align="center"><img src="img/DriftV4.jpg" width="500"></p><br/><br/>  

---

## 🆕 Key Features

- ZMK Studio enabled, and can also be keymapped using [Nick Coutsos' Editor](https://github.com/nickcoutsos/keymap-editor)  
- Connects through a **dongle** for improved wireless functionality  
- Adds a **newly integrated trackball** - One less device to carry. Enjoy full cursor control without the need for a separate mouse.  
- Can install sockets for **choc v1/v2 switches**

---

## 🔢 Key Count & Layout

- **63 keys** total  
- Only **5 keys fewer** than the 68-key Drift V2/V3  
- Removed the **outermost columns**, but the layout still provides everything needed to easily migrate from conventioal 60%-65% keyboards.  
- The **encoder** is now placed on the **thumb cluster**  
- The **right half** features a **swappable trackball**, allowing you to try different materials or replace the trackball module.

If you’ve used the Drift V2 or V3 before, you’ll adapt to this version very quickly.  
The trackball has been smoothly integrated and is not hard to get used to.  

---

## 🛠️ Design Notes

This model took extensive time and refinement to bring together, and I can easily call it my Masterpiece.

- The **OLEDs were removed** to avoid signal interference with the MCU underneath  
- **4-pin OLED sockets remain**, so users can reinstall displays and make firmware changes if desired  
- Designed with **maximum modding potential** in mind, and all the case parts can be 3D-Printed so even more colors

---

## ⚙️ Build Options

The V4 supports multiple build configurations:

- **MX switch** builds  
- **Choc V1/V2 low-profile** builds  
- Many possibilities for **multiple case designs**, I made many parts for this, and hope to keep making more!  

---

## 🧭 Trackball Behavior & Controls

### ✅ How the Trackball Behaves

#### 🛑 While You're Typing
- The **trackball is disabled while you type**.
- It automatically re-enables **0.5 seconds after the keyboard stops receiving key presses**.

#### 🖱️ While You’re Using the Trackball
- When you move the trackball, the **right half switches to mouse-only mode**.
- This means you **can’t type** on the right side until:
  - You stop moving the trackball for **~1.2 seconds**, **then** the keyboard returns to normal typing mode.
- This function prevents accidental mouse activation while typing and vice versa.

---

### 🔒 Permanent Mouse Mode (Optional)
If you want the right half to stay in mouse mode:

- **Hold `Raise` + press `6`**  
  → Mouse mode stays locked on.
- To exit, **Hold `Raise` + press `6` again**  
  → Returns to normal keyboard operation.

---

### 🎯 Mouse Controls (When Mouse Mode Is Active)

| Action | Key |
|--------|------|
| **Left Click** | `K` |
| **Right Click** | `L` |
| **Scroll** | Hold `O` + move the trackball |

---

### 🎥 Extra 3D Navigation Functions (Optional)
For users working in **3D programs**, Drift V4 includes two special macros while the mouse layer is active:

#### 🌀 Orbit
- **Key:** `.` (period)
- **Function:** Holds **Shift + Middle Click** while the trackball moves  
- **Usage:** Rotate/orbit around models and objects

#### 📐 Pan
- **Key:** `,` (comma)
- **Function:** Holds **Middle Click** while the trackball moves  
- **Usage:** Pan the view horizontally/vertically in 3D space  

---

### ⚙️ Customizing Trackball Behavior
If you want to customize how the trackball or mouse keys work, you’ll need to update your firmware:

- Edit your fork on GitHub  
- Recompile the firmware  
- Flash **all three devices**: left half, right half, and dongle  

---


- This keyboard was developed alongside Drift Keyboard V3, though it was not released at the same time.  
- Its design is original, and is not derived from any existing keyboard other than the original Drift Keyboard.  

You can see more actual builds [-=HERE=-](https://www.instagram.com/majin.keyboards)  

# Keymap

![Keymap](https://github.com/Timception/drift-v4-trackball-dongle/blob/main/keymap-drawer/drift.svg)  

## Acknowledgments  

This project makes use of code and ideas from the following repositories:
- [ZMK Firmware](https://github.com/zmkfirmware) (MIT License) - Zephyr™ Mechanical Keyboard (ZMK) Firmware  
- [ufan/zmk](https://github.com/ufan/zmk) (MIT License) – Original ZMK base and PMW3610 work  
- [badjeff/zmk-pmw3610-driver](https://github.com/badjeff/zmk-pmw3610-driver) – PMW3610 driver work, based on ufan’s code  
- [badjeff/zmk-behavior-key-press-lip](https://github.com/badjeff/zmk-behavior-key-press-lip) - LIP Key Press Behavior
- [leafflat/sai44](https://github.com/leafflat/sai44) (MIT License) – Dongle code reference  
- [nuovotaka/zmk-pointing-acceleration-alpha](https://github.com/nuovotaka/zmk-pointing-acceleration-alpha) (MIT License) – Pointer acceleration  
- [caksoylar](https://github.com/caksoylar/keymap-drawer) (MIT License) - Keymap Drawer  

All third-party code remains under their original licenses.  






