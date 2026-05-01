## Table of Contents

- [Summary](#summary)
- [Overview of Tools](#overview-of-tools)
    - [Parallel Impedance Solver](#parallel-impedance-solver)
    - [Wye-Delta Conversion Tool](#wye-delta-conversion-tool)
    - [Phasor-Calculation Engine](#phasor-calculation-engine)

# Summary

A suite of custom-built applications for the TI-84 calculator designed to streamline common circuit analysis tasks. These tools reduce repetitive computation, minimize human error, and accelerate problem-solving in steady-state and network analysis.

## Overview of Tools
This library houses multiple circuit-analysis applications designed to give young EE students a competitive edge and teach the power of script automation.

### Parallel Impedance Solver

Computes equivalent impedance for  components in parallel networks.  This application can be used on simple resistive networks or may be used in combining complex impedances in phasor domain analysis. 

Here is a guide on how to use it:

1.) Click PRGRM on your TI-84.  
2.) You should see the application's Home Screen.  
![Equivalent Impedance Graphic 1](EqImpedIntro.jpg)  
3.) The application will prompt you for how many impedances are in the parallel network you want to combine. You may enter up to 5. Now enter each value when prompted.
![Equivalent Impedance Graphic 2](EqImpedDemo.jpg)  
4.) The application will now display the array it stores the values in. Click enter.  
5.) The application will now display the equivalent impedance in rectangular form.
![Equivalent Impedance Graphic 1](EqImpedResult.jpg)  





### Wye–Delta Conversion Tool
Quickly converts between Wye (Y) and Delta (Δ) configurations, eliminating tedious algebra. Before inputting any values, the application displays an orientation diagram to help the user map the current circuit to the transformation. Below are steps to use the application

1.) Click on PRGRM on your TI-84.  

2.) You should see the Home Screen.  

![Delta-Wye Conversion Graphic1](DWIntro.jpg) 

3.) The application will notify you of an incoming diagram to help you orient and convert your values to be used in the program:    

![Delta-Wye Conversion Graphic2](DWPrompt.jpg)   

4.) The application will display the aformentioned diagram :    
![Delta-Wye Conversion Graphic3](DWDiagram.jpg)   

5.) Input your values.

6.)Redraw your converted circuit with the new values.


### Phasor Calculation Engine 
Performs arithmetic on phasors in both:

Rectangular form (a + jb)
Polar form (magnitude ∠ angle)

Designed to simplify steady-state sinusoidal analysis, including addition, subtraction, multiplication, and division.
