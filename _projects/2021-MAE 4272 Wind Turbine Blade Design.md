---
layout: project
title: Wind Turbine Blade Design Project
description: Designed, modeled, and wind-tunnel tested a custom NACA-4418 turbine blade to evaluate structural performance and aerodynamic power output.
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/turbine-pic.png
---

## **Project Overview**
For the MAE 4272 Wind Energy Engineering course, our team was tasked with designing, fabricating, and experimentally evaluating a small-scale wind turbine blade suitable for testing in Cornell’s **Big Blue Wind Tunnel**. The goal was to engineer a blade that met realistic aerodynamic performance expectations while remaining structurally sound under operational loads. This project followed an authentic engineering workflow—balancing theory, CAD, simulation, prototyping, and testing—to produce a blade capable of efficiently converting wind energy into mechanical power.

<img src="{{ '/assets/images/cad-model.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **Design Process**
We selected the **NACA 4418 airfoil** because of its high lift at low Reynolds numbers, gentle stall behavior, and suitability for 3D-printed wings. Using MATLAB-based blade element momentum (BEM) calculations, we generated a twist and chord schedule designed to keep local angles of attack near optimal values across the radius.

The blade was then modeled in CAD and structurally evaluated using **ANSYS**, verifying that stresses remained well below yield and that deflection stayed within safe limits during expected load cases. Iterations focused on refining the tip geometry, reducing stress concentrations near the root, and ensuring manufacturability for 3D printing.

<img src="{{ '/assets/images/ansys-pic.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **Testing Summary**
The finalized blade was printed, mounted to the test rig, and evaluated under three controlled wind-speed conditions. At each wind speed, we performed a sequence of brake-torque steps to measure rotational speed and torque, which we used to compute mechanical power output.

The resulting **power curves** showed clear performance differences across wind speeds and closely aligned with our MATLAB predictions. Structural integrity was confirmed throughout testing—no deformation, flutter, or stall behavior occurred at the design wind speed.

<img src="{{ '/assets/images/power-curve.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **My Contribution**
I contributed across design, simulation, and analysis. I helped refine the blade geometry, supported ANSYS structural modeling, assisted with MATLAB power-curve processing, and collected and analyzed wind-tunnel data. I also contributed significantly to documentation and presentation materials, ensuring our engineering decisions and results were communicated clearly and professionally.

---