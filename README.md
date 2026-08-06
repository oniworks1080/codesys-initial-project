# codesys-initial-project

## Overview
My initial exposure to using the Codesys IDE and some of its general capabilities such as ladder diagram, HMI design and tracing in the troubleshooting process.

---

## Key Components

### 1. **Buttons**:
   - **Reset Button**: Resets the whole circuit to its original state (all OFF).
   - **Stop Button**: Stops Start Buttons 2 & 3.
   - **Start Buttons 1**: Turns on Red Light.
   - **Start Buttons 2**: Turns on Red & Green Light.
   - **Start Buttons 3**: 
   Turns OFF Red Light | Turns ON Green Light & Motor 1 | Turns ON Motor 2 after 5 seconds | Turns OFF Fan after 10 seconds.


---

## How the System Works

Through a series of relays and contactors a certain sequence of loads will engage. In this particular program Start Button 2 is dependent on 1 and Start Button 3 is dependent on 2.

---

## How to Run the Project

1. **Install CODESYS**: Ensure that you have installed CODESYS on your system. Refer to the [CODESYS official website](https://www.codesys.com/) for installation instructions.
2. **Download the Project Files**: Import the project files into CODESYS.
3. **Compile and Run**: Compile the program and download it to the CODESYS runtime environment to simulate the elevator operation.

---

## Demo

For a better understanding of how the system works, included is a demo gif and a screenshot of the variables.
