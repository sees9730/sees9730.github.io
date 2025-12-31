---
permalink: /experience/
title: "Experience"
---

## Thesis: Safe Autonomous Systems via TPOs & Neural Networks

**University of Colorado Boulder** | Aug 2025 – May 2026
**Advisor:** Morteza Lahijanian | ARIA Systems

![Thesis Research](/assets/images/thesis_diagram.png)

### Timed Partial Orders (TPOs)
Extending TPO expressiveness to handle complex autonomous mission scenarios including conditional workflows, hierarchical task structures (TPO within a TPO), and dependency-aware planning. The goal is to enable autonomous systems to reason about and execute multi-stage missions more efficiently.

### Neural Control Synthesis
Developing a stochastic control synthesis framework using neural certificates to provide safety guarantees for learned controllers. The goal is to prove that autonomous systems can operate safely under uncertainty while leveraging neural networks.

---

## Laboratory for Atmospheric and Space Physics (LASP)

**Mission Planner & Autonomy Engineer** | Boulder, CO | Jan 2023 – Current

![LASP Logo](/assets/images/lasp_logo.png)

Built an autonomous constraint-based task planning framework in Python for NASA CubeSat missions in LEO sun-synchronous orbits.

### Missions

![SPRITE Logo](/assets/images/sprite_logo.png) ![MANTIS Logo](/assets/images/mantis_logo.png)

**SPRITE** - 12U CubeSat studying supernova remnants and reionization proxies.

**MANTIS** - First 16U astrophysics CubeSat observing exoplanet atmospheres and stellar physics in UV spectrum.

**CUTE** - NASA's first astrophysical ultraviolet/optical 6U CubeSat.

### Mission Planner

![Mission Planner Interface](/assets/images/mission_planner_ui.png)

Designed and implemented an autonomous planning framework that eliminated manual scheduling conflicts and optimized observation windows for SPRITE, MANTIS, and CUTE missions.

**Impact:**
- Reduced planning time from 1-2 hours to 5-15 minutes
- Enabled single-click autonomous planning across three concurrent missions
- Added visualization capabilities (never existed before)
- Prediction features: battery estimates, downlink/uplink windows, onboard file capacity, performance metrics
- Scaled to become LASP's standard CubeSat planning framework for future LEO missions

### Pixel Processing Pipeline

![Pixel Processing Results](/assets/images/pixel_processing.png)

Developed a Python pipeline using parallel computing to fit pixel behavior patterns and eliminate background noise from spectral images captured by the CUTE CubeSat. Journal paper written.

---

## Arkisys

**Embedded Flight Systems Engineer Intern** | Long Beach, CA | May 2025 – August 2025

![Arkisys Logo](/assets/images/arkisys_logo.png)

Designed and implemented flight software architecture for the Cutter reusable spacecraft bus—a 3-axis stabilized platform hosting up to 6 payloads for LEO missions.

![SAM E70 MCU](/assets/images/same70_chip.png) ![Cutter Vehicle](/assets/images/cutter_vehicle.png)

### Technical Approach

Built the C flight software for the Cutter space vehicle using multi-MCU architecture (SAM E70) with Ethernet TCP/IP communication backbone. Implemented IEEE 1588 PTP hardware time synchronization to maintain network utilization below 30% during critical operations.

Designed a fault-tolerant communication framework minimizing network overhead with dynamic reconfiguration capabilities, enabling autonomous operation without ground intervention.

### Achievements

- Integrated multi-CPU architectures with sensors and actuators for autonomous flight operations
- Created HITL testing software for propulsion systems
- Implemented digital twin of full system for ground testing and validation
- Designed and presented full system architecture at Preliminary Design Review (PDR)
