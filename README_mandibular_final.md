
# Mandibular Reconstruction – Comparative Biomechanical Simulation

This repository presents a comparative study on mandibular reconstruction using biomechanical finite element simulation. The analysis investigates different implant configurations and their impact on bone stress distribution and remodeling behavior.

---

## Project Summary

This research includes **three mandibular models**:

1. **Healthy Mandible (No Defect)**  
   → Used as a reference model to evaluate stress and bone remodeling response.

2. **Reconstruction with Two Implants**  
   → Implants placed at positions 12 and 14 in a fibula graft-supported segment.

3. **Reconstruction with Three Implants**  
   → Implants placed at positions 12, 13, and 14, with extended coverage.

All models were subjected to **100 N masticatory loading**, and bone density changes were calculated using a custom UMAT (FORTRAN-based material subroutine) in Abaqus.

---

## Repository Structure

```
ABAQUS/
├── case1_healthy_mandible.inp
├── case2_double_implant.inp
├── case3_triple_implant.inp
FORTRAN/
├── umat_bone_remodeling.f
DOCUMENTS/
├── thesis_summary.pdf
├── figures/
README.md
```

---

## Tools & Methods

- **FEA Software:** Abaqus CAE 2022
- **Coding:** FORTRAN (User-defined UMAT)
- **Modeling & Meshing:** Mimics, CATIA
- **Analysis:** Bone remodeling equations, time-dependent mechanical loading

---

## Research Origin

This project is based on the following Master's Thesis:

> _"Finite Element Modeling and Bone Remodeling Analysis of Mandibular Reconstruction"_  
> M.Sc. in Medical Engineering (Biomechanics)  
> Sahand University of Technology, Iran  
> Author: **Farzaneh Gholamian**

---

## Contact

- Email: gholamian92@gmail.com    
- LinkedIn: [www.linkedin.com/in/farzaneh-gholamian-biomedical-enginee](#)
