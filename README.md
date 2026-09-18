# Advanced Projectile Motion Simulator

An interactive, web-based physics engine built to visualize trajectory dynamics with high accuracy. Most online physics calculators stick to idealized, vacuum-based trajectories that ignore real-world. This simulator changes that by modeling complex fluid dynamics, environmental factors, and planetary physics directly in interactive 2D and 3D space.

---

## Key Features

* **Interactive Launch Parameters:** Fine-tune initial velocity, launch angle, mass, starting height, and local gravitational acceleration using responsive sliders and input fields.
* **Aerodynamic Drag & Lift:** Model true atmospheric conditions by tweaking drag coefficients ($C_d$), lift forces, projectile spin rates and ambient air density.
* **Projectile Customization:** Switch seamlessly between primitive geometries (Sphere, Cube, Pyramid, Cylinder), custom colors, and styled trajectory paths (continuous lines, dashed lines, or points).
* **Environmental & Wind Controls:** Simulate directional wind vectors across $360^\circ$, adjust wind velocity, and toggle atmospheric visual effects like rain, snow, and fog density.
* **3D Visual Engine:** Toggle between Perspective and Top-View cameras in a fully interactive 3D viewport to inspect launch arcs from any angle.
* **Planetary Physics Comparison:** Test launches under real celestial conditions. Compare trajectories across Earth, the Moon, Mars, Venus, Jupiter, or define custom gravitational constants.
* **Data Logging & Export:** Monitor live kinematics (kinetic energy, current height, time to peak, max range) and export raw simulation datasets as structured JSON or CSV files for post-analysis.

---

## Technical Overview

The simulator computes kinematic updates frame-by-frame by resolving force vectors acting on the projected mass. 

### Drag Force Equation
$$F_d = \frac{1}{2} \cdot \rho \cdot v^2 \cdot C_d \cdot A$$

Where:
* $\rho$ = Air Density ($\text{kg/m}^3$)
* $v$ = Velocity relative to wind ($\text{m/s}$)
* $C_d$ = Drag Coefficient
* $A$ = Cross-sectional area (calculated from projectile shape)

---

## Quick Setup

You can download the app or use the html file with your browser.
https://drive.google.com/drive/folders/1T17M-UJvC-uhkFsvbCa3UMQb3TdWaF1n

---
Running Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/bekamregasa-droid/Projectile-Simulator.git](https://github.com/bekamregasa-droid/Projectile-Simulator.git)
