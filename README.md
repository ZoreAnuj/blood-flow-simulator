# Blood Flow Simulator

A C++ application that models blood flow using Poiseuille’s Law. This project simulates fluid dynamics in vascular systems, calculating flow rate based on vessel geometry and fluid properties. It serves as a foundational exploration into physics-based simulation for complex systems.

## Key Features
* Calculates volumetric flow rate using Poiseuille’s equation.
* Accepts inputs for vessel radius, pressure difference, viscosity, and length.
* Provides a command-line interface for parameterized simulations.
* Outputs results in standard units for analysis.

## Tech Stack
* C++ (Standard Library)
* CMake (Build system)

## Getting Started
```bash
git clone https://github.com/zoreanuj/blood-flow-simulator.git
cd blood-flow-simulator
mkdir build && cd build
cmake .. && make
./blood-flow-simulator
```