## Introduction

This manual describes the use and function of the Shadow Modular Grasper

### Abbreviations

Abbreviation | Meaning
--- | ---
API | Application Programming Interface
DoF | Degrees of Freedom
EC | EtherCAT
EEPROM | Electrically Erasable Programmable Read Only Memory. 
GUI | Graphical User Interface.
LED | Light Emitting Diode. (A small coloured light)
MCU | Micro Controller Unit. (A small, usually embedded, CPU)
PC | Personal Computer.
PWM | Pulse Width Modulation. (The digital method used to emulate an analogue signal.)
ROS | Robot Operating System.

### Modular Grasper Technical Spec

The Shadow Agile Grasper is an advanced solution for grasping and handling a wide range of objects.

* 9 Degrees of Freedom (DoF) 
* 3 Fingers  
* 3 Joints per Finger          <img align="right" src="../img/tech_spec_1.png" alt="Technical Specification 1">
  * Base rotation,	-45° to +45°
  * Proximal,	-80° to +60°
  * Distal,		-60° to +80°
* Maxon DC Motors
* Backdrivable Gearbox 
* Non-slip surfaces for Grasp Stability 
* 2.7 kg weight 
* 2 kg Payload (using power grasp) 
* 20 N intermittent force per fingertip, 10 N continuous
* 260 mm maximum span
* 1 kHz Position Control Loop , with 0.02° position sensing resolution  ![Technical Specification 2](../img/tech_spec_2.png)
* 1.39 mNm resolution direct Torque sensing at each joint
* 10 kHz onboard Torque Control Loop 
* 0.5 second full range open/close speed
* ROS Compliant (Robot Operating System www.ros.org)
* EtherCAT® interface
* 24V DC, 150W power envelope
* Safety Systems:
  * Over temperature protection
  * Inherent compliance via Series Elastic Actuator
  * Patented chain configuration protects internal drive train
* Mounting plate to attach to standard robot arms
* Grasping Library with open APIs (Python/ROS/REST)
* Bespoke fingertips can easily be redesigned to accommodate different environments
* OptoForce tactile sensing in fingertips (option)

![Technical Specification 3](../img/tech_spec_3.png)