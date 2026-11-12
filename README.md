# High-Precision Robotic End-Effector Customization for Autonomous Solar Panel Connecting

## Project Overview
* This repository features the Design for Manufacturing (DFM) case study of a customized mechanical modification for a parallel industrial robotic end-effector (modeled around a dual-finger framework). The objective was to adapt the gripper to execute high-precision, repeatable alignment and mating cycles for delicate solar panel connectors. Regardless of solar connector orientation in space/approach from the gripper within 30° of rotation, the attachment is designed to guide and snap the solar connector into place, while ensuring a tight enough fit that the connector does not move as the robot is applying force to snap the connectors together. 

* These attachments are designed to be secured via two zip ties fed through them to quickly attach/detach from the gripper and ensure the robotic gripper can be used for a variety of tasks beyond autonomous solar panel connection. They were designed to be quickly printed for a rapid iteration process. Final tests with the fully automated process confirmed perfect mating with the solar connectors regardless of connector orientation or 

*Note: Due to the components being used in active infrastructure, all proprietary engineering files (`.f3d`, `.STEP`) and spatial datasets have been completely scrubbed. This repository serves strictly as a technical documentation portfolio highlighting remote agile product development, rapid prototyping execution, and iterative tolerancing loops.*

---

### Technical Workflow Meta
* **Role:** Remote Mechanical Design Engineer / CAD Expert
* **CAD Environment:** Autodesk Fusion 360 (Parametric & Assembly Modeling)
* **Execution Strategy:** Distributed Rapid Prototyping (Remote Design -> Onsite 3D Printing Production -> Physical Loop Testing)
* **Development Depth:** 8 Full Iteration Cycles to achieve operational tolerance validation. Missing versions 4 and 6 due to rapid iteration and minute changes between versions of slight tolerances. 

---

## Technical Specifications & DFM Constraints

* **Actuator Baseline:** Two-finger parallel actuation mechanism (0–95mm jaw travel limit, 2kg clamping profile).
* **Manufacturing Medium:** Onsite Fused Deposition Modeling (FDM) 3D printing.
* **Material Selection:** PETG blends for high mechanical tensile strength and environmental UV/thermal resistance during physical outdoor simulation tests.
* **Target Part Interface:** Complex interlocking contours of standard solar connector terminal shapes.
* **Precision Metric:** Mating alignment threshold engineered down to ±0.20mm to prevent structural shearing of plastic connector tabs.

---

```plaintext
Pikka-Gripper-Modification_propertyofTARinc/
├── design-1/
│   ├── images/
│   │   ├── design-1.png
│   └── README.md
├── design-2/
│   ├── images/
│   │   ├── design-2.png
│   └── README.md
├── design-3/
│   ├── images/
│   │   ├── design-3.png
│   └── README.md
├── design-5/
│   ├── images/
│   │   ├── design-5.png
│   └── README.md
├── design-7/
│   ├── images/
│   │   ├── design-7.png
│   └── README.md
├── design-8/
│   ├── images/
│   │   ├── design-8.png
│   └── README.md
├── README.md       # Main project overview
```

---

## Note on Portfolio Visuals (Conceptual Representation)
*Note: To safeguard property rights, images depict generic assembly stages rather than the final operational terminal footprint.*

---

## Solar Connectors
The solar connectors used in the lab, and ultimately the construction site, is restricted information. General dimensions for a similar connector was provided and a model was made to remotely check expected connector fit and general part dimensioning. Models of the connectors are shown below, taking the shape of general, mass-produced solar panel connectors. 

---

## Final Thoughts
This project was made to be quickly iterative and fast to produce, being intentionally semi-permanent. For future development, more robust design considerations would ideally be used, such as a nylon-tipped set screw fed through a brass threaded insert soldered into the part to attach via pressure from the screw for stronger, more consistent attachment as well as more rapid attachment/detachment as opposed to zip ties. 
