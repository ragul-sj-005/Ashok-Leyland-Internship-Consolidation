# Summer Internship at Ashok Leyland Limited, Hosur – I

> **Duration:** 11th May 2026 – 03rd July 2026  
> **Department:** Maintenance & Industrial Automation  
> **Organization:** Ashok Leyland Limited, Hosur – I  
> **Academic Program:** B.E. Robotics and Automation Engineering, PSG College of Technology

---

# Overview

This repository serves as a comprehensive documentation of my Summer Internship at **Ashok Leyland Limited, Hosur – I**, where I had the opportunity to experience the real-world implementation of manufacturing systems, maintenance engineering, industrial automation, and PLC-based control systems.

Unlike a conventional academic project, this internship allowed me to work inside one of India's leading commercial vehicle manufacturing industries, where every day introduced new technologies, engineering practices, industrial standards, and problem-solving approaches.

Throughout the internship, I gradually progressed from understanding manufacturing operations and engine remanufacturing processes to working with maintenance engineers and finally contributing to two industrial automation projects involving Siemens PLCs and Human Machine Interfaces (HMI).

This repository documents that complete journey.

---

# Internship Journey

The internship was structured in multiple phases, with each phase introducing a new aspect of industrial engineering.

```
Company Induction
        │
        ▼
Understanding Manufacturing Operations
        │
        ▼
ALRECON Department
(Engine Remanufacturing)
        │
        ▼
Maintenance Team – Shop Floor 2
        │
        ▼
Project 1
PLC-Based AHU Control Panel
        │
        ▼
Project 2
PLC-Based Coolant Conditioning System
```

Each stage contributed significantly to my understanding of manufacturing systems and industrial automation.

---

# Phase 1 – Understanding the Manufacturing Environment

The internship began with an induction program that introduced the history, culture, manufacturing philosophy, and operational structure of Ashok Leyland Limited.

During this phase, I gained insights into:

- Manufacturing divisions
- Production flow
- Safety procedures
- Industrial discipline
- Lean Manufacturing practices
- Ashok Leyland Production System (ALPS)
- 5S workplace organization
- Quality standards
- Plant operations

This provided the foundation required to understand how different departments interact to manufacture commercial vehicle engines and components efficiently.

---

# Phase 2 – ALRECON Department (Engine Remanufacturing)

The next phase of the internship was carried out in the **ALRECON (Ashok Leyland Reconditioning) Department**, where I observed the complete lifecycle of engine remanufacturing.

Instead of manufacturing a new engine, ALRECON restores used engines back to original specifications through systematic inspection, machining, reconditioning, and testing.

During this phase, I understood the complete remanufacturing workflow:

- Engine receiving
- Engine dismantling
- Degreasing and cleaning
- Component segregation
- Visual inspection
- Dimensional inspection
- Precision measurement
- Machining operations
- Component reconditioning
- Engine assembly
- Dressing operations
- Dynamometer testing
- Quality inspection
- Engine dispatch

Observing these processes helped me understand how quality control, precision engineering, and standardized inspection procedures ensure that remanufactured engines achieve the same level of reliability as newly manufactured engines.

I also gained exposure to production planning, inventory management, material traceability, quality assurance practices, and documentation procedures followed in large-scale manufacturing industries.

---

# Phase 3 – Maintenance Team (Shop Floor 2)

After understanding manufacturing operations, I joined the Maintenance Team of Shop Floor 2.

This phase completely changed my perspective.

Rather than observing manufacturing, I began understanding how manufacturing itself is sustained.

I learned that uninterrupted production depends heavily on maintenance engineering, preventive planning, equipment monitoring, troubleshooting, and industrial automation.

During this phase, I studied:

- Preventive Maintenance
- Predictive Maintenance
- Breakdown Maintenance
- Electrical Maintenance
- Mechanical Maintenance
- PLC-based control systems
- Industrial sensors
- Contactors
- Relays
- Circuit breakers
- Motors
- Industrial instrumentation
- Control panels
- Industrial wiring
- Human Machine Interfaces (HMI)
- Documentation practices
- Safety procedures

Working alongside maintenance engineers provided valuable exposure to practical industrial troubleshooting techniques and equipment diagnostics.

This phase strengthened my understanding of how automation and maintenance work together to achieve reliable manufacturing operations.

---

# Project 1 – PLC-Based AHU Control Panel

One of the most valuable experiences during the internship was contributing to the development of a PLC-based Air Handling Unit (AHU) Control Panel for Shop Floor 5.

The objective of the project was to automate the operation of the Air Handling Unit using Siemens PLC technology while providing a user-friendly Human Machine Interface for operator interaction.

The project involved:

