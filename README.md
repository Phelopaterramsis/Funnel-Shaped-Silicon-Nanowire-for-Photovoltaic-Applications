# 🌞 Funnel-Shaped Silicon Nanowire for Photovoltaic Applications  
A simulation-based study on enhancing light absorption in solar cells using funnel-shaped silicon nanowire (SiNW) nanostructures modeled with Lumerical FDTD.

## 📌 Course  
**Optics Final Project – Spring 2024**  
University of Science and Technology at Zewail City  
Supervised by **Dr. Salem Farag Hegazy**  
TAs: Awad Khaled Mohamed, Mohammed Mansour

## 👥 Team  
- **Phelopater Ramsis (202001171)**  
- Mohamed Essam (202000196)

---

## 📘 Project Overview  
This project explores an advanced **surface-texturing nanostructure** aimed at increasing the absorption efficiency of photovoltaic (PV) cells.  
Using **Lumerical ANSYS (FDTD)**, a **funnel-shaped silicon nanowire** was modeled, combining cylindrical and conical sections to maximize:

- Broadband light absorption  
- Light trapping efficiency  
- Reduction in reflection  
- Enhancement of leaky mode resonances  

Traditional cylindrical or conical nanowires offer limited trapping, but the funnel design increases the number of supported resonant modes — resulting in significantly higher absorption across the solar spectrum.

---

## ⚙️ Methods & Simulation Setup

### **1. FDTD Method**  
Maxwell’s equations were solved using the 3D Finite-Difference Time-Domain method, ideal for analyzing electromagnetic interaction with complex nanostructures.

### **2. Geometry**  
Key structural parameters:
- **h₁ (Cylinder height):** 510 nm  
- **h₂ (Cone height):** 1520 nm  
- **d₁ (Top cone diameter):** 220 nm  
- **d₂ (Base cone diameter):** 310 nm  
- **d₃ (Cylinder base diameter):** 400 nm  

### **3. Solar Cell Layering**
- **n-layer:** 340 nm, 10²¹ cm⁻³  
- **Intrinsic layer:** 3390 nm  
- **p-layer:** 600 nm, 5×10¹⁹ cm⁻³  

### **4. Boundary Conditions**
- Periodic boundary conditions (PBCs) in x & y  
- Perfectly matched layers (PML) in z  

---

## 📊 Key Analysis Metrics

### **Absorption Efficiency**  
A(λ) = 1 − R(λ) − T(λ)  
Evaluates how much incident light becomes absorbed.

### **Ultimate Efficiency (η)**  
Calculated via spectrum-weighted absorption.

### **Short-Circuit Current Density (Jsc)**  
A main indicator of photovoltaic performance.

---

## 📈 Results Summary

### **Enhanced Light Trapping**  
The funnel geometry significantly increases:
- Leaky mode resonances  
- Light–matter interaction  
- Broadband absorption  

### **Spectral Analysis**
Simulation graphs showed:
- **Low reflection** across broad wavelengths  
- **Controlled transmission**  
- **Strong absorption peaks** tied to the funnel geometry  

### **IV & PV Curves**  
Simulation outputs demonstrate strong photovoltaic performance.

### **Performance Metrics**
Achieved values from the simulations:
- **Short-Circuit Current (Jsc):** 15.00 mA/cm²  
- **Open-Circuit Voltage (Voc):** 0.72 V  
- **Maximum Power (Pmax):** 17.89 mW/cm²  
- **Fill Factor (FF):** 1.66  
- **Efficiency:** **17.89%**

These values indicate excellent light-trapping and conversion efficiency for the designed nanostructure.

---

## 🧩 Files in This Folder  
- **Phelopater-MohamedOptics Final Project.pdf** – full simulation report and results  
- **README.md** (this file)

---

## 📎 Conclusion  
The funnel-shaped SiNW demonstrates substantial improvement in the optical and electrical performance of PV devices. By enhancing absorption, reducing reflection, and promoting resonant trapping, this design presents a promising pathway for next-generation high-efficiency solar cells.

