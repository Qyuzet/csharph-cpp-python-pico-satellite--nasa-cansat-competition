# CanSat 2023 Preliminary Design Review (PDR) Documentation

## Overview

The CanSat competition provides a unique opportunity for students to design, build, and launch a small satellite system. This document outlines the preliminary design review (PDR) for our CanSat project, which aims to fulfill the mission requirements set forth by the CanSat 2023 competition. Our CanSat system comprises a container and a payload, each designed to execute specific scientific and engineering tasks.

## Team Organization

Our team, the **Makara Aeronautics Avionics Team (MAAT)** from the **University of Indonesia**, is a diverse group of students with a shared passion for aerospace engineering and avionics. The team has been nominated to the final Critical Design Review (CDR) phase and scored an impressive 90 out of 100 for the PDR blueprint.

### Team Members and Roles

- **Project Manager:** Oversees the overall project coordination and management.
- **Systems Engineer:** Ensures system integration and functionality of all subsystems.
- **Payload Engineer:** Designs and tests the payload components.
- **Container Engineer:** Focuses on the design and integration of the container.
- **Electronics Engineer:** Manages the electronic components, including sensors and data acquisition systems.
- **Software Engineer:** Develops and tests the software for data collection and analysis.
- **Safety Officer:** Ensures all safety protocols are followed during the design and launch phases.
- **Programming Team Lead:** **Riki Awal Syahputra** - Leads the programming team, responsible for developing the software and ensuring the successful implementation of the programming aspects of the project.

## Acronyms

To facilitate understanding, a list of acronyms used throughout this document is provided below:

- **CanSat:** Container Satellite
- **PDR:** Preliminary Design Review
- **CDR:** Critical Design Review
- **CONOPS:** Concept of Operations
- **DCS:** Descent Control System
- **GPS:** Global Positioning System

## Mission Summary

The primary mission objective of our CanSat is to deploy a payload from the container at a predetermined altitude, collect scientific data during descent, ensure the egg payload, point the camera position, and ensure the safe recovery of the payload. We have chosen to attempt the selectable objective, which involves measuring atmospheric pressure, temperature, and capturing images during descent. The rationale for this selection is based on the scientific value of the data and the feasibility of integrating the required sensors within the payload constraints.

## System Requirement Summary

The CanSat system must meet several high-level requirements to ensure mission success:

- **Deployment:** The CanSat must deploy from the launch vehicle at a specified altitude without mechanical failures.
- **Descent Control:** The descent rate must be controlled to ensure data collection and safe landing.
- **Data Acquisition:** The payload must collect atmospheric data (pressure, temperature) and capture images during descent.
- **Recovery:** The payload must be recoverable and intact after landing.
- **Communication:** The CanSat must transmit data to the ground station in real-time.

## System Level Configuration Trade & Selection

We considered two preliminary system-level concepts for our CanSat design:

1. **Concept A:** A streamlined cylindrical container with a deployable parachute for descent control and a payload equipped with multiple sensors and a camera.
2. **Concept B:** A modular container with detachable sections, each equipped with independent descent control mechanisms.

After evaluating the concepts based on criteria such as weight, cost, ease of assembly, and reliability, we selected Concept A. The streamlined design reduces aerodynamic drag and simplifies the deployment mechanism, making it more reliable.

## Physical Layout

The physical layout of the selected CanSat configuration includes:

- **Container Dimensions:** _Specified at PDR_
- **Payload Components:** Sensors, camera, data acquisition system, and descent control mechanisms.
- **Sensor Placement:** Strategically placed to optimize data collection during descent.
- **Power Supply:** Batteries housed within the payload to power all electronic components.

## System Concept of Operations (CONOPS)

The CanSat operations can be divided into three main phases:

1. **Launch and Deployment:**
   - The CanSat is integrated into the launch vehicle.
   - At the target altitude, the container is deployed, and the payload begins its descent.

2. **Descent Operations:**
   - The parachute deploys to control the descent rate.
   - Sensors collect atmospheric data, and the camera captures images.
   - Data is transmitted to the ground station in real-time.

3. **Recovery and Data Analysis:**
   - The payload lands safely.
   - The team retrieves the payload and downloads any stored data.
   - Data is analyzed to meet mission objectives and verify system performance.

## Launch Vehicle Compatibility

The CanSat must fit within the payload section of the launch vehicle. Our design ensures clearances are maintained, and no sharp protrusions exist that could hinder deployment. We have included a dimensioned drawing to demonstrate the fit and ensure compatibility.

## Sensor Subsystem Design

The sensor subsystem includes the following components:

- **Air Pressure Sensor:** Measures atmospheric pressure during descent.
- **Air Temperature Sensor:** Records temperature variations.
- **GPS Sensor:** Tracks the CanSat's location.
- **Camera:** Captures images of the descent and landing area.
- **Battery Voltage Sensor:** Monitors the power supply status.

## Trade Studies and Selection

For each sensor, we conducted trade studies to evaluate different models based on interfaces, resolution, cost, size, weight, and other relevant factors. The selected sensors are:

- **Air Pressure Sensor:** [Model Name], chosen for its high resolution and reliability.
- **Air Temperature Sensor:** [Model Name], selected for its accuracy and compact size.
- **GPS Sensor:** [Model Name], chosen for its robust performance and ease of integration.
- **Camera:** [Model Name], selected for its high-resolution imaging capabilities.
- **Battery Voltage Sensor:** [Model Name], chosen for its precise monitoring capabilities.

## Descent Control Design

The descent control system (DCS) is critical for ensuring the payload's safe descent and landing. Our design includes:

- **Parachute:** A lightweight, deployable parachute that ensures a controlled descent rate.
- **Aerobraking Mechanisms:** Deployed to stabilize the payload during descent and reduce terminal velocity.
- **Payload Uprighting Mechanisms:** Ensure the payload lands in an upright position for optimal data collection post-landing.

## Mechanical Subsystem Design

The mechanical subsystem encompasses the structural elements of both the container and the payload:

- **Container Structure:** Durable materials chosen for their strength-to-weight ratio, ensuring protection during launch and deployment.
- **Payload Structure:** Compact and robust design to house all sensors and electronic components securely.
- **Attachment Mechanisms:** Securely mount sensors, batteries, and other components to withstand the forces experienced during launch and descent.

## Conclusion

Our CanSat project embodies a comprehensive approach to meeting the CanSat 2023 competition requirements. Through meticulous design, rigorous trade studies, and thorough testing, we aim to achieve mission success and contribute valuable scientific data. The detailed design considerations and subsystem integrations outlined in this document demonstrate our team's commitment to excellence in engineering and innovation in the field of small satellite systems.
