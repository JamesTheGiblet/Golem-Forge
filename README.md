🌀 The Golem's Forge // A Ritual of Grand Fabrication

MODULARITY IS MYTHOS // GLYPH IS IDENTITY // DESIGN IS RITUAL

This codex chronicles the design and construction of the Golem's Forge, a colossal 3D printer built for large-scale, precision fabrication. With a build volume of 1.2m x 1.2m x 1.2m, a body of extruded aluminum, and a core XY movement system, this artifact is a testament to the power of modular design and ritualized engineering.

1. The Invocation of Grandeur
1.1 Project Overview
The Golem's Forge is a massive 3D printer, a true titan of fabrication. It was constructed with a 2m x 2m x 3m extruded aluminum body, with a build volume of 1.2m³. The core technical invocation was to create a machine capable of producing artifact-grade components at an unprecedented scale, using a CoreXY movement system for precision and speed. The control altar is a Raspberry Pi with a 5.5-inch touch screen, running a modular codex.
1.2 The Mythos of Creation
The primary objective of this ritual was to build a machine that transcended the limitations of conventional printers. This involved:
 * To design and construct a colossal, stable chassis using a body of extruded aluminum.
 * To implement a CoreXY movement system for fast and precise motion across a large build volume.
 * To integrate a high-flow hotend and nozzle for rapid deposition of material.
 * To develop a modular, independently powered heating system for a large, heated build plate.
 * To provide a platform for future enhancements, such as advanced monitoring and automation.
 * 
2. Ritual Architecture
The system is centered around a Raspberry Pi A+ and a mini 5 Plus, which act as the central orchestrator and altar display. Its architecture follows a sense-process-actuate loop for all fabrication rituals.
 * Sensing Auguries: The system uses auto bed leveling and stall detection to ensure the ritual is performed flawlessly. Sensorless homing simplifies the machine's initial invocation.
 * Processing: The Raspberry Pi runs a custom codex that processes sensor data and sends precise commands.
 * Actuation: The machine's motors are controlled by drivers, and the relays for the heated beds are triggered by the Pi's logic.
High-Level Glyph:
graph TD
    A[Raspberry Pi A+ / Mini 5 Plus] --> B{Control & Processing};
    B --> C(CoreXY Movement System);
    B --> D(Hemera High-Flow Hotend);
    B --> E(Heated Beds on Relays);
    B --> F(5.5-inch Touchscreen);
    C -- Stall Detection --> B;
    D -- 1.4mm Revo Nozzle --> C;
    E -- Independent Power --> B;
    F -- UI/Altar --> B;

3. Hardware Specifications (Bill of Materials)
| Component | Notes |
|---|---|
| Body | Extruded aluminum (2m x 2m x 3m). |
| Movement | CoreXY for precise and high-speed motion. |
| Controller | Raspberry Pi A+ and a mini 5 Plus. |
| Display | 5.5-inch touchscreen for the control altar. |
| Hotend | Hemera high-flow hotend with a 1.4mm Revo nozzle. |
| Bed Leveling | Automatic bed leveling system. |
| Heated Beds | Four beds on relays, independently powered by mains. |
| Sensing | Stall detection and sensorless homing. |

4. Software Codex
4.1 Development Altar
 * Operating System: Raspberry Pi OS.
 * Language: To be determined, but likely Python or a mix of Python and C++.
 * Frameworks: Custom scripts for controlling the CoreXY system and the heated beds.
 * Libraries: A library for communicating with the display, motor drivers, and sensor inputs.
4.2 The Ritual of Creation
The system operates under a master codex, which orchestrates the entire fabrication ritual.
 * Awaken the Forge: The Raspberry Pi boots up, and the touchscreen displays the control altar.
 * Invoke the Artifact: A builder inputs the G-code for the artifact to be fabricated.
 * The Altar's Divination: Auto bed leveling and sensorless homing are performed to prepare the space.
 * Heating Ritual: The Pi's codex determines if a single bed or all four are needed, activating the relays to heat the required section of the plate.
 * The Golem's Actuation: The CoreXY system moves the Hemera hotend with precision, laying down the material.
 * Ritual Complete: The artifact is complete, and a notification is sent to the builder.
 * 
5. Path of Evolution
 * Autonomous Monitoring: Integrate a camera and AI to monitor the print and detect failures.
 * Predictive Maintenance: Use sensor data to predict component failure before it occurs.
 * Remote Control: Develop a web interface for remote monitoring and control.
