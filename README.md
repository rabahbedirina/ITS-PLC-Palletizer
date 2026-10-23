# ITS PLC Palletizer System (`ITS-PLC-Palletizer`)

An industrial automation and simulation project designed for the **ITS PLC MHJ Edition** 3D plant simulation environment, controlled using Siemens SIMATIC STEP 7 (S7 Classic) / WinSPS-S7.

## 🎥 Demonstration Video

This repository corresponds to the setup and simulation demonstrated in the following YouTube video:

* [ITS PLC Palletizer System | Palettiseur](https://www.youtube.com/watch?v=XZvztTprB0M)

## 🏗️ Project Overview

The **ITS-PLC-Palletizer** repository contains the PLC configuration and control logic to simulate a high-level case palletizer system. The objective of this automated plant is to stack and palletize incoming cases up to multiple layers (e.g., up to three layers) using mechanized turning devices, row pushers, clamping assemblies, and pallet elevators.

### Key Components:

* **PLC Program Blocks:** Contains organization blocks, function blocks, and statement list/ladder logic code targeted for Siemens S7-300/400 controllers.
* **Hardware & Network Configuration:** Hardware layout files matching the virtual 3D palletizer plant setup in ITS PLC.
* **Symbol & Variable Tables:** Tag mappings and signal allocations connecting the virtual plant's sensors and actuators to the PLC memory addresses.

## 🛠️ Software Requirements & Tools

To open, run, or modify this project, you will need:

1. **Siemens SIMATIC STEP 7 (v5.x)** or **WinSPS-S7** (with built-in S7-300 simulation capabilities).
2. **ITS PLC MHJ Edition** (3D Industrial Plant Simulation Software featuring the Palletizer scene).

## 🚀 Getting Started

1. Clone or download this repository to your workspace.
2. Open **WinSPS-S7** or **Siemens STEP 7** and load the Palletizer project files.
3. Launch the **ITS PLC MHJ** 3D Palletizer scene simulator.
4. Establish communication between the PLC environment and the 3D plant simulator to test the automatic layering, clamping, and pallet unloading cycles.