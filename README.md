# Roban Systems: Helping Hand for Disabled People

Welcome to the Roban Systems project, a groundbreaking IoT solution designed to provide assistance and support to disabled individuals. This README file contains information about the project, its features, setup instructions, and more.

# Project Overview

Over the last few decades, many researchers have focused on connecting everyday objects and weaving a web of interconnected devices. These can be physical devices, automobiles, embedded systems or everyday home appliances. The connectivity of these devices is enabled by the underlying technology known as the Internet of Things (IoT) [1]. These devices can communicate with one another and seamlessly collect and transfer data in between to adapt and reciprocate to dynamic situations. The IoT is gaining tremendous traction from the IT industry as well as individual enthusiasts alike. This is because microcontroller technologies have evolved that enable these complex infrastructures and are more accessible to average developers. The use of single board computers also refers to as System on Chip (SoC) in IoT-based systems, enables rapid interconnection of environmental sensors and decent computational capabilities along with vision sensors that make it easy to develop fairly in large applications. Advancements in machine learning algorithms for mobile and low-power devices also pave the way for intelligent devices in IoT systems. A typical home automation system connects heterogeneous devices, collects data, and decides based on the observed data from these sensors. The means of communication between these devices is typically Wi-Fi or Bluetooth and in some cases a cellular network (3G/4G/5G) [2]. We were focusing on how IoT can drastically improve the lives of disabled people by addressing limited access in many ways. We also spoke about how smart homes and home automation systems are rising in popularity, allowing people to control various aspects of their homes from a single place without getting up. However, for disabled people, this technology holds much more significance. It is not adding additional value but solving some of their biggest hurdles like being unable to access specific items or devices. Smart homes single-handedly allow disabled people to live more independently with an easy-access lifestyle. With the sophistication of IoT technology, it has become a possibility for disabled people to rely lesser on their caregivers

# MODULES AND REQUIREMENTS


### Bed and Ventilation Module
The bed and ventilation module is used to adjust the bed position and adjust the ventilation by sliding the curtains. Disabled people can adjust the bed positions by themselves through voice commands, so they can acquire their comfortable positions. By controlling the ventilation system by voice command they can adjust the natural lighting and ventilation.
 
### Basic Needs Module
The basic need module consists of an Artificial ventilation system like fans, or exhaust fans, a lighting system like AC and DC lights, warm lights and a pest control system. Disabled people can adjust the bed positions by themselves through voice commands so they can full fill their needs using the IoT
 
### Patient Monitor Module
This module consists of several sensors that are connected over IoT, and by that sensor, we can monitor the patient’s health and make health plans and it can also alert the authorities when there are any emergencies happen. We can implement patient monitoring like temp, oxygen, pulse, etc. and monitor the environment of the patient.

### Medical Aid Module
This module can automate or remote the essential medical supply like medicines, oxygen, water etc. This is done by the multiple relays and solenoid valve pumps etc. 
 
### security and Entertainment Module
Disabled people are seen in a closed environment so there is a chance of mental depression. So we connect entertainment like TV, social media, and streaming platforms in this module Disabled people can use them through voice commands. And security is also essential for them so we connected a security camera we can use this camera to monitor the patient’s external and internal environment.

# Requirements
### system configuration 
The system must be full fill the configuration of 4GB RAM and a minimum operating system of Windows 7 or more.

