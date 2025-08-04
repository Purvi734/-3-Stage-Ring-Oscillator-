# 3 Stage Ring Oscillator
Design and Implementation of a 3 Stage Ring Oscillator on Cadence Virtuoso 
This project involves the design, simulation, layout, and verification of a 3-stage CMOS ring oscillator using Cadence Virtuoso and 180nm technology. The oscillator is implemented using three cascaded CMOS inverters and demonstrates self-sustained oscillation due to the odd number of inversions and feedback
## Tools & Technology
EDA Tool: Cadence Virtuoso

Technology Node: 180nm CMOS PDK

Verification: Assura (DRC & LVS)

## Design Details
Implemented a 3-stage inverter-based ring oscillator using standard CMOS logic.

Each inverter was sized for optimal drive strength to sustain stable oscillation.

Connected the output of the third inverter back to the input of the first to complete the feedback loop.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3c015cee-5562-4da2-9e22-59f0102ad66c" />


## Transient Analysis
Set the initial condition to 0 and then ran the ADE L.

Performed transient simulations to observe oscillation waveform.

Verified oscillation frequency and waveform shape across a range of supply voltages.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c6268597-7d1d-4443-a1fe-9bc8e655fc6b" />


## Layout and Physical Verification
Completed full custom layout of the ring oscillator using Cadence layout editor.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22a191e5-eb39-4457-9470-45b8bc2ca3c6" />

Ensured proper spacing, alignment, and design rule compliance.

## Performed:

### DRC (Design Rule Check) — No violations

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/16c7b00f-3252-4eff-81a2-a6bb0eb8934b" />


### LVS (Layout vs Schematic) — Netlist matched schematic


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/92d02933-75a4-444c-b227-d9825952f018" />



