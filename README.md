# Attenuation Measurement 2.5 GB & 10 GB
# Attenuation-Limited Fiber Length

## Objective
- Calculate the attenuation-limited fiber length based on the power budget equation.  
- Simulate the resulting system and verify that it meets performance objectives.

---

## Theory
The **power budget equation** states that the power budget in a transmission system must equal the sum of all power losses plus the power margin.  

The power budget is the difference between the transmitter output power and the receiver sensitivity in dBm:

<img width="994" height="468" alt="image" src="https://github.com/user-attachments/assets/28074fe1-e571-4356-bf4c-29cf212c8173" />

In this exercise, all parameters are given except the fiber length, which must be determined.  

The **receiver sensitivity** is defined as the minimum power required to achieve a BER of <img width="54" height="38" alt="image" src="https://github.com/user-attachments/assets/56f53e67-161a-4d53-ba6e-e31a3725ea43" />, corresponding to a Q factor of 6.  
- Receiver sensitivity depends on the bit rate.  
- Fiber attenuation depends on the operating wavelength.  

---

## Pre-lab Calculations
Using the power budget equation and the parameters below, determine the attenuation-limited fiber length:

- **Transmitter output power:** 0 dBm  
- **Operating wavelength:** 1550 nm  
- **Bit rate:** 2.5 Gb/s  
- **Receiver sensitivity:** -30 dBm  
- **Fiber attenuation:** 0.19 dB/km  
- **Number of connectors:** 2  
- **Loss per connector:** 0.5 dB  
- **Additional known losses:** 0 dB  
- **Power margin:** 6 dB  

---

## Layout
- The system has been created using **OptiSystem** and exported as an **OptiPerformer** file.  
- Two versions exist: one for **2.5 Gb/s** and one for **10 Gb/s**.  
- Work with the **2.5 Gb/s** version first.  
- An optical attenuator represents connector loss and system margin.  
- Adjust parameters according to the table above.  
- Dispersion and nonlinear effects in the fiber are disabled.  
- To set the receiver sensitivity to -30 dBm for 2.5 Gb/s, set the **thermal noise parameter** in the receiver to **8.97e-24 W/Hz**.  
- Visualizer components are included to obtain necessary simulation data.  

---

## Simulation
1. Run the simulation and record:
   - **Optical power levels (dBm):**
     - Both ends of fiber  
     - Receiver input  
   - **BER analysis:**
     - BER  
     - Q factor  
     - Eye diagram  

2. Set the fiber length to **125% of the calculated pre-lab value** and repeat the simulation and data recording.  

---


- # For 2.5 GB

 <img width="1600" height="558" alt="WhatsApp Image 2026-04-22 at 11 41 33 AM" src="https://github.com/user-attachments/assets/20dbb66d-b95c-4f39-9d5c-596ceed9b4c2" />


  <img width="1600" height="1026" alt="WhatsApp Image 2026-04-22 at 11 41 33 AM (1)" src="https://github.com/user-attachments/assets/f28b6a37-8cfe-4cf3-8962-65011e7fc5b1" />

<img width="1920" height="1080" alt="Screenshot (297)" src="https://github.com/user-attachments/assets/607f2297-afaa-48f5-9ae2-5fa49d55b4bb" />

# For 10 GB

<img width="1600" height="558" alt="WhatsApp Image 2026-04-22 at 11 41 33 AM" src="https://github.com/user-attachments/assets/7a1de671-20af-4798-bc5b-930a85148c4e" />

 <img width="1600" height="1265" alt="WhatsApp Image 2026-04-22 at 11 41 33 AM (2)" src="https://github.com/user-attachments/assets/a1272ea2-b4f1-4d30-8196-8a4f952b822b" />






<img width="1920" height="1080" alt="Screenshot (298)" src="https://github.com/user-attachments/assets/1c42eaa2-5c4c-4403-baea-dceb5c783030" />

## Result

Thus the Experiment was succesfully completed and output is verified.

