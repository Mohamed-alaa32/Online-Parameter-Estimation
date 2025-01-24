# Online-Parameter-Estimation

| **Team Members** | **Accounts**      |
|-------------------|-------------------|
| Adham Waleed     |      [@AdhamWaleed](#)         |
| Mohamed Alaa     |                   | 
| Marwan Mahmoud   |        [@Marwan Mahmoud](#)             |
| Omar Khaled      |       [@Omar61554](#)              |
| Omar Emad        |          [@Omar Emad](#)           |

## Introduction
This project aims to build a mathematical model for a mechatronic system, estimate its parameters, and validate its performance. The system, a **DC motor-driven linear motion unit**, is experimentally tested to collect input and output data. The following tasks are performed:

1. Develop a mathematical model of the DC motor system.
2. Experimentally test the system to collect input and output data.
3. Replicate the system model in Simulink.
4. Use the **Parameter Estimation Tool** to determine system parameters.
5. Compare the simulated response with the physical model to evaluate accuracy and identify discrepancies.

This work highlights the application of **modeling**, **simulation**, and **parameter estimation methodologies** in engineering practice.

## Key Features
- Experimental testing of the DC motor system.
- Accurate mathematical model development.
- Simulation using MATLAB/Simulink.
- Parameter estimation and performance validation.

## System Overview
The mechatronic system includes:
- A **DC motor** for driving linear motion.
- Sensors to capture input (voltage) and output (position/speed).
- Experimental setup for real-time data collection.

The collected data is used for:
- Identifying system parameters like resistance, back EMF constant (Κₒ), torque constant (Κᵀ), and efficiency.
- Validating the accuracy of the Simulink model.

## Methodology
1. **Experimental Data Collection**: Input voltage and output motion are recorded for various conditions.
2. **System Modeling**: The DC motor's equations are derived and implemented in Simulink.
3. **Parameter Estimation**: Using MATLAB's Parameter Estimation Tool to tune parameters for best fit with experimental data.
4. **Validation**: Compare simulated results with physical measurements.

## Results and Validation
Below are some visual results from the project:

### Simscape Model
![Simscape Model Full](https://github.com/user-attachments/assets/4f213528-5d4c-4da9-b71b-1759b2512ff2)

### GUI

![GUI Arduino](https://github.com/user-attachments/assets/87b83e5d-8abd-4bbc-977e-53d4d041585d)



### Experimental vs Simulated Response
![Param8](https://github.com/user-attachments/assets/4e8eb7ee-062b-4c0a-98e9-8f7934fcaa69)



### Full Assembly
![Physical Model CAD 1](https://github.com/user-attachments/assets/e28441fb-067c-4037-9462-3e07f14f2d56)
![Physical Model CAD 2](https://github.com/user-attachments/assets/42f58945-9f62-4baf-9692-398c6ae3026f)


## Report
For detailed explanations, derivations, and results, please refer to the full report [here](https://drive.google.com/file/d/1yMU4xLJWwgrSheOeOfZTUfycAGEJT1Sy/view).
<!-- ![My_QR_Code_1-4096](https://github.com/user-attachments/assets/adf08ca2-53db-4251-9062-28494695b95b) -->


