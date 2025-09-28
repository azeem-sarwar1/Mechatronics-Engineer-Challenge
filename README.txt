KiCad PCB Design – Evaluation Task

This repository contains the PCB design created as part of the evaluation task using **KiCad**.


## 📌 Task Overview
1. **PCB Creation**
   - Added components:
     - Default KiCad LED symbol with footprint and 3D model is downloaded and modified.
     - Custom symbol + footprint for **TCAN4551-Q1** (VQFN-20 package) and 3D model is download.
     - Default KiCad symbol **MCIMX6D4AVT**.
     - Verified footprints with 3D viewer and picture attached.

2. **Custom Libraries**
   - Created a **custom symbol library** (`TCAN4551-Q1.kicad_sym`).
   - Created a **custom footprint library** (`custom-footprints.pretty/TCAN4551_VQFN20.kicad_mod`).
   - Linked symbol and footprint.

3. **Design Rules**
   - Applied custom microvia design rules for the BGA component:
     - Minimum annular width: **2 mil**
     - Minimum via diameter: **8 mil**
     - Minimum via hole: **4 mil**

4. **Bonus**
   - Library for **TCAN4551-Q1** also stored in a separate repository, which can be mounted as a submodule.

---

## 📂 Repository Structure



This project contains,
2 Schematic sheets
PCB file with 3D models of all components
Custom footprint and symbol library of TCAN4551-Q1
3D Model of LED (Downloaded with some changes)
3D model of TCAN4551-Q1 (Downloaded)

