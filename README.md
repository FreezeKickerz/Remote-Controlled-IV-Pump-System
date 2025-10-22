Enhancing Patient Safety through Remote-Controlled Robotics for Intravenous Administration

Overview

This project addresses the challenge of healthcare-associated infections caused by frequent nurse-patient contact during IV dosage adjustments. 
By creating a remote-controlled IV pump system, this project enhances patient safety, reduces infection risk, and improves hospital efficiency.

The team designed and prototyped a system that allows healthcare providers to control an Alaris BD IV pump remotely through a Raspberry Pi interface. 
This enables dosage changes without entering patient rooms, minimizing exposure and saving valuable medical staff time.

Objectives
-Enable remote control of the BD Alaris PC Unit and pump modules.
-Maintain full pump functionality while operated remotely.
-Reduce infection risks associated with in-person dosage changes.
-Improve operational efficiency in clinical settings.

Approach
-Research and Reverse Engineering: Investigated communication pathways between the BD Alaris PC Unit and its keypad using logic analyzers.
-Hardware Integration: Connected each button to Raspberry Pi GPIO pins to emulate the keypad’s input signals.
-Software Development: Developed Raspberry Pi software to interpret and send control signals to the PCU, providing both wired and wireless control options.
-Prototype Development: Built a digital prototype displaying system interactions and verified its physical implementation using LEDs and wiring to show data transmission.
-Testing and Validation: Measured response time, accuracy, and reliability of remote commands under various conditions.

Key Features
-Real-Time Control: Adjust IV pump flow rates remotely with minimal latency.
-User Interface: Raspberry Pi touchscreen interface for easy operation by healthcare staff.
-Reliable Communication: Secure wired and wireless connections for hospital settings.
-Error Handling: Safety protocols for disconnections or system errors.

Outcomes
-Reduced healthcare-associated infection risks by minimizing nurse-patient contact.
-Decreased time wasted donning and removing PPE.
-Increased efficiency and workflow for nurses and hospital staff.
-Extended the life of physical keypads by using a virtual interface.

System Components
-BD Alaris PC Unit
-BD Alaris Pump Modules
-Raspberry Pi 4 with Touchscreen
-Custom Ribbon Cable and Connectors
-Logic Analyzer and Soldering Tools

Testing and Evaluation
-Accuracy Testing: Verified fluid delivery precision across various conditions.
-Response Time: Ensured near real-time adjustments to flow rates.
-Stress Testing: Validated system reliability under prolonged use.

Future Work
-Expand functionality through optocouplers for signal mediation.
-Integrate VNC viewer for fully wireless control.
-Add real-time monitoring via camera or screen mirroring.
-Enhance security with encrypted wireless communication.

Demonstration

Watch the project demo on YouTube: https://youtu.be/76HGZfMxT2o
