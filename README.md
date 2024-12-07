# Vortex Shedding in Underwater Circular Cylinders

This repository contains the simulation and analysis of vortex shedding around underwater circular cylinders at high Reynolds number (Re = 10,000). The project demonstrates the dynamics of Vortex-Induced Vibrations (VIV) and evaluates the accuracy and reliability of the RANS Shear-Stress Transport (SST) turbulence model in capturing the VIV phenomenon.

Here is the vorticity with time:


https://github.com/user-attachments/assets/4c1806cc-3ece-4534-a7f7-cfc6ec3863ea


## Overview

Vortex shedding plays a significant role in underwater structures' vibrations, known as Vortex-Induced Vibrations (VIV). The study investigates:
- The formation and evolution of vortices downstream of a circular cylinder.
- Time-varying lift and drag coefficients due to vortex shedding.
- Pressure distribution along the cylinder surface.

## Results and Validation

The results are validated by comparing the pressure coefficients along the cylinder surface with experimental data of [Stephen Wornom 2001](https://www.sciencedirect.com/science/article/abs/pii/S0045793011000636)

### Velocity
Vortex evolution with time:
![Velocity](https://github.com/saifrehman945/FluentVortexShedding/blob/Initial_simulations/Results/Images/timestamps.png)

### Lift vs Time
![Lift](https://github.com/saifrehman945/FluentVortexShedding/blob/Initial_simulations/Results/Images/Cl.png)

### Drag vs Time
![Drag](https://github.com/saifrehman945/FluentVortexShedding/blob/Initial_simulations/Results/Images/Cd.png)


## Key Highlights

1. **Vortex Formation Dynamics**  
   - Vortices are generated alternately downstream of the circular cylinder.  
   - Animations showcase the evolution of vortices over 50s, 100s, and 450s.

2. **Lift and Drag Coefficients**  
   - Time-varying lift and drag coefficients demonstrate the oscillatory behavior of VIV.

3. **Pressure Distribution**  
   - Pressure coefficients along the cylinder surface are compared with experimental data for validation.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/vortex-shedding.git
   cd vortex-shedding
   ```

2. Open the `FluentFiles/` directory in ANSYS Fluent and load the provided case files.

3. Run the simulation and export results for further analysis.

4. View animations in the `Animations/` folder or generate new ones using the exported data.

## Prerequisites

- **ANSYS Fluent** (tested with version Ansys 2020R1)

## License

This project is licensed under the [MIT License](LICENSE).
