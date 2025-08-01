# 🔩 Hydraulic Cylinder Selection and Design

This project focuses on the selection, verification, and redesign of a **double-acting hydraulic cylinder** based on given performance requirements. It includes catalog-based selection, engineering checks for stress and buckling, wall and cap dimensioning, and full seal replacement from SKF industrial seal offerings.

---

## 📁 Contents

- `Hydraulic_Cylinder_Selection_and_Design.pdf`  
  The full design report covering:
  - Problem statement and design objectives
  - Cylinder and rod dimensioning
  - Buckling and wall thickness checks
  - Cylinder cap strength verification
  - Seal and guide ring selection from SKF catalog
  - Safety factors and material justification

---

## ⚙️ Design Inputs

- **Working Pressure**: 10 MPa  
- **Bore Diameter**: 125 mm  
- **Stroke**: 150 mm  
- **Rod Diameter**: 90 mm (from selected model)

---

## 🔍 Cylinder Selection

Selected from **Rexroth Bosch catalog**:

- **Model**: `CDT3/MS2/125/90/150F1X/B11HHDMWW`  
- Features: 125 mm bore, 150 mm stroke, 90 mm rod, double-acting cylinder

---

## 🧮 Key Calculations

| Feature                  | Result                           | Verified? |
|--------------------------|----------------------------------|-----------|
| Minimum Rod Diameter     | 88.4 mm                          | ✅         |
| Required Wall Thickness  | 7.74 mm (actual: 17.5 mm)        | ✅         |
| Buckling Safety Factor   | Z = 162                          | ✅         |
| Cap Thickness Check      | h_min = 0.02 mm (satisfied)      | ✅         |

---

## 🧪 Seal Selection

All seals selected from **SKF industrial seals catalog**:

- O-rings  
- Piston seal  
- Rod seal  
- Piston guide rings  
- Rod guide ring  
- Wiper seal  

---

## 🧰 Materials Used

| Component        | Material | Yield Strength |
|------------------|----------|----------------|
| Cylinder Tube    | C35E     | 300 MPa        |
| Piston Rod       | C45E     | 370 MPa        |
| Cylinder Caps    | St52     | 355 MPa        |

---

## 📌 Author Info

**Name**: Saif-Aldain Aqel  
**University**: BME – Mechanical Engineering Department  
**Date**: 2023

---

## 📚 References

1. Design aid material  
2. Rexroth Bosch hydraulic cylinder catalog  
3. SKF Industrial Seals  
   https://www.skf.com/group/products/industrial-seals

---
