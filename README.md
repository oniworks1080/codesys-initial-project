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

For a better understanding of how the system works, included are screenshots and demonstration video.

- **Variables**
<img width="2553" height="1400" alt="Program Variables" src="https://github.com/user-attachments/assets/79baceb3-ff1c-4313-b782-98b3837efdcb" />

- **Ladder Logic & HMI**
<img width="1907" height="962" alt="Program LD and HMI" src="https://github.com/user-attachments/assets/af618344-570d-4c41-9e2a-4fc0656b0db3" />

- **Demo GIF**
https://github.com/user-attachments/assets/a7fcc268-2ec6-45a0-b652-f57e58b79905


