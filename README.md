# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME:CHANDRU P
## REGISTER NUMBER:212223110007
## DEPARTMENT:CSE(IOT)
## YEAR:3rd
## DATE:17-02-2026

### Aim:
To understand and implement various counter operations in Programmable Logic Controller (PLC) ladder logic.

### Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports counter functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger the counter operations.
Output Devices: LEDs or other indicators to visualize the counter outputs.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.

### Theory:
Counters in PLCs are used to count events or occurrences, such as the number of items passing on a conveyor belt, the number of cycles a machine runs, or how many times a process has started or stopped. Counters are commonly used in automation to perform tasks like stopping a machine after a set number of products or signaling a notification when a count reaches a specific value.

### Types of Counters:
Up Counter (CTU) Functionality:

The up counter counts every time the input condition becomes TRUE (ON). When the accumulated value reaches the preset value, the counter output becomes TRUE. If the reset input is triggered, the counter resets to zero.
Down Counter (CTD) Functionality:

The down counter decreases the count every time the input condition becomes TRUE (ON). When the count reaches zero, the counter output becomes TRUE. The counter can be reset by a reset input to the preset value.
Up/Down Counter (CTUD) Functionality:

The up/down counter can increment or decrement the count based on two different inputs. One input increments the count, while the other decrements it. When the count reaches the preset value or zero, the respective outputs become TRUE. The counter can be reset as required.


### Procedure:
Setup the PLC Programming Environment:
Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Counters:
Up Counter (CTU):

Create a rung with an input (e.g., a push button) linked to a CTU instruction.
Set the preset value (e.g., 10 counts). Assign an output to indicate when the preset value is reached.
Down Counter (CTD):

Create a rung with an input linked to a CTD instruction.
Set the preset value (e.g., 5 counts). Assign an output to indicate when the counter reaches zero.
Up/Down Counter (CTUD):

Create a rung with separate inputs for counting up and counting down.
Set the preset value (e.g., 8 counts). Assign outputs for when the count reaches the preset value or zero.
Simulate the Ladder Logic:
Up Counter (CTU):

Run the simulation in the PLC software. Press the input button repeatedly and observe the counter increment until the preset value is reached, at which point the output activates.
Down Counter (CTD):

Run the simulation, press the input button repeatedly, and observe the counter decrement. When the counter reaches zero, the output activates.
Up/Down Counter (CTUD):

Simulate both the up and down counting inputs. Observe how the counter increments or decrements and how the output is activated when the count reaches the preset value or zero.
Download and Execute:
Download the ladder logic program to the PLC if available and run it.
Test the counters with the physical push buttons and observe the LEDs or other output devices.
### Outputs:

## COUNTER:
<img width="1919" height="1079" alt="Screenshot 2026-02-10 103511" src="https://github.com/user-attachments/assets/ad9c30bb-5204-4833-9a33-47e0eaa9b685" />
<img width="1919" height="1079" alt="Screenshot 2026-02-10 103820" src="https://github.com/user-attachments/assets/b244d217-fd0c-4ba0-963c-5cbe672b7516" />

##  UP COUNTER(CTU):
<img width="1347" height="765" alt="Screenshot 2026-02-19 100516" src="https://github.com/user-attachments/assets/13ea352b-3b21-4467-b5c7-46efcdb1c4df" />
<img width="1890" height="1031" alt="Screenshot 2026-02-19 100505" src="https://github.com/user-attachments/assets/0a1dc5aa-61bd-4cc7-b621-bbbf5254ef9d" />

## DOWN COUNTER(CTD):

<img width="1003" height="533" alt="Screenshot 2026-02-19 190738" src="https://github.com/user-attachments/assets/76adcb6a-6693-4318-aa2e-3785b5f3f60e" />
<img width="1019" height="437" alt="Screenshot 2026-02-19 190748" src="https://github.com/user-attachments/assets/d7cc611f-3363-4fc3-b22c-a10c08d1e9a7" />

<img width="1915" height="1032" alt="Screenshot 2026-02-19 190708" src="https://github.com/user-attachments/assets/63557e55-aab3-4c0e-b8b5-fc0cb786a139" />

## UP DOWN(CTUD):
<img width="1224" height="547" alt="Screenshot 2026-02-19 192045" src="https://github.com/user-attachments/assets/655e082a-0b72-46a6-822a-c30f379cfea8" />
<img width="1219" height="496" alt="Screenshot 2026-02-19 192055" src="https://github.com/user-attachments/assets/56b4e193-9161-4895-a149-794492eb84f6" />
<img width="1917" height="1033" alt="Screenshot 2026-02-19 191942" src="https://github.com/user-attachments/assets/c724a6d0-9e74-4b2d-a920-6c07da539deb" />

<img width="1919" height="1032" alt="Screenshot 2026-02-19 192027" src="https://github.com/user-attachments/assets/ffcd5204-3000-4bfa-80a2-14e954aeb85f" />







### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
