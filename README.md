# SOC


# Project Title: State of Charge (SoC) Estimation for Electric Vehicle Battery using Unscented Kalman Filter 


## Project Description:

This project aims to develop a sophisticated State of Charge (SoC) estimation system for an electric vehicle (EV) battery using the Unscented Kalman Filter (UKF). SoC estimation is crucial for accurate battery management and optimizing the performance and lifespan of EV batteries. The UKF, a robust variant of the Kalman filter, is employed to handle non-linear battery dynamics and uncertainties effectively.

## Key Components:

#### Battery Model:

- Developed an accurate battery model considering voltage, current, temperature, and internal resistance dynamics.
- Battery parameters, such as capacity, open-circuit voltage, and Peukert's exponent are implemented.

#### Unscented Kalman Filter (UKF):

- The UKF is a non-linear estimation technique that approximates the posterior distribution of the system state.
- Implemented the UKF algorithm, including the prediction and update steps.

#### Data Collection:

- Collect real-world battery data, including voltage, current, and temperature, during various driving scenarios.
- Use this data to validate and tune the SoC estimation algorithm.

#### State Estimation:

- Implement the UKF to estimate the battery's SoC in real-time.
- Incorporate the battery model into the UKF to predict the battery's behavior.

#### Validation and Testing:

- Validate the SoC estimation accuracy by comparing the estimated SoC with the actual measured values.
- Test the algorithm under different driving conditions, temperatures, and battery ages.

#### Simulation:

- Simulate the SoC estimation algorithm in software environments such as MATLAB/Simulink.


#### Performance Optimization:

- Fine-tune the UKF parameters to achieve optimal estimation accuracy and robustness.
- Analyze the algorithm's response to noisy measurements, disturbances, and changes in battery characteristics.
