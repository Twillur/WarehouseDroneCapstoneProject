# Drone System for Intralogistical Payload Transport

BSc capstone project, American University of Armenia (2024–2025), supervised by Krist Samuel.

An autonomous drone for moving payloads inside a warehouse. It localises itself with ArUco markers read by an onboard camera, holds position with PID control, and carries loads in a custom 3D-printed gripper.

**Hardware:** Pixhawk 4 flight controller · Raspberry Pi companion computer · camera · 3D-printed gripper

## Contents

| File | What it is |
|---|---|
| `ArUco Detection` | Marker detection and pose estimation script |
| `Actuators Gripping Mechanism` | Gripper actuation script |
| `Conops.pdf` | Full concept-of-operations report |

The report is also published by AUA: [cse.aua.am](https://cse.aua.am/wp-content/uploads/2025/07/William_Kojumian_Conops.pdf). Presented at the 2025 AUA CSE Student Research Showcase.
