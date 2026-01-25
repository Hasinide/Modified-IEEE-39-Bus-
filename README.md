# Modified-IEEE-39-Bus-with 72% IBR penetration

The repository provides data and model files for a modified IEEE 39-bus test system with approximately 72% inverter-based resource (IBR) penetration. Starting from the original IEEE 39-bus system models presented in [1] and [2], the network has been modified to represent a high-IBR scenario suitable for parallel power system restoration studies.

The contents of this repository enable the construction and analysis of a network configuration comprising two restoration islands, facilitating EMT-based investigations of island synchronization and parallel restoration in converter-dominated grids.

| Type | Network component | Contents |
|---------|-------------|-------------|
| Network model data | Generator data | Synchronous generators, GFM units, GFL PV units |
| Network model data | Load data | Load models and parameters |
| Network model data | Transformer data | Transformer impedance data |
| Network model data | Transmission line models | Line conductor types and modelling approaches |
| Network model data | Transmission line data | Transmission line impedance data |
| Diagrams | Overall detailed SLD | Complete system single-line diagram |
| Diagrams | Control block diagram for GFMI | Control structure of grid-forming inverter |
| Diagrams | Droop control diagram for GFM | Active and reactive power droop control structure |




References

[1] DIgSILENT PowerFactory: "39 Bus New England System", 2024

[2] M. A. Pai: “Energy Function Analysis for Power System Stability”, Kluwer Academic Publishers, Boston/Dordrecht/London, 1989, ISBN: 0-7923- 9035-0, ISBN-13: 978-1-4612-8903-6
