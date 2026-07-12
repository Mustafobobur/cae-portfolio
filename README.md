# cae-portfolio
CAE simulation portfolio projects — FEA analysis and validation studies
📄 [View Project 1: Cantilever Beam Analysis (PDF)](./Cantilever%20Beam%20Analysis%20–%20Portfolio%20Project%201.pdf)


## Project 2: Piston-Crankshaft Mechanism

### Overview

<img width="1037" height="602" alt="Снимок экрана 2026-07-12 165316" src="https://github.com/user-attachments/assets/8c75fe7a-560a-4506-8383-95f306d57805" />



Designed a three-part mechanical assembly modeling the core motion-conversion mechanism found in combustion engines: a crankshaft, connecting rod, and piston. Built as an Assembly Design in Fusion 360 with independent components joined via revolute joints.

### Components

<img width="756" height="508" alt="Снимок экрана 2026-07-12 165344" src="https://github.com/user-attachments/assets/0581372f-6c90-4513-9754-b2c5ec8623f0" />
<img width="787" height="612" alt="Снимок экрана 2026-07-12 165331" src="https://github.com/user-attachments/assets/2cc3c3f1-0187-428d-be1a-c1e5b02d576a" />
<img width="1918" height="1078" alt="Снимок экрана 2026-07-12 165120" src="https://github.com/user-attachments/assets/5801e365-b1bc-4857-8300-4c1ebd8c6758" />

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

