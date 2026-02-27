# Activity 4: Collaborative Robot Fundamentals

**Course:** CS 304 - Robotic Agents  
**Due Date:** Friday, February 27, 11:59PM

---

## Overview

In this activity, you will experiment with a **collaborative robot (cobot) simulator** to explore fundamental concepts in robotic manipulation: Cartesian movements, axis orientation, payload management, and pick-and-place operations. You will document your experiments and analyze how the robot responds to different commands.

The simulator models a **FANUC CRX 10iA** collaborative robot with:
- 6 degrees of freedom (6 joints)
- Max payload: 10 kg
- Max reach: 1249 mm
- SCHUNK EGP 64 gripper

---

## Getting Started

### Opening the Simulator

**Access the simulator online:** https://learnroboticagents.com/cobot-simulator

### Controls

**Mouse Controls:**
- **Left-click + drag:** Rotate camera around robot
- **Right-click + drag:** Pan camera
- **Scroll wheel:** Zoom in/out

**Keyboard Shortcuts:**
- `R` - Reset camera view
- `G` - Toggle grid
- `L` - Toggle axis labels

**Robot Controls (in sidebar):**
- **Cartesian Mode:** Move robot end effector to specific X, Y, Z positions
- **Payload Mode:** Adjust payload weight and operate gripper
- **Orientation Mode:** Rotate end effector using Yaw, Pitch, Roll
- **Info Panel:** View joint angles, toggle labels, access robot specs

---

## Robot Specifications

*Based on FANUC CRX-10iA specifications (total motion range)*

| Joint | Name | Range of Motion |
|-------|------|-----------------|
| J1 | Base | 380° |
| J2 | Shoulder | 360° |
| J3 | Elbow | 570° |
| J4 | Wrist 1 | 380° |
| J5 | Wrist 2 | 360° |
| J6 | Wrist 3/Gripper | 450° |

### Key Concepts

**Cartesian Movement:**
- X-axis: Left/Right (from robot's perspective)
- Y-axis: Forward/Backward
- Z-axis: Up/Down (vertical)

**Orientation (Euler Angles):**
- **Yaw:** Rotation around Z-axis (left/right tilt)
- **Pitch:** Rotation around X-axis (forward/backward tilt)
- **Roll:** Rotation around Y-axis (twist)

**Payload:**
- Maximum payload: 10 kg
- Exceeding 80% capacity causes robot strain (visible vibration)
- Gripper max capacity: 1.25 kg (SCHUNK EGP 64)

---

## Experiments Overview

Complete the following experiments and document your findings in `experiments.md`:

1. **Cartesian Movement:** Explore X, Y, Z coordinates and understand the robot's reach
2. **Joint Angles:** Record how joint angles change with different positions
3. **Orientation:** Experiment with Yaw, Pitch, Roll
4. **Payload Testing:** Test payload limits and observe strain effects
5. **Pick and Place:** Complete pick-and-place tasks with the gripper

---

## Submission

- Complete all experiments in `experiments.md`
- Document observations, measurements, and conclusions
- Push your completed work to your GitHub repository
