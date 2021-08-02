# VSD_PLL_using_sky130nm_PDK

Table of contents
=================
<!--ts-->
   * [Day 1](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#day-1)
      * [Introduction to Phase Locked Loop(PLL)](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#introduction-to-physical-design-flow)
      * [Phase Locked Loop(PLL) Specification](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#introduction-to-openlane-flow)
      * [Circuit description](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#openlane-directory-structure)
      * [Tool Setup](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#openlane-directory-structure)
   * [Day 2](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#day-2)
      * [Design prepartion and synthesis flow](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#design-prepartion-and-synthesis-flow)
      * [Floorplan](https://github.com/manjunathrv/VSD_Advanced_Physical_Design_with_sky130nmPDK#design-prepartion-and-synthesis-flow)

# Day 1 

## Introduction to Phase Locked Loop(PLL)
A Phase Locked Loop generates a precise clock signal, <br/>
The components of the PLL are described in the block diagram below, <br/> 

<img src="Images/Day_1_1b.PNG" width="600"> <br/> 

| Components                     | Description           |
|--------------------------------|-----------------------|
| Phase Frequency Detector (PFD) | Total power draw over |
| Charge Pump (CP) | Depends on the available capacity of the power source  |
| Low Pass Filter(LP) | Form factor and size of the battery  |
| Voltage Control Oscillator (VCO) | Form factor and size of the battery  |
| Frequency Divider (FD) | Form factor and size of the battery  |

## Phase Locked Loop(PLL) Specification 
The PLL specification are described below, 

| Specification                     | Value           |
|--------------------------------|-----------------------|
| Corner | TT (Typical) |
| Supply Voltage | 1.8V  |
| Temperature | 25 DegC (Room Temperature) |
| Modes | VCO Mode and PLL mode |
| Input Frequency | Fmin = 5Mhz and Fmax = 12.5Mhz  |
| Mutiplier| Form factor and size of the battery  |
| Jitter (RMS) | <~20ns  |
| Duty Cycle | 50%  |

## Circuit description 
The PLL specification are described below, 

| Specification                     | Value           |
|--------------------------------|-----------------------|
| Corner | TT (Typical) |
| Supply Voltage | 1.8V  |
| Temperature | 25 DegC (Room Temperature) |
| Modes | VCO Mode and PLL mode |
| Input Frequency | Fmin = 5Mhz and Fmax = 12.5Mhz  |
| Mutiplier| 8x  |
| Jitter (RMS) | <~20ns  |
| Duty Cycle | 50%  |

## Tool Setup
The tools and the setup details used for the development of the PLL are given below, 
| Tool                     | Description           | Setup details | 
|-----------------|---------------|-----------------------|
| Ngspice | Circuit Simulation | sudo apt-get install ngspice | 
| Magic | Layout Design  | Setup described in https://opencircuitdesign.com/magic |



# Day 2 

## Introduction to Phase Locked Loop(PLL)
A Phase Locked Loop generates a precise clock signal, <br/>
The components of the PLL are described in the block diagram below, <br/> 

| Components                     | Description           |
|--------------------------------|-----------------------|
| Phase Frequency Detector (PFD) | Total power draw over |
| Charge Pump (CP) | Depends on the available capacity of the power source  |
| Low Pass Filter(LP) | Form factor and size of the battery  |
| Voltage Control Oscillator (VCO) | Form factor and size of the battery  |
| Frequency Divider (FD) | Form factor and size of the battery  |












