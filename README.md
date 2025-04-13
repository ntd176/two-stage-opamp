# two stage opamp
Project topic: design of a unbuffer opamp on 180nm CMOS technology. This is the final project for the AID course.
The teacher provided the topology structure, along with specific design requirements.
My simulation results based on the design specifications are presented in the table below: 
| **Parameter**    | **Specification** | **Simulation Result** |
|:----------------:|:-----------------:|:----------------------:|
| **Av** (Gain)          | > 3000 V/V         | 2400 V/V              |
| **GB** (Gain Bandwidth)| 5 MHz              | 19 MHz                |
| **SR** (Slew Rate)     | > 10 V/μs          | Rise: 5.08 V/μs  <br> Fall: 2.54 V/μs |
| **PM** (Phase Margin)  | 60°                | 115°                  |
| **V<sub>out</sub> Range**  | -0.5 V → 0.5 V     | -0.3 V → 0.7 V        |
| **ICMR**               | -0.5 V → 0.5 V     | -0.8 V → 0.7 V        |
| **P<sub>diss</sub>** (Power Dissipation) | < 3 mW            | 1.44018 mW           |
