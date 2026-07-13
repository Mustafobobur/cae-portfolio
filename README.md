# cae-portfolio
CAE simulation portfolio projects — FEA analysis and validation studies
📄 [View Project 1: Cantilever Beam Analysis (PDF)](./Cantilever%20Beam%20Analysis%20–%20Portfolio%20Project%201.pdf)


## Project 2: Piston-Crankshaft Mechanism

### Overview

<img width="1918" height="1078" alt="Снимок экрана 2026-07-12 165120" src="https://github.com/user-attachments/assets/5801e365-b1bc-4857-8300-4c1ebd8c6758" />





Designed a three-part mechanical assembly modeling the core motion-conversion mechanism found in combustion engines: a crankshaft, connecting rod, and piston. Built as an Assembly Design in Fusion 360 with independent components joined via revolute joints.

### Components
  <img width="1037" height="602" alt="Снимок экрана 2026-07-12 165316" src="https://github.com/user-attachments/assets/8c75fe7a-560a-4506-8383-95f306d57805" />
  <img width="787" height="612" alt="Снимок экрана 2026-07-12 165331" src="https://github.com/user-attachments/assets/2cc3c3f1-0187-428d-be1a-c1e5b02d576a" />
  <img width="756" height="508" alt="Снимок экрана 2026-07-12 165344" src="https://github.com/user-attachments/assets/0581372f-6c90-4513-9754-b2c5ec8623f0" />





- **Crankshaft**: main journal, offset crank pin, and web plate — the offset geometry converts rotational motion into the crank pin's circular sweep
- **Connecting rod**: dog-bone profile with two pin holes, linking the crank pin to the piston
- **Piston**: cylindrical body with a pin hole through the center

### What I Learned
- Assembly Design workflow: creating independent components vs. single-part modeling
- Joint types (Revolute) and how joint chains propagate motion between parts
- Debugging kinematic issues: fixed a hole diameter equal to material width (which fully removed the end material instead of leaving a ring), corrected component orientation using Move/Copy rotation, and diagnosed a broken joint chain by inspecting the Joints browser panel
- The importance of grounding a fixed reference point before building a moving joint chain

### Status
Core geometry and pin-to-pin joints are complete and correctly oriented. The base rotation constraint (crankshaft to a fixed ground reference) is the next step to get the full mechanism animating end-to-end.



Wooden Chair — Fusion 360 Model

A parametric 3D model of a classic wooden dining chair, designed in Autodesk Fusion 360. Features a slatted vertical backrest, tapered legs, and a solid seat panel.


<img width="1920" height="632" alt="Wooden_chair_2026-Jul-13_04-28-29PM-000_CustomizedView11755699382" src="https://github.com/user-attachments/assets/5971c5b7-1ab8-4ada-a79c-5b05abc7f2c1" />
<img width="1920" height="632" alt="Wooden_chair_2026-Jul-13_04-24-18PM-000_CustomizedView45224735462" src="https://github.com/user-attachments/assets/93d6f839-ef1d-42a9-98f5-0ca40e5239e7" />



Design Details

<img width="1918" height="1078" alt="Снимок экрана 2026-07-13 212659" src="https://github.com/user-attachments/assets/15b5a642-c530-45a4-b68d-b92e521d1409" />



Style: Traditional slat-back dining chair
Backrest: Vertical slats set into a curved top rail, two-tier construction
Seat: Solid flat panel, slightly wider at the front than the back
Legs: Four straight tapered legs with front and side stretchers for stability
Material (visual): Stained wood finish, warm medium-brown tone
Software: Autodesk Fusion 360, modeled as a single parametric part



