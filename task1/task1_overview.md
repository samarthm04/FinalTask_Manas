Task 1 - Power stage and System Architecture

The following task involves designing a 5V and 3.3V linear regulator breakout PCB using ICs KF50BD-TR and MCP1700T-3002E/TT in KiCAD.

**Why do we need a linear voltage regulator?**

The final task involves designing an electronic speed controller(ESC) for the drone.


The microcontroller on the ESC requires a power source, typically supplied by the same power source used to power the motor. 
However, the supply voltage of a microcontroller is usually 5V or 3.3V, and motors run at higher voltages.
Thus, one must implement a step-down operation and ensure the power supply is stable and provides enough currentto power both the microcontroller and the motor.

To ensure stable power, the ESC uses a voltage regulator to regulate the voltage supplied to the microcontroller.
This helps prevent the microcontroller from being damaged by voltage spikes or drops in the power supply.



SCHEMATIC FOR TASK1 
![image](https://user-images.githubusercontent.com/110652550/235357321-13b1a58d-40c6-4600-9f16-6d17ad68feb6.png)


PCB FOR TASK 1

<img src="https://user-images.githubusercontent.com/110652550/235358810-f4563439-307f-464a-8a15-759242941c73.png" width="50%" height="50%" />

3D model of the PCB

<img src="https://user-images.githubusercontent.com/110652550/235358919-34def6db-a242-429a-96ad-df5342c3dc39.png" width="50%" height="50%" />


