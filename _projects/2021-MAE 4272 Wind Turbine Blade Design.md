---
layout: project
title: Wind Turbine Blade Design Project
description: Designed, modeled, and wind-tunnel tested a custom NACA-4418 turbine blade to evaluate structural performance and aerodynamic power output.
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/turbine-pic.png
---


Project Overview: For the MAE 4272 Wind Energy Engineering course, our team was tasked with designing, fabricating, and experimentally evaluating a small-scale wind turbine blade suitable for testing in Cornell’s **Big Blue Wind Tunnel**. The goal was to engineer a blade that met realistic aerodynamic performance expectations while remaining structurally sound under operational loads. This project mimicked an authentic engineering design workflow—balancing theory, CAD, simulation, prototyping, and testing—to produce a blade capable of efficiently converting wind energy into mechanical power.

![CAD model of final blade]({{ '/assets/images/cad-model.png' | relative_url }})

Design Process: We selected the **NACA 4418 airfoil** because of its high lift at low Reynolds numbers, gentle stall behavior, and suitability for 3D-printed wings. Using MATLAB-based blade element momentum (BEM) calculations, we generated an initial twist and chord schedule designed to keep local angles of attack near optimal values across the radius. The blade was modeled in CAD and structurally evaluated using **ANSYS**, verifying that stresses remained well below yield and deflection stayed within safe limits during expected load cases. Several iterations focused on refining the tip geometry, reducing stress concentrations near the root, and ensuring manufacturability for 3D printing.

![Wind tunnel test photo]({{ '/assets/images/turbine-pic.png' | relative_url }})

Testing Summary: The finalized blade was printed, mounted to the test rig, and evaluated under three controlled wind-speed conditions. For each speed, we performed a sequence of controlled brake-torque steps to measure rotational speed and torque, allowing us to compute mechanical power output. The resulting **power curves** showed clear performance differences across wind speeds and aligned closely with our MATLAB predictions. Structural integrity was also confirmed during operation—no deformation, flutter, or indications of stall at the design wind speed.

![Power curve plot]({{ '/assets/images/power-curve.png' | relative_url }})

My Contribution: I contributed across design, simulation, and analysis. Specifically, I helped refine the blade geometry, supported ANSYS structural modeling, assisted with MATLAB power-curve processing, and collected and analyzed wind-tunnel data during testing. I also contributed significantly to documentation and presentation materials, ensuring our engineering rationale and experimental results were communicated clearly.
