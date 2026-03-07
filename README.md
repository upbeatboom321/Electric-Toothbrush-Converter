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
- Power source: [3.7 V LiPo or 2x AAA]
- Compact handheld form factor
- Replaceable manual toothbrush compatibility
- Safe and comfortable vibration amplitude

## Concept Selection

Two vibration approaches were considered.

Eccentric rotating mass motor
A DC motor with an off center mass that generates vibration through centrifugal force.

Crank driven oscillation
A DC motor driving a crank mechanism that converts rotational motion into controlled angular oscillation.

Selected approach: The approach chosen for this project will involve a crank driven oscillation. 

Rationale: An eccentric rotating mass system generates vibration by creating imbalance in the motor shaft. For the vibration to be effective at the bristles, the motor and rotating mass must be positioned close to the brush head to reduce energy loss through damping. However, placing a vibrating mass near the brush head can reduce user comfort and cause unwanted vibration of surrounding components that contact the mouth.

In contrast, a crank driven oscillation mechanism converts rotational motion into controlled angular oscillation of the brush head. This allows motion to be directed specifically into the bristles rather than dissipated throughout the entire handle. Although the handle still experiences some vibration, the brush head motion is predictable, repeatable, and mechanically defined by the crank radius. This improves efficiency of energy transfer and allows precise control over frequency and amplitude.

This approach also simplifies analysis and design calculations because stroke length and frequency are directly determined by motor speed and crank geometry.

## How the Mechanism Works

The motor rotates a disk with a pin placed off center. As the disk spins, the pin drives a linkage that causes the toothbrush shaft to oscillate left and right. This converts continuous motor rotation into repeated angular motion of the brush head.

### Key Terms

**Crank radius**  
The distance from the center of the motor shaft to the center of the offset pin.

**Stroke**  
The total motion from one extreme position to the other.

**Frequency**  
The number of oscillations per second, measured in hertz.

**Angular oscillation**  
A repeated left and right turning motion around a pivot or axis.

---

## Basic Math

### Frequency

Frequency is determined by motor speed:

**f = RPM / 60**

Where:  
- `f` = frequency in hertz  
- `RPM` = motor speed in revolutions per minute

### Stroke

For a simple crank system:

**stroke = 2 × crank radius**

### Angular Motion at the Brush

If the brush rotates left and right, the tip displacement depends on the length of the brush head and the angle of rotation.

For small angles:

**tip displacement ≈ length × angle**

### Velocity

For oscillating motion:

**vmax = A × 2πf**

Where:  
- `A` = amplitude  
- `f` = frequency

### Acceleration

**amax = A × (2πf)²**

These equations help estimate how strong the motion will be and whether the design is realistic for the motor and printed parts.

---

## Mechanical Design

The mechanical system consists of:

- A DC motor
- A rotating crank disk
- An offset crank pin
- A linkage or rack system
- A toothbrush clip
- A housing to support and align the mechanism

The mechanism is intended to be 3D printed for rapid prototyping and testing.

### Current Design Notes

- Motion type: Angular oscillation
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

## Testing Plan

The performance of the prototype will be tested using the following methods.

### 1. Frequency Measurement

Measure motor speed and convert to oscillation frequency using:

**f = RPM / 60**

Tools:
- Tachometer
- Slow motion video
- Phone based measurement apps

### 2. Tip Displacement

Measure how far the toothbrush tip moves left to right.

Tools:
- Ruler in slow motion video
- Frame by frame analysis

### 3. User Feel and Comfort

Record observations about:
- Strength of motion
- Comfort in hand
- Comfort near mouth
- Noise level
- Stability

### 4. Mechanical Reliability

Observe:
- Wear on linkage parts
- Backlash
- Cracking in printed parts
- Motor heating
- Alignment issues

