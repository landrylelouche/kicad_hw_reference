# 🤝 Contributing to the KiCad Hardware Blocks Project

Thank you for your interest in contributing to this open-source repository!

## 🧭 Purpose

This repository aims to gather reusable and modular electronic design blocks (MCUs, sensors, SOMs, actuators, etc.) created using KiCad EDA. Every contribution strengthens the open hardware ecosystem.

---

## ✅ What You Can Contribute

- New complete design blocks (schematic + PCB)
- Enhancements to existing blocks
- Documentation (README, datasheets, integration guides)
- Bug fixes in source files
- Useful scripts or automation tools

---

## 🛠️ Expected Block Structure

Each block must be placed in a `blocks/BLOCK_NAME/` folder and include:

- `schematic.kicad_sch`
- `layout.kicad_pcb`
- `bom.csv` (with manufacturer references)
- `doc/README.md` (overview, pinout, integration notes)
- (optional) `outputs/` (Gerber/Drill files)

---

## 📌 Basic Rules

- Use **KiCad 7.x or higher**
- Prefer **widely available components**
- Follow the folder structure
- Document technical choices in `README.md`
- Make a clear Pull Request with an explicit title

---

## 🧪 Test Before Submitting

Before submitting your contribution:
- Open `.kicad_sch` and `.kicad_pcb` files without errors
- Fix all DRC/Electrical Rule violations
- Check spelling and clarity in documentation

---

## 📝 How to Contribute

1. Fork this repository
2. Create a new branch with a clear name (`feature/new-sensor-block`)
3. Commit your files with meaningful messages
4. Open a **Pull Request** to the `main` branch

Thank you for building open hardware with us! 💪
