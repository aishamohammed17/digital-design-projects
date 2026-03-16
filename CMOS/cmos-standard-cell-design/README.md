# CMOS Inverter Design (GPDK45nm)

## Brief Overview
Designed and characterized CMOS standard cells using gpdk45nm technology. 

## Tools
- Cadence Virtuoso
- Spectre
- gpdk45nm

## Cells Implemented:
- INVx1
- NAND2x1
- NOR2x1

## Design Architecture
Each logic gate was implemeted using complementary:
- PMOS pull-up network
- NMOS pull-down network

Transistor sizes were adjusted to balance rising and falling propagation delays.

## Layout
Layouts were created following standard cell design practices including:
- diffusion sharing  
- minimal routing  
- power rail alignment  

All layouts passed DRC and LVS verification.

## Simulation
Transient simulations were performed to measure switching characteristics.

## Metrics analyzed:
- propagation delay  
- rise time  
- fall time  

## CMOS Inverter (INVx1)

### Schematic
[paste image]

### Layout
[paste image]

### Transient Simulation
[paste waveform]

---

## NAND2 Gate

### Schematic
[paste]

### Layout
[paste]

### Simulation
[paste]

---

## NOR2 Gate

### Schematic
[paste]

### Layout
[paste]

### Simulation
[paste]

---

### Results
## Observations
- PMOS devices require larger widths to balance pull-up strength  
- NAND gates typically exhibit faster falling transitions due to parallel NMOS devices  
- NOR gates tend to have slower rising transitions due to series PMOS devices
