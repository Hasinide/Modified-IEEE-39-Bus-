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
| Diagrams | Control block diagram for GFLI | Control structure of PV GFL and PV plant block diagram |
| Diagrams | Droop control diagram for GFMI | Active and reactive power droop control structure |
| Diagrams | VSM control diagram for GFMI | VSM control diagram |

The GFM droop control model for the BESS plant is based on the Technical reference of DIgSILENT Grid-forming Converter Templates[3].
The EMT model for GFL PV plant is based on DIgSILENT Powerfactory Technical Reference for the PV Systems [4].

References

[1] DIgSILENT PowerFactory: "39 Bus New England System", 2024.

[2] Working Group C4.503, "Power System Test Cases for EMT-Type Simulation Studies," 2018. [Online] Available: https://www.e-cigre.org/publications/detail/736-power-system-test-cases-for-emt-type-simulation-studies.html 

[3] DIgSILENT PowerFactory 2024, "Technical Reference-DIgSILENT Grid-forming Converter Templates (Droop Controlled Converter, Synchronverter, Virtual Synchronous Machine)",2024.

[4] Technical Reference PV System. Heinrich-Hertz-Strasse 9, 72810 Gomaringen / Germany, 2019.


