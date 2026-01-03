---
layout: project
title: Wind Turbine Blade Design
description: Team-based project for MAE 4272: Fluids and Heat Transfer Lab where I designed, modeled, and wind-tunnel tested a custom NACA 4418 turbine blade to evaluate aerodynamic performance and mechanical power output.
technologies: [Autodesk Fusion 360, MATLAB, ANSYS, Wind Tunnel Testing]
image: /assets/images/turbine-pic.png
---

## **Overview**

I completed this project as part of MAE 4272: Fluids and Heat Transfer Lab, working on a team to design, manufacture, and experimentally test a small-scale wind turbine blade in Cornell’s wind tunnel. The objective was to connect aerodynamic theory and experimental methods by designing a blade that produced measurable power while remaining structurally stable under load.

This project emphasized the full experimental workflow, including analytical modeling, CAD design, structural analysis, fabrication, and wind tunnel testing.

<img src="{{ '/assets/images/cad-model.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **Design & Analysis**

Our team selected the NACA 4418 airfoil due to its favorable performance at low Reynolds numbers and predictable stall behavior at the tested scale. I ran blade element momentum calculations in MATLAB to generate a chord and twist distribution that maintained effective angles of attack along the blade span.

I supported development of the blade geometry in CAD and used ANSYS to evaluate stress and deflection under expected aerodynamic loading. We iterated the root and tip geometry to reduce stress concentrations, improve manufacturability, and ensure the blade could be safely tested in the wind tunnel.

<img src="{{ '/assets/images/ansys-pic.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **Wind Tunnel Testing & Results**

After fabrication, we mounted the blade to the wind tunnel test rig and conducted trials at three freestream velocities. At each speed, we stepped through a range of brake torque settings while measuring rotational speed and torque.

I helped collect experimental data and processed the results using Excel and MATLAB to calculate mechanical power output and generate power curves for each operating condition. The measured trends aligned closely with our analytical predictions, validating both the blade design and the modeling approach. The blade remained structurally stable throughout testing with no visible deformation.

<img src="{{ '/assets/images/power-curve.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **My Contribution**

This was a team-based project. My contributions included running MATLAB blade element momentum calculations to inform blade geometry, supporting CAD development and structural simulation, developing and organizing the wind tunnel testing procedure, collecting and processing experimental data, and assembling the final report documentation.

---

## **Outcome**

I delivered a validated turbine blade design supported by analytical modeling, simulation, and wind tunnel data. This project strengthened my ability to connect fluid mechanics theory to experimental testing, interpret real performance data, and communicate results clearly through technical documentation.
