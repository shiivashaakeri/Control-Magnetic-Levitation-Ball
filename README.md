
# Control-Magnetic-Levitation-Ball
This project is a part of the "Advanced Control" course at the University of Tehran. It aims to control a magnetic levitation system for stabilizing a ball at a desired position. The project consists of two phases. In Phase 1, a model of the magnetic levitation system is developed, and a PID controller is designed. In Phase 2, state-feedback and observer-based controllers are designed to enhance the system's performance.
## Phase 1
### Magnetic Levitation System Model
This section presents the mathematical model of the magnetic levitation system used in the project.
### State-Space Analysis 
The state-space representation of the system is derived in this section
### Linearization and Equilibrium Points
The system is linearized around its equilibrium points to obtain a linear model that facilitates controller design.
### Transfer Function
In this section, the transfer function of the linearized system is derived and analyzed.
### PID Controller Design
A proportional-integral-derivative (PID) controller is designed based on the transfer function obtained in the previous section.
### Control Non-Linear Model in Simulink
This section presents a simulation of the control system in Simulink using the non-linear model of the magnetic levitation system.

## Phase 2
### State-Feedback Design
In this section, a state-feedback controller is designed based on the state-space model of the system.
### State-Feedback with Additive Disturbance Design
The state-feedback controller is enhanced by incorporating an additive disturbance in the system model.
### Tracker using State-Feedback with Integral Action
An integral action is added to the state-feedback controller to improve the system's tracking performance.
### Observer Design
In this section, an observer-based controller is designed to estimate the system's state variables.
### Reduced Order Observer Design 
The observer-based controller is optimized using a reduced-order observer.
### Control Non-Linear Model in Simulink
The control system is simulated in Simulink using the non-linear model of the magnetic levitation system.

## Helpful Links
- [Magnetic Levitation Model](https://de.mathworks.com/help/sl3d/examples/magnetic-levitation-model.html)
- [LQR-based Optimal Tuning of PID Controller for Trajectory Tracking of Magnetic Levitation System](https://www.researchgate.net/publication/271144927_LQR_based_Optimal_Tuning_of_PID_Controller_for_Trajectory_Tracking_of_Magnetic_Levitation_System)
- [Control of Magnetic Levitation System Using PID and LQG Controllers](https://core.ac.uk/download/pdf/80148227.pdf)
- [Magnetic Levitation System Control using PID Controller](https://www.youtube.com/watch?v=W46V4Y3jdJs)

Please refer to these links to gain a better understanding of the project's concepts and techniques.
