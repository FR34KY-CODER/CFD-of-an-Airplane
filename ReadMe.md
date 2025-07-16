# ✈️ CFD Analysis of Aircraft Model using ANSYS Fluent and SolidWorks

## 📌 Overview

This project involves the **Computational Fluid Dynamics (CFD)** analysis of a **custom-designed aircraft geometry** created in **SolidWorks**, imported into **ANSYS Fluent** via STL format. The goal was to study **aerodynamic behavior** including **pressure distribution, lift, and drag forces** under turbulent flow conditions.

> ✅ Tools Used: SolidWorks | ANSYS Fluent | CFD Post | Meshing Tools  
> ✅ Skills Involved: CAD Design, Meshing, Boundary Condition Setup, Flow Simulation, Turbulent Modeling

---

## 🛠️ Project Workflow

### 1. 3D CAD Modeling – SolidWorks

- Designed a simplified fixed-wing aircraft model using SolidWorks surface and solid modeling tools.
- Exported the final geometry as `.STL` for compatibility with Fluent preprocessing.

---

### 2. Preprocessing & Meshing – ANSYS Meshing

- Imported the STL model into ANSYS Fluent Mesher.
- Generated **unstructured tetrahedral mesh**, with inflation layers near the surface to capture boundary layer effects.
- Mesh quality was refined based on **skewness** and **orthogonality** metrics.

---

### 3. Solver Setup – ANSYS Fluent

- Flow Type: **Steady, Incompressible Turbulent Flow (k-ε Model)**
- Boundary Conditions:
  - **Inlet:** Velocity Inlet
  - **Outlet:** Pressure Outlet
  - **Aircraft Body:** No-slip wall
- Air properties were set to standard sea-level conditions.

---

### 4. Results & Postprocessing

- Visualized **velocity streamlines**, **pressure contours**, and **wall shear stress** on aircraft surfaces.
- Calculated **lift and drag coefficients**, and observed flow separation zones on the tail and wing edges.

---

## 📈 Key Outcomes

- Understood aerodynamic behavior of custom aircraft geometry under ideal flow conditions.
- Demonstrated proficiency in **CAD-to-CFD workflows**, meshing practices, and **turbulence modeling**.
- Strengthened knowledge of fluid behavior around **aero surfaces** with curvature and fuselage taper.

---

## 👨‍💻 Author

**Ojasvi Goyal**  
B.Tech – Mechanical Engineering  
LNMIIT Jaipur  

