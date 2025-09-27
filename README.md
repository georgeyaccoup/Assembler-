
# Assembler (Sorting & Assembly Line)

**Sorting and Assembler Line** — using 3 main systems:  
- PLC for automation  
- Hydraulic pushers for sorting  
- Robotic arm for assembling  

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Architecture / Components](#architecture--components)  
- [Prerequisites](#prerequisites)  
- [Setup / Installation](#setup--installation)  
- [Usage](#usage)  
- [Folder Structure](#folder-structure)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)

---

## Overview

This project implements an automated system combining sorting and assembly processes. It integrates:

- A **PLC (Programmable Logic Controller)** for managing automation logic  
- **Hydraulic pushers** for sorting items in a production line  
- A **robotic arm** to assemble parts after sorting  

It can be used for simulating or controlling real-world industrial automation workflows.

---

## Features

- Real-time sorting control using PLC logic  
- Hydraulic actuation for routing items to different lanes  
- Robotic arm automation for final assembly  
- Logging and status monitoring  
- Support for simulation (or interfacing with hardware)  

---

## Architecture / Components

The system is divided into modular subsystems:

| Subsystem | Role |
|----------|------|
| PLC Module | Control logic, sensors, actuators, sequencing |
| Hydraulic System | Physical sorting pushers to direct items |
| Robotic Arm | Picks, places or assembles parts |
| Communication / Interface Layer | Messaging, signals, events between components |
| Logging / Monitoring | Record operations, errors, status |

---

## Prerequisites

Before running this project, ensure you have:

- A PLC programming environment or simulator  
- Hardware interfacing capabilities (for actuators, sensors, motors)  
- Development tools (e.g. for the control logic code)  
- Dependencies (see next section)  

---

## Setup / Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/georgeyaccoup/Assembler-.git
   cd Assembler-


2. Install any required dependencies (languages, libraries, drivers).

3. Configure hardware or simulation settings (e.g. port names, channels).

4. Deploy control logic to the PLC / controller.

5. (Optional) Launch any monitoring or UI tools.

---

## Usage

1. Power on all hardware / start simulators.
2. Run the PLC program / logic.
3. Feed input items into the system.
4. Monitor sorting and assembly via logs or UI.
5. Adjust configurations as needed.

Make sure all safety interlocks and sensors are tested before full operation.

---

## Folder Structure

Here is a breakdown of the main directories and files in this repo:

```
Assembler-/
├── AdditionalFiles/PLCM/         # PLC modules, code, or project files  
├── IM/                            # Interface module(s)  
├── Logs/                          # Logs and runtime output  
├── System/                        # Core system logic, control layers  
├── Vci/                           # (Possibly Vision, Communication, Interface)  
├── XRef/                          # Cross-reference code or mapping files  
├── Assembler.factoryio            # FactoryIO template or scene  
├── FactoryIO_Template_S7-1200_... # Template / configuration file  
└── README.md                      # (This file)  
```
