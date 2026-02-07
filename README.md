# SOLIDWORKS FLOW SIMULATION

# CFD Analysis of Hot–Cold Water Mixing in a T-Junction Duct  

## 📖 1. Introduction

Efficient fluid flow through ducting systems is essential in many engineering fields such as:

- HVAC systems  
- Thermal management of equipment  
- Chemical processing  
- Fluid transport networks  

This project presents a **numerical Computational Fluid Dynamics (CFD) study** of internal duct flow in a **T-junction mixing configuration**, where **hot water** and **cold water** enter through two separate inlets, mix inside the junction, and exit through a single outlet. All simulations were performed using **SolidWorks Flow Simulation**.

---

## 🛠️ 2. Software & Tools

- **Software**: SolidWorks  
- **Module**: SolidWorks Flow Simulation  
- **Analysis Type**: Internal flow (ducted flow with heat transfer)

SolidWorks Flow Simulation was chosen for its excellent CAD integration, ease of use, and reliable engineering-level CFD capabilities.

---

## 🏗️ 3. Model Description

The geometry consists of a **T-junction mixing duct** with:

- Two inlet ducts (hot fluid + cold fluid)  
- One outlet duct (mixed fluid)  
- Internal flow with **coupled thermal–fluid mixing behavior**

The model represents a typical **hot–cold fluid mixing junction** used in thermal control and fluid distribution systems.

---

## 🎯 4. Objectives of the Simulation

1. Analyze mixing behavior of hot and cold water streams  
2. Study outlet temperature distribution after mixing  
3. Evaluate velocity and pressure variations  
4. Assess effect of thermal mixing on fluid density  
5. Identify recirculation zones or flow disturbances  
6. Demonstrate capability of SolidWorks Flow Simulation for thermal-fluid problems

---

## ❓ 5. Study Questions

1. How do hot and cold inlet streams interact at the T-junction?  
2. What is the resulting temperature distribution at the outlet?  
3. How does velocity change due to flow mixing?  
4. What pressure variations occur across the junction?  
5. Are there recirculation zones or thermal stratification?  
6. How can mixing efficiency be improved through design changes?

---

## 📊 6. Measured Quantities

The simulation tracked the following parameters:

- Velocity (m/s)  
- Pressure (Pa)  
- Relative Pressure (Pa)  
- Temperature (°C)  
- Fluid Temperature (°C)  
- Fluid Density (kg/m³)  
- Vorticity (1/s)  
- Shear Stress (Pa)  
- Total Enthalpy Flux (W/m²)

---

## 📈 7. Results

### 7.1 Min / Max Values Table

| Parameter                     | Minimum          | Maximum         |
|-------------------------------|------------------|-----------------|
| Density (Fluid) [kg/m³]       | 958.22           | 1000.63         |
| Pressure [Pa]                 | 101317.01        | 101331.59       |
| Temperature [°C]              | 4.82             | 101.08          |
| Temperature (Fluid) [°C]      | 4.82             | 101.08          |
| Velocity [m/s]                | 0                | **0.139**       |
| Velocity (X) [m/s]            | -0.121           | 0.125           |
| Velocity (Y) [m/s]            | -0.066           | 0.069           |
| Velocity (Z) [m/s]            | -0.032           | 0.135           |
| Vorticity [1/s]               | 8.89 × 10⁻²⁷     | **14.97**       |
| Relative Pressure [Pa]        | -7.99            | 6.59            |
| Shear Stress [Pa]             | 0                | 0.38            |
| Total Enthalpy Flux [W/m²]    | -1.553 × 10⁸     | 6.952 × 10⁷     |

### 7.2 Graphical Outputs

![PipeCFD0](PipeCFD0.png)

![PipeCFD1](PipeCFD1.png)

![PipeCFD2](PipeCFD2.png)

![PipeCFD3](PipeCFD3.png)

![PipeCFD4](PipeCFD4.png)

![PipeCFD5](PipeCFD5.png)

# Download CFD Analysis PDF

[⬇️ Download PDF](pdf/CFD%20Analysis%20of%20Hot%E2%80%93Cold%20Water%20Mixing%20in%20a%20T-Junction%20Duct%20Using%20SolidWorks%20Flow%20Simulation.pdf)

---

## 🧠 8. Discussion

- **Low-velocity regime** — max velocity only **0.139 m/s**  
- Very small pressure variation → **stable flow**, low pressure losses  
- Wide temperature range (≈5 °C → 101 °C) confirms **effective thermal mixing**  
- Density variation follows temperature change (temperature-dependent density)  
- Increased **vorticity** near junction → localized mixing & flow interaction  
- Low shear stress values → flow remains stable

---

## 🔍 9. Interpretation & Engineering Significance

| Aspect                        | Observation / Result                              | Engineering Meaning / Significance                                                                                   |
|-------------------------------|----------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Temperature Results**       | Wide range: 4.82 °C – 101.08 °C                   | Indicates strong thermal mixing. Outlet temperature converges toward intermediate value → effective mixing performance |
| **Velocity & Flow Behavior**  | Maximum velocity only 0.139 m/s                   | Low-speed regime typical for controlled mixing systems where high turbulence is undesirable                             |
| **Pressure & Energy**         | Minimal pressure variation (very low drop)        | Energy-efficient design → lower pumping power required, reduced operational energy cost                               |
| **Density Variation**         | 958.22 – 1000.63 kg/m³ (temperature-dependent)    | Confirms importance of using temperature-dependent fluid properties in CFD simulations                                 |
| **Vorticity & Mixing**        | Increased vorticity near the T-junction           | Localized rotational structures enhance mixing without causing excessive turbulence or flow instability               |
| **Shear Stress**              | Very low values (max 0.38 Pa)                     | Flow remains stable and well within safe operating limits for most ducting applications                               |
| **Overall Design Performance**| Stable flow, effective mixing, minimal losses     | T-junction geometry performs well for hot–cold water blending → good baseline for real-world applications             |
| **Limitations**               | Steady-state only, low velocities, no turbulence model comparison | Transient behavior, higher flow rates, and experimental validation recommended for future work                        |

### Limitations  
- Steady-state analysis only  
- Low flow velocities  
- No turbulence model comparison  
- No experimental validation performed

---

## ✅ 10. Conclusion

This study successfully demonstrated **SolidWorks Flow Simulation** for analyzing **hot–cold water mixing** in a T-junction duct.

**Key takeaways:**

- Stable and efficient flow behavior  
- Very low pressure losses  
- Effective thermal mixing  
- Clear coupling between temperature and density  
- CFD provides valuable insight difficult to obtain experimentally

---

## 🏭 11. Industrial Applications

- **HVAC systems** — mixing and distribution ducts  
- **Power plants** — cooling water systems  
- **Chemical & process industries** — fluid routing & blending  
- **Automotive** — air intake / exhaust duct design  
- **Electronics cooling** — airflow and thermal management

---

## 🚀 12. Future Work & Recommendations

- Transient (time-dependent) mixing analysis  
- Turbulent flow simulations (higher velocities)  
- Geometry optimization for better mixing / lower pressure loss  
- Comparison with different turbulence models  
- Experimental validation of CFD results  
- Parametric study (inlet temperatures, flow rates, junction angles)

---
