# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

![Screenshot 2025-03-24 122239](https://github.com/user-attachments/assets/c22930fc-f396-4787-807d-51088ad7959e)



## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:
 <img width="1920" height="1080" alt="Screenshot 2025-10-04 112528" src="https://github.com/user-attachments/assets/36ac8ff7-4a9b-499f-9cf2-4a4f05aeb8de" />
 <img width="968" height="304" alt="image" src="https://github.com/user-attachments/assets/f3f783ee-515f-47e4-9026-de3c736e65cf" />

## Output

#### 1. Transient Analysis Output:
<img width="1920" height="1080" alt="Screenshot 2025-10-04 113309" src="https://github.com/user-attachments/assets/04445f3c-de5f-44d8-8352-c6aad284eee9" />
<img width="1920" height="1080" alt="Screenshot 2025-10-04 113232" src="https://github.com/user-attachments/assets/e60490d3-d4e2-47c9-8c49-9d56a821251c" />
<img width="1920" height="1080" alt="Screenshot 2025-10-04 113207" src="https://github.com/user-attachments/assets/fa847043-97d4-48a4-b7a9-5dc16abe9e26" />


## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


