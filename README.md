# Electric-Toothbrush-Converter

## Project Overview:

This project explores the design of a compact motor driven mechanism that converts a standard manual toothbrush into a high frequency electric toothbrush.

The goal is to design a mechanically efficient system that either: 1) produces strong, controlled vibration at the brush head or 2) a oscillating mechanism that moves that causes the brush to move with high frequency. All while remaining compact, handheld, battery powered, and modular.

## Problem Statement

Commercial electric toothbrushes are often expensive and proprietary. This project investigates whether a removable insert style handle can convert a standard manual toothbrush into a high frequency vibrating toothbrush using a compact DC motor system.

The challenge is efficiently transmitting rotation from the motor to the brush head without excessive damping or energy loss.

## Design Requirements

- Target frequency: [200 to 300 Hz]
- Target rotational speed: [12000 to 18000 RPM]
- Power source:[ To be determined]
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
- Estimated crank radius: [enter value]
- Estimated brush tip movement: [enter value]
- Material: [PLA, PETG, ABS, nylon, etc.]
- Mounting method: [press fit, screws, adhesive, etc.]

---

## Electronics

### Planned Components

- DC motor: [model or type]
- Battery: [type and voltage]
- Switch: [on off or push button]
- Motor control: [direct power or PWM]

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
