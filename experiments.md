# Experimental Documentation

## Experiment 1: Cartesian Movement

### Procedure
1. Go to **Cartesian Mode**
2. Move X from -10 to +10, then Y, then Z
3. Record the end effector position from the Info panel

### Data

| X | Y | Z | End Effector Pos |
|---|---|---|------------------|
| 0 | 3 | 0 | (from panel) |
| 5 | 3 | 0 | |
| 0 | 5 | 0 | |
| 0 | 3 | 5 | |
| -5 | 3 | 0 | |

### Questions
- What is the maximum reach in each direction?
- Which joint (J1, J2, J3) controls each axis?

**Answers:**
- Max X: ___ | Max Y: ___ | Max Z: ___
- X: ___ | Y: ___ | Z: ___

---

## Experiment 2: Joint Angles

### Procedure
1. Enable **Joint Labels** in Info panel
2. Move to 3 different positions
3. Record joint angles from Info panel

### Data

| Position | X, Y, Z | J1 | J2 | J3 | J4 | J5 | J6 |
|----------|---------|----|----|----|----|----|-----|
| Home | 0,3,0 | | | | | | |
| Pos 1 | | | | | | | |
| Pos 2 | | | | | | | |

### Question
Which joint rotates the base? Which controls height?

**Answer:** ____

---

## Experiment 3: Orientation (Yaw, Pitch, Roll)

### Procedure
1. Go to **Orientation Mode**
2. Set Yaw to -90°, 0°, 90° - describe motion
3. Set Pitch to -45°, 45° - describe motion  
4. Set Roll to -90°, 90° - describe motion

### Observations

| Angle | Value | Description of Motion |
|-------|-------|----------------------|
| Yaw | -90° | |
| Yaw | 90° | |
| Pitch | -45° | |
| Pitch | 45° | |
| Roll | -90° | |
| Roll | 90° | |

### Question
Which angle tilts gripper forward? Which twists it?

**Answers:** Pitch = ___ | Roll = ___

---

## Experiment 4: Payload & Gripper

### Part A: Gripper

### Procedure
1. Go to **Payload Mode**
2. Move above a colored box
3. Close gripper (slider = 1) to pick up
4. Move to green drop zone
5. Open gripper (slider = 0) to release

### Data

| Box | Pick Position | Drop Zone | Success? |
|-----|---------------|-----------|----------|
| Red | X:__ Y:__ Z:__ | | Yes/No |
| Blue | | | |
| Yellow | | | |
| Green | | | |

### Part B: Payload

### Procedure
Set payload slider and note the status:

| Payload | % of Max | Color | Strain |
|---------|----------|-------|--------|
| 0 kg | 0% | Green | None |
| 5 kg | | | |
| 8 kg | | | |
| 10 kg | | | |

### Question
At what payload % does strain become "High"?

**Answer:** ____%

---

## Experiment 5: Pick and Place Challenge

Complete: Pick up all 4 boxes and move to drop zone.

Record your solution:

| Box | Pick X,Y,Z | Drop X,Y,Z |
|-----|------------|------------|
| Red | | |
| Blue | | |
| Yellow | | |
| Green | | |
