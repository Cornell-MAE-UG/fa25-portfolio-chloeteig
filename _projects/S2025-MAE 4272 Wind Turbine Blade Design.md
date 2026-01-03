---
layout: project
title: Wind Turbine Blade Design
technologies: [Autodesk Fusion 360, MATLAB, ANSYS, Wind Tunnel Testing]
image: /assets/images/turbine-pic.png
---

## **Overview**

I completed this project as part of MAE 4272: Fluids and Heat Transfer Lab, working on a team to design, manufacture, and experimentally test a small-scale wind turbine blade in Cornell’s wind tunnel. The objective was to connect aerodynamic theory and experimental methods by designing a blade that produced measurable power while remaining structurally stable under load.

This project followed the full experimental workflow, including analytical modeling, CAD design, structural analysis, fabrication, and wind tunnel testing.

<img src="{{ '/assets/images/cad-model.png' | relative_url }}" style="max-width: 650px; width: 100%; display:block; margin: 1.5rem auto;" />

---

## **Design Approach & Modeling**

Our team selected the NACA 4418 airfoil due to its favorable performance at low Reynolds numbers and predictable stall behavior at the tested scale. I ran blade element momentum (BEM) calculations in MATLAB to generate a chord and twist distribution that maintained effective angles of attack along the blade span.

Using these outputs, we refined blade geometry to balance aerodynamic performance with practical constraints like manufacturability and structural robustness.

---

## **CAD & Structural Analysis**

I supported development of the blade geometry in CAD and used ANSYS to evaluate stress and deflection under expected aerodynamic loading. We iterated the root and tip geometry to reduce stress concentrations, improve manufacturability, and ensure the blade could be safely tested in the wind tunnel.

<img src="{{ '/assets/images/ansys-pic.png' | relative_url }}" style="max-width: 650px; width: 100%; display:block; margin: 1.5rem auto;" />

---

## **Wind Tunnel Testing & Results**

After fabrication, we mounted the blade to the wind tunnel test rig and conducted trials at three freestream velocities. At each speed, we stepped through a range of brake torque settings while measuring rotational speed and torque.

I helped collect experimental data and processed results using Excel and MATLAB to calculate mechanical power output and generate power curves for each operating condition. The measured trends aligned closely with our analytical predictions, validating both the blade design and the modeling approach. The blade remained structurally stable throughout testing with no visible deformation.

<img src="{{ '/assets/images/power-curve.png' | relative_url }}" style="max-width: 650px; width: 100%; display:block; margin: 1.5rem auto;" />

---

## **My Contribution**

This was a team-based project. My contributions included:
- Running MATLAB BEM calculations to generate chord/twist distributions for blade geometry
- Supporting CAD development and blade geometry iteration
- Using ANSYS to evaluate stress and deflection under expected loading
- Helping develop and organize the wind tunnel testing procedure
- Collecting and processing experimental data and assembling the final report documentation

---

## **Outcome**

I delivered a validated turbine blade design supported by analytical modeling, simulation, and wind tunnel data. This project strengthened my ability to connect fluid mechanics theory to experimental testing, interpret real performance data, and communicate results clearly through technical documentation.
