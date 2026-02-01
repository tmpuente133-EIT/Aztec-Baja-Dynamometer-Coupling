# Custom Motor-to-Spline Coupling for Baja SAE Dynamometer

## Overview
This project involved the design of a **custom mechanical coupling** to interface an electric motor with an existing **splined drivetrain shaft** for a student-built dynamometer supporting the **Aztec Baja SAE Racing Team**.

![Full drivetrain assembly overview](images/assembly_overview.png)

The primary challenge was adapting **non-standard, pre-existing components** into a reliable, manufacturable torque-transmitting assembly while maintaining alignment and minimizing drivetrain loads.

---

## Project Context
Baja SAE dynamometers are often built using a combination of:
- Salvaged drivetrain components
- Off-the-shelf electric motors
- Custom shafts, gears, and frames

In this case, the motor output shaft was **incompatible with the splined input shaft** used elsewhere in the dyno system. Commercial couplings did not meet the geometric, space, or interface requirements, motivating a fully custom solution.

---

## Design Objectives
- Transmit torque from motor to dyno shaft reliably  
- Interface with an **existing external spline profile**  
- Maintain concentricity and alignment  
- Fit within existing packaging constraints  
- Allow straightforward manufacturing and assembly  
- Enable future serviceability and disassembly  

---

## Coupling Design

### External Geometry
The coupling is a cylindrical adapter designed to fit within the dyno drivetrain envelope while maintaining sufficient wall thickness for torque transmission.

ADD Photo here of full coupling

### Internal Features
Internal splines were modeled to match the mating shaft profile and provide reliable torque transfer with adequate engagement length.

![Coupling section view showing internal splines](images/coupling_section.png)

A split-section view was used to verify spline engagement, wall thickness, and internal clearances.

---

## Assembly Integration

The coupling installs inline between the motor and shaft assembly:

![Exploded assembly showing motor, coupling, and shaft](images/exploded_view.png)

1. The motor shaft engages the coupling bore  
2. Internal splines mate with the dyno shaft  
3. The shaft is supported by bearings mounted to a rigid frame  
4. Torque is transmitted axially through the coupling into the drivetrain  

This configuration minimizes bending loads on the motor while preserving alignment.

![Installed coupling in dyno frame](images/installed_coupling.png)

---

## CAD & Modeling
- Designed entirely in **SolidWorks**
- Included:
  - Fully constrained part models  
  - Section views to verify spline engagement  
  - Exploded assembly views for documentation  

Design iterations focused on:
- Spline engagement length  
- Wall thickness for torque capacity  
- Manufacturability using conventional machining processes  

---

## Engineering Considerations
- Torque transmission through involute splines  
- Stress concentration at spline roots  
- Assembly tolerances and fit  
- Alignment sensitivity between motor and shaft  
- Practical manufacturing constraints for a student-built system  

---

## Results & Impact
- Enabled successful mechanical integration of the dyno drivetrain  
- Eliminated the need for hard-to-source commercial adapters  
- Provided a reusable solution adaptable to future dyno configurations  
- Demonstrated applied mechanical design under real-world constraints  

---

## Skills Demonstrated
- Mechanical design under interface uncertainty  
- CAD for power transmission components  
- Design for manufacturability  
- Reverse engineering and component inference  
- Engineering communication and documentation  

---

## Acknowledgments
Designed in support of the **Aztec Baja SAE Racing Team** dynamometer project.
