# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

<img width="1919" height="1190" alt="Screenshot 2026-02-21 135700" src="https://github.com/user-attachments/assets/8d466eac-01d1-4b7e-8713-f6a7f3c815a8" />
<img width="1916" height="1199" alt="Screenshot 2026-02-21 135547" src="https://github.com/user-attachments/assets/7f292389-529a-4a47-ba55-cf60a5ae5a7e" />

### Schematicand Symbol of 2-Input EX-OR Gate:


<img width="1919" height="1199" alt="Screenshot 2026-02-23 090031" src="https://github.com/user-attachments/assets/6fa05ad3-ff53-4b74-98dc-78c29e581455" />
<img width="1919" height="1199" alt="Screenshot 2026-02-23 090008" src="https://github.com/user-attachments/assets/4a88d9dd-c65f-49a7-b9b6-c5832a4a32ca" />


### Schematicand Symbol of Half Adder:
<img width="1918" height="1199" alt="Screenshot 2026-02-26 080717" src="https://github.com/user-attachments/assets/d83a0f86-146d-4a5a-929f-a55997e9fab7" />
<img width="1919" height="1199" alt="Screenshot 2026-02-26 080921" src="https://github.com/user-attachments/assets/21c68bb2-7c2f-460b-a4e6-08c7aa267961" />


## Output
### Transient Analysis Output:
<img width="866" height="698" alt="Screenshot 2026-02-26 094813" src="https://github.com/user-attachments/assets/eccf0346-b605-4cef-90ef-639755e3eead" />

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)

<img width="512" height="663" alt="Screenshot 2026-02-26 094832" src="https://github.com/user-attachments/assets/af803582-eb77-427a-871b-b004ba92dc77" />

<img width="1918" height="1199" alt="Screenshot 2026-02-26 094742" src="https://github.com/user-attachments/assets/cad2be82-a611-41bc-9966-913f21b79c8f" />


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
