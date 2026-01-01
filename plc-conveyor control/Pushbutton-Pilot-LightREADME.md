# PLC Pushbutton & Pilot Light Logic  
### Guided Practice 2.2 — EET231  
### LaDarius Roberts

## Overview  
This project demonstrates basic PLC input/output behavior using pushbuttons (PB1, PB2) and pilot lights (PL1–PL4). The goal was to observe how different input conditions affect the output indicators and document the resulting system behavior.

## Tools and environment  
- **Platform:** Course PLC simulation environment  
- **Programming language:** Ladder logic  
- **I/O types:** Discrete pushbuttons and pilot lights  

## Tag description  
- **PB1:** Pushbutton 1 (input)  
- **PB2:** Pushbutton 2 (input)  
- **PL1:** Pilot Light 1 (output)  
- **PL2:** Pilot Light 2 (output)  
- **PL3:** Pilot Light 3 (output)  
- **PL4:** Pilot Light 4 (output)  

## Observed system behavior  

- **Case 1: PB2 pressed**
  - PL3 lights momentarily  
  - PL3 turns off and PL4 turns on  

- **Case 2: PB1 pressed, then PB2 pressed**
  - When PB1 is pressed, PL1 and PL2 light  
  - When PB2 is pressed afterward, nothing changes  

- **Case 3: PB1 inactive, PB2 pressed**
  - When PB1 is pushed, nothing