### C++ language
As Arduino. began developing new MCU boards based on non-AVR processors like the ARM/SAM MCU used in the Arduino Due, they needed to modify the Arduino IDE so it would be relatively easy to change the IDE to support alternate toolchains to allow Arduino C/C++ to be compiled for these new processors. They did this with the introduction of the Board Manager and the SAM Core. A "core" is the collection of software components required by the Board Manager and the Arduino IDE to compile an Arduino C/C++ source file for the target MCU's machine language.
3.6.3 Alexa
Alexa Voice Service (AVS) Integration is a new feature of AWS IoT Core that enables device makers to make any connected device an Alexa Built-in device. AVS for AWS IoT reduces both the cost and complexity of producing Alexa Built-in devices by offloading compute and memory-intensive tasks from physical devices to the cloud. With the reduction in the engineering bill of materials (BOM) cost, device makers can now cost-effectively build new categories of differentiated voice-enabled products such as light switches, thermostats, small appliances and more. This allows end-consumers to talk directly to Alexa in new parts of their home, office, or hotel rooms for a truly ambient experience.
3.6.4 Blynk platform
Everything you need to build and manage connected hardware: device provisioning, sensor data visualization, remote control with mobile and web applications, Over-The-Air firmware updates, secure cloud, data analytics, user and access management, alerts, automation and much more.Blynk platform powers low-batch manufacturers of smart home products, complex HVAC systems, agricultural equipment, and everyone in between. These companies build branded apps with no code and get the full back-end IoT infrastructure through one web app.

# The Arduino Integrated Development Environment
The Arduino Integrated Development Environment - or Arduino Software (IDE) - contains a text editor for writing code, a message area, a text console, a toolbar with buttons for common functions and a series of menus. It connects to the Arduino hardware to upload programs and communicate with them.


### The Proteus Design Suite
The Proteus Design Suite is a proprietary software tool suite used primarily for electronic design automation. The software is used mainly by electronic design engineers and technicians to create schematics and electronic prints for manufacturing printed circuit boards.
### Node MCU
NodeMCU is a low-cost open-source IoT platform. It initially included firmware which runs on the ESP8266 Wi-Fi SoC from Espressif Systems, and hardware which was based on the ESP-12 module. Later, support for the ESP32 32-bit MCU was added.
### Sensors
A sensor is a device that detects and responds to some type of input from the physical environment. The input can be light, heat, motion, moisture, pressure or any number of other environmental phenomena.
### Relay module
A power relay module is an electrical switch that is operated by an electromagnet. The electromagnet is activated by a separate low-power signal from a microcontroller. When activated, the electromagnet pulls to either open or close an electrical circuit.
### SMPS 
The full form of SMPS is Switched Mode Power Supply also known as Switching Mode Power Supply. SMPS is an electronic power supply system that makes use of a switching regulator to transfer electrical power effectively
### Pump/valve
Reciprocating pumps are a type of positive displacement pump, consisting of a: Fluid-End (consisting of two chambers, suction and discharge, separated by spring-loaded valves) and a Suction Inlet (where fluid flows from piping through a valve into the first chamber, aka suction chamber). Valves regulate and control flow and pressure in pumping systems. They also play an important role in site safety. Understanding the types of valves and how they work can help end users select the right valves for their application’s use.


## Getting Started

1. Clone the repository to your local machine.
2. Set up the control unit (Raspberry Pi or Arduino) and connect sensors/actuators as per the hardware diagram provided.
3. Install necessary dependencies and libraries on the control unit.
4. Configure IoT communication protocols for data exchange between devices.
5. Develop or install the mobile app for user interaction and monitoring.
6. Run the system and test its functionality with various scenarios.

## Usage

- Power on the control unit and ensure all components are connected and functioning properly.
- Launch the mobile app and establish a connection with the control unit.
- Use voice commands or app controls to operate the robotic arm and other features.
- Monitor sensor data and receive alerts for any anomalies or events.

## Future Improvements

- Integration with AI/ML algorithms for advanced automation and decision-making.
- Enhancements in user interface and experience for the mobile app.
- Expansion of sensor capabilities for detecting additional parameters.
- Cloud integration for data analytics, storage, and remote access.
- Collaboration with healthcare professionals for specialized functionalities.

## Contribution Guidelines

- Fork the repository and make your changes or improvements.
- Create a new branch for your feature or enhancement.
- Submit a pull request detailing the changes and their impact.

## License

This project is licensed under the [MIT License](LICENSE), allowing for both personal and commercial use.

## Contact

For any inquiries or feedback, please contact:
- Project Lead: [Your Name](mailto:your.email@example.com)
- Technical Support: [Support Team](mailto:support@example.com)
