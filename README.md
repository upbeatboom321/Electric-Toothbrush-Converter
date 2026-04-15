# Electric-Toothbrush-Converter

## Project Overview:

This project explores the design of a compact motor driven mechanism that converts a standard manual toothbrush into a high frequency electric toothbrush.

The goal is to design a mechanically efficient system that either: 1) produces strong, controlled vibration at the brush head or 2) a oscillating mechanism that moves that causes the brush to move with high frequency. All while remaining compact, handheld, battery powered, and modular.

## Problem Statement

Commercial electric toothbrushes are often expensive and proprietary. This project investigates whether a removable insert style handle can convert a standard manual toothbrush into a high frequency vibrating toothbrush using a compact DC motor system.

The challenge is efficiently transmitting vibration from the motor to the brush head without excessive damping or energy loss.

## Design Requirements

- Target vibration speed: 8000-20000RPM
- Power source: 3xAAA batteries in series
- Compact handheld form factor
- Replaceable manual toothbrush compatibility
- Safe and comfortable vibration amplitude

## Concept Selection

Two vibration approaches were considered.

Eccentric rotating mass motor/ vibration motor
A DC motor with an off center mass that generates vibration through centrifugal force.

Crank driven oscillation
A DC motor driving a crank mechanism that converts rotational motion into controlled angular oscillation.

Selected approach: The approach chosen for this project will involve a vibration motor. 

Rationale: A vibration motor was chosen over a crank driven oscillation mechanism because it is mechanically simpler, more compact, and easier to prototype. The vibration motor can generate high frequency motion with fewer moving parts, which reduces design complexity, manufacturing difficulty, and the risk of mechanical failure. This makes it more suitable for an early stage prototype where the main goal is to achieve noticeable brush vibration quickly and reliably.

## How the Mechanism Works

The vibration motor is mounted at the end of a link bar while the Toothbrush is clipped at the other end which allows to transfer vibration across.

## Mechanical Design

The mechanical system consists of:

- A Vibration motor
- A link bar
- A toothbrush clip
- A housing to support and align the mechanism

The mechanism is intended to be 3D printed for rapid prototyping and testing.

### Current Design Notes

- Motion type: Vibration motor
- Estimated motor vibration with brush: 8000-20000RPM
- Material: PLA plastic
- Mounting method: Press fit

---

## Electronics

### Planned Components

- Battery: 3xAAA batteries in series (4.5v)
- Switch: On off switch
- Motor control: direct power

### Electrical Goals

- Maintain stable motor speed under load
- Keep power system compact
- Avoid overheating
- Allow repeatable testing

---

## CAD and Prototyping

This project will use CAD and 3D printing to develop the mechanism and housing.

### Design Focus

- Lightweight moving parts
- Low backlash in the linkage
- Rigid motor mounting
- Compact toothbrush attachment system
- Easy disassembly for testing and iteration

---
# Current
---

## Current Specifications and Version

**Configuration:**  
- Motor: DC Coreless Vibration Motor 7x25mm, 1-6V Rated, 8000-20000RPM
- Power source: 3xAAA batteries in series
- Material: PLA plastic
- Brush attachment: Semi-cicrle like clip that goes around the lower midpoint of the brush

Current: Version 4
---

## Electrical Diagram

The electric wiring for this project is quite simple represented by the following diagram.

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/edd6b2010d671f4ffcdd68ea69ed5afbbf082775/Electrical%20Diagram/ETC%20(Electrical%20Diagram).png)

Inside the acutal Main body of the ETC, where the battery positive and negative terminal make contact with the plastic, small pieced of metal were placed there connected to wires. This allows for the battery to be replacable while ensuring proper connection.

## Future corrections

The ETC is effective and there is substancial vibration at the brush head, however the vibration mechanism is making too much noise. The link bar making contact with the surrounding enviroment is causing the vibration to transfer to the whole body and not just the brush head. The vibration motor is further dampened by the switch located in side the main body due to it being to big and making direct contact with the motor. The case is okay but becomes uncomfortable to hold when brushing the top teeth. The brush also turns while brushing causing there to be less overall vibration.

Too make is product more effective: the material surrounding the link bar will need to make less contact while not degrading structual integrety, the switch will need to be smaller to give more room for the vibration motor, the casing will need to be more confortable to hold using ergonomic designs, the clip for the brush needs to be universal while firmly holding onto the any brush.

## Final Photos

![image alt]([https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/edd6b2010d671f4ffcdd68ea69ed5afbbf082775/Electrical%20Diagram/ETC%20(Electrical%20Diagram).png](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Final%20with%20everything).jpeg))

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Inside%20case%20with%20electrical%201).jpeg)

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Inside%20case%20with%20electrical%202).jpeg)

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Main%20body%20with%20Back%20lid).jpeg)

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Main%20body).jpeg)

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Simple%20vibration%20mechanism).jpeg)

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Vibration%20mechanism%20focus%20back).jpeg)

![image alt](https://github.com/upbeatboom321/Electric-Toothbrush-Converter/blob/bc1a8993c03731aabfaebd6da449c6d216bca477/ETC%20Media/ETC%20(Vibration%20mechanism%20focus%20front).jpeg)





