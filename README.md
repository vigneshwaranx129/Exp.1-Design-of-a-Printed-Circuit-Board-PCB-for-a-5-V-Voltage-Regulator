# Exp.1-Design-of-a-Printed-Circuit-Board-PCB-for-a-5-V-Voltage-Regulator
## Aim

To design the schematic and PCB layout of a 5 V voltage regulator circuit using KiCad, perform electrical and design rule checks, and generate Gerber files for PCB fabrication

## Apparatus Required

1.Computer with KiCad (Version 8.0 or later)
2.7805 Voltage Regulator (TO-220 Package)
3.DC Input Connector (7–12 V)
4.Output Connector
5.Capacitor – 0.33 µF (Input)
6.Capacitor – 0.1 µF (Output)
7.Capacitor – 10 µF Electrolytic (Optional)
8.LED
9.330 Ω Resistor
10.PCB design libraries available in KiCad

## Circuit Diagram

<img width="1915" height="1198" alt="image" src="https://github.com/user-attachments/assets/e477c349-53fa-40a7-9ad9-cb3d6dd008f3" />


## Procedure

1.Open KiCad and create a new project.
2.Draw the schematic by placing the 7805 regulator, capacitors, resistor, LED, and connectors.
3.Assign proper net labels (VIN, +5V, GND).
4.Perform Electrical Rule Check (ERC) and rectify all errors, if any.
5.Assign suitable footprints to all schematic components.
6.Open the PCB Editor and import the netlist/schematic.
7.Arrange all components considering minimum track length and proper placement.
8.Define the board outline.
9.Route all PCB tracks using the required track width.
10.Create a copper fill (ground plane) connected to GND.

## Output

## PCB output:

<img width="1913" height="1198" alt="image" src="https://github.com/user-attachments/assets/db6d0eed-ba4f-4c4d-bb7b-24cd92b56d97" />

## 3D output:

<img width="1913" height="1198" alt="image" src="https://github.com/user-attachments/assets/fb107ed1-8a59-468d-8e92-ae9ba6370211" />
<img width="1915" height="1198" alt="image" src="https://github.com/user-attachments/assets/58cfc86f-4ed7-43f9-9f65-4266c7a7de68" />


## Result:

The PCB layout for the 5 V Voltage Regulator was successfully designed in KiCad. The schematic passed the Electrical Rule Check (ERC), the PCB passed the Design Rule Check (DRC) without errors, and the Gerber files required for PCB fabrication were successfully generated










11.Run the Design Rule Checker (DRC) and correct any reported violations.
12.Add reference designators, board title, and revision information.
Generate Gerber files and drill files for PCB fabrication.