- Studying the existing AHU system
- Requirement analysis
- Understanding HVAC operation
- Electrical panel design
- Component selection
- PLC hardware configuration
- Siemens TIA Portal programming
- HMI development
- Electrical wiring
- PLC-HMI communication
- System testing
- Validation

The implemented control system allowed manual blower speed selection through the HMI while ensuring proper interlocking and safe equipment operation through PLC logic.

This project strengthened my understanding of industrial automation system development from initial design through final commissioning.

---

# Project 2 – PLC-Based Coolant Conditioning System

The second project represented the most technically challenging phase of the internship.

The objective was to develop a PLC-based monitoring system capable of continuously monitoring the coolant conditioning process associated with engine testing operations.

Unlike conventional automation applications, this project required accurate real-time monitoring of rotating equipment.

The project involved:

- Understanding coolant circulation systems
- Studying process instrumentation
- PLC configuration
- High-Speed Counter implementation
- RPM monitoring
- HMI development
- Real-time process visualization
- Testing and validation

One of the major engineering tasks involved implementing High-Speed Counter (HSC) technology available within Siemens PLCs.

Dedicated High-Speed Counter channels:

- **ID1000** – Engine RPM
- **ID1004** – Motor RPM

were configured to acquire high-frequency pulse signals generated by rotating equipment.

To achieve deterministic execution, RPM calculations were performed using a Cyclic Interrupt executing in less than **10 milliseconds**.

The pulse frequency was converted into rotational speed using the Pulse Per Revolution (PPR) methodology:

```
RPM = (Frequency × 60) / Pulse Per Revolution
```

Double Integer (DINT) variables were utilized to ensure reliable handling of continuously increasing pulse counts during high-speed operation.

The calculated RPM values were displayed on the Human Machine Interface, providing maintenance engineers with accurate real-time monitoring of engine and motor operating conditions.

This project significantly enhanced my understanding of industrial automation, PLC programming, high-speed signal processing, industrial instrumentation, and process monitoring.

---

# Technologies and Tools

### Industrial Automation

- Siemens PLC
- Siemens TIA Portal
- Human Machine Interface (HMI)
- High-Speed Counter (HSC)
- PLC-HMI Communication

### Programming Concepts

- Ladder Logic
- Cyclic Interrupt Programming
- High-Speed Pulse Processing
- RPM Calculation
- Pulse Per Revolution (PPR)
- Double Integer (DINT)

### Industrial Engineering

- Preventive Maintenance
- Predictive Maintenance
- Breakdown Maintenance
- Industrial Instrumentation
- Electrical Control Panels
- Industrial Wiring
- Troubleshooting
- Testing & Commissioning

---

# Skills Developed

Throughout the internship, I strengthened both technical and professional competencies.

### Technical Skills

- Industrial Automation
- PLC Programming
- HMI Development
- Electrical Panel Design
- Industrial Instrumentation
- Control System Development
- Troubleshooting
- Process Monitoring
- Maintenance Engineering
- Manufacturing Systems

### Professional Skills

- Engineering Documentation
- Analytical Thinking
- Problem Solving
- Technical Communication
- Teamwork
- Industrial Safety
- Time Management
- Professional Ethics

---

# Key Learning Outcomes

The internship successfully bridged the gap between classroom learning and industrial practice.

More importantly, it helped me understand that modern manufacturing is a multidisciplinary integration of:

- Mechanical Engineering
- Electrical Engineering
- Electronics
- Instrumentation
- Automation
- Software
- Production Engineering

Working on real industrial systems demonstrated how these disciplines combine to achieve reliable, efficient, and intelligent manufacturing operations.

The experience strengthened my interest in Industrial Automation, Robotics, PLC Programming, Manufacturing Systems, and Smart Factory technologies.

---

# Acknowledgement

I sincerely thank **Ashok Leyland Limited, Hosur – I**, the Maintenance Department, ALRECON Department, and all the engineers, supervisors, technicians, and mentors who guided me throughout this internship.

I am also grateful to **PSG College of Technology** for providing this opportunity to gain practical industrial exposure and apply academic concepts in a real manufacturing environment.

---

# Final Reflection

This internship was much more than an industrial training programme—it was an opportunity to witness how engineering principles are transformed into reliable industrial solutions. From understanding engine remanufacturing in ALRECON to working alongside maintenance engineers and contributing to PLC-based automation projects, every phase expanded my technical knowledge and strengthened my confidence as an aspiring Robotics and Automation Engineer.

The experience reinforced my passion for industrial automation, intelligent manufacturing, and smart factory technologies, and it has laid a strong foundation for my future career in automation, robotics, and advanced manufacturing systems.
