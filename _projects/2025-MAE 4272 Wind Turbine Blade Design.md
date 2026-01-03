---
layout: project
title: Wind Turbine Blade Design Project
description: Designed, modeled, and wind-tunnel tested a custom NACA-4418 turbine blade to evaluate structural performance and aerodynamic power output.
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/turbine-pic.png
---

## **Project Overview**
For the MAE 4272 Wind Energy Engineering course, our team was asked to design, build, and test a small wind turbine blade for use in Cornell’s Big Blue Wind Tunnel. The goal was to create a blade that could produce realistic aerodynamic performance while also remaining structurally reliable under load. The project gave us experience with a complete engineering workflow that included conceptual design, modeling, simulation, fabrication, and testing.

<img src="{{ '/assets/images/cad-model.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **Design Process**
We chose the NACA 4418 airfoil because it performs well at low Reynolds numbers and has a smooth stall behavior that works for 3D printed blades. We ran MATLAB blade element momentum calculations to help us create a twist and chord schedule that kept local angles of attack near desirable values along the span.  

We developed the blade in CAD and then used ANSYS to check stresses and deflection under expected loading. The simulations confirmed that the design was structurally sound and that the blade shape could be manufactured reliably. We also refined the tip shape and root region to reduce stress concentrations and improve print quality.

<img src="{{ '/assets/images/ansys-pic.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **Testing Summary**
Once the blade was printed, we mounted it onto the test rig and ran trials at three wind speeds. At each speed, we stepped through a series of brake torque settings and recorded torque and rotational speed. From this, we calculated mechanical power output and created three power curves for the blade in excel and combined them on MATLAB.

The results showed clear trends across the wind speeds and matched closely with our MATLAB predictions. In addition, our blade remained stable throughout testing, with no signs of deformation or stall behavior at any points.

<img src="{{ '/assets/images/power-curve.png' | relative_url }}" style="max-width: 650px; display:block; margin: 1.5rem auto;" />

---

## **My Contribution**
I developed the testing plan, kept the project on track through each stage, and completed much of the report assembly. I also worked on data collection in the wind tunnel, helped organize our results into clear visuals, and supported the team in preparing our final presentation and documentation.

---