# Project
# Alaram Countdown using Arduino in SimulIde
## Table of Content:
* Features
* Description
* Objective
* Block Diagram
* Flow Chart
* Components
* Requirements
* Test Plan
* Code
* Circuit Diagram PNG
* Code Simulation PNG
* Further Development
* SWOT Analysis
* 4W's & 1H
* Output PNG
## Features:
* Displays countdown which trigerrs the buzzer alarm.
* After entering the correct password the buzzer will be deactivated.
## Description:
* This project focuses on developing an Alarm Arduino Uno circuit, with a buzzer sound with a 10 seconds countdown, user needs to enter the correct password to deactivate the connection and to turn off the alarm.
## Objective:
* To make an Alarm circuit using Arduino and to implement it using SimulIde.
## Block Diagram
![image](https://user-images.githubusercontent.com/98816218/156927288-7e352645-1c04-435e-b3cf-a5731112d4ab.png)
## Flow Chart
![image](https://user-images.githubusercontent.com/98816218/157063670-43875a5c-3457-4a55-9265-70536e6ef07d.png)
## Components:
* Arduino Uno 45
* 16x2 LCD Display Hd44780
* 4x3 Numeric Keypad
* Buzzer
* Power source
* LED
* Resistor
## Requirements:
* High Level Requirements:

|  ID  |  Description  |
| ------  | ------  |
|  HLR1  |  Knowledge of Arduino  | 
|  HLR2  |  Writing the code  |
|  HLR3  |  Making the Circuit  |

* Low Level Requirements:

|  ID  |  Description  |
|  ------  |  ------  |
|  LLR1  |  Knowledge of Components   |
|  LLR2  |  Adding necessary library files in Arduino  |
|  LLR3  |  Implimenting circuit in Simu Ide  |

## Test Plan
# High Level Test Plan
|  Test ID  |  Description  |  Expected Input  |  Expected Output  |  Status  |
| ------  | ------  | ------ | ------ | ------ |
|  H01  |  Writing Code  |  Compiling the Code  |  No Errors  |  Implemented  |   
|  H02  |  Generating Hex FIle  |  Hex File  |  Hex File  |  Implemented  |
|  H03  |  Making the Circuit  |  Components  |  Circuit  |  Implemented  |
|  H04  |  Buzzer  |  Component  |  Buzzer sound  |  Implemented  |

# Low Level Test Plan
|  Test ID  |  Description  |  Expected Input  |  Expected Output  |  Status  |
| ------  | ------  | ------ | ------ | ------ |
|  L01  |  Library files  |  Added Library files  |  Execution without Errors  |  Implemented  |   
|  L02  |  Countdown display  |  Run  |  Display  |  Implemented  |
|  L03  |  Circuit   |  Implementing Circuit    |  Run Circuit  |  Implemented  |
## Code
*
## Circuit Diagram
![image](https://user-images.githubusercontent.com/98816218/156929051-3700f6ed-bd29-4d03-b7bc-fe5e0882810f.png)
## Code Simulation
![image](https://user-images.githubusercontent.com/98816218/156929105-43c719a5-45b8-4f94-b2e0-281f6cd7d910.png)
## Further Development:
* We can extend this project features by adding humidity, Air Quality display and even upgrade this into automatic light system and Visitor Counter System.
* For displaying Humidity we can use Hygrometer 
* For displaying Air Quality we can use Optical sensors, Metal Oxide Sesnor(To measure Nitrogen, Oxygen and Carbondioxide),Photo Ionization Sensor.
* For Visitor Counter we can use Ultra Sonic Sensor.
* For Automatic Light Sytem we can PIR Sensor. 
## SWOT Analysis:
* Strenghts: Count down alarm

* Weakness: If the user enters wrong password buzzer wont go off, there is no reset option. 

* Oppurtunities: Can be extended for displaying Humidity, Air Quality etc.

* Threats: No major threats

## 4W's & 1H:
* Who: Can be used by every person
* What: For calculating countdown
* When: Can be utilized when a person needs an alarm.
* Where: House, Offices
* How: By using Arduino and other components.
## Output
![image](https://user-images.githubusercontent.com/98816218/156928634-2e04679a-e9d0-482d-beaa-d4b733d71f39.png)
