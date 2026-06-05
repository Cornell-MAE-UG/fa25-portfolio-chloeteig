---
layout: project
title: UPick - Assistive Device Redesign
technologies: [CAD, Rapid Prototyping, Soldering, Assistive Technology, Open Source Design]
image: /assets/images/upick-cover.png
---

## **Overview**

I completed this project as a Product Engineering Intern with Tikkun Olam Makers (TOM) in Tel Aviv, Israel during the summer of 2025. TOM is a global nonprofit that connects engineers and makers with people who have unmet assistive technology needs. I was assigned to redesign the UPick, a vacuum-based handheld device that enables wheelchair users and individuals with limited hand dexterity to independently lift flat objects from the floor.

The existing device functioned mechanically but had significant aesthetic and usability shortcomings. My goal was to improve the form, finish, and circuit reliability while preserving the core vacuum mechanism and keeping the design reproducible for the open-source community.

---

## **The Device**

The UPick operates on vacuum adhesion technology, powered by a rechargeable 3.7V lithium battery and a small diaphragm air pump. When activated, suction cups at the tip of the device create enough vacuum force to pick up flat items like papers, cards, or dropped objects from the floor, requiring minimal grip strength or hand dexterity from the user.

<img src="{{ '/assets/images/upick-cad.png' | relative_url }}" style="max-width: 650px; width: 100%; display:block; margin: 1.5rem auto;" />

<p style="text-align:center; font-size:0.9rem; color:#666;">Exploded view showing the PVC tube body, air pump, battery housing, 3D printed connectors, suction assembly, and power switch.</p>

---

## **Redesign Process**

I evaluated the existing prototype and identified the primary areas for improvement: inconsistent paint finish on the tubing, unreliable solder joints in the circuit, and overall aesthetics that didn't reflect the quality of the underlying concept.

I created and tested updated CAD models, then fabricated an improved prototype by cutting and finishing the PVC tubing, applying a multi-coat spray paint and sanding process, and resoldering the circuit to improve electrical reliability. Each change was tested iteratively before being incorporated into the final build.

<img src="{{ '/assets/images/upick-iterations.png' | relative_url }}" style="max-width: 650px; width: 100%; display:block; margin: 1.5rem auto;" />

<p style="text-align:center; font-size:0.9rem; color:#666;">Prototype iterations.</p>

<img src="{{ '/assets/images/upick-sautering.png' | relative_url }}" style="max-width: 650px; width: 100%; display:block; margin: 1.5rem auto;" >Sautering circuits.</p>

---

## **Open Source Publication**

After finalizing the redesign, I compiled and published updated documentation to the TOM open-source platform, where it has since been downloaded 18 times by maker communities around the world. The documentation includes fabrication steps, a full parts and tools list, CAD files, and circuit details so that anyone with access to basic shop tools and an FDM printer can reproduce the device.

<a href="{{ '/assets/UPick.pdf' | relative_url }}" target="_blank">Download the full build documentation →</a>

---

## **My Contribution**

I worked on this project with one other intern. My contributions included:
- Evaluating the existing prototype and identifying areas for improvement
- Creating and iterating CAD models for the redesigned geometry
- Fabricating the updated prototype including tubing prep, paint finish, and soldered circuits
- Writing and publishing open-source documentation to the TOM platform

---

## **Outcome**

The redesigned UPick is a cleaner, more reliable version of a device that gives people greater independence in daily life. This project was my first experience taking full ownership of a physical product redesign from evaluation through fabrication and documentation, and it reinforced how much the details of finish and reliability matter in assistive technology.