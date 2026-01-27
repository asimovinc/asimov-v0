# Asimov v0, an open-source bipedal robotic legs

Asimov is a complete bipedal leg for humanoid robots, built with off-the-shelf components and compatible with low-volume manufacturing processes.

![Asimov Legs](media/asimov-legs-repo-v0.png)

<video src="https://github.com/asimovinc/asimov-v0/raw/main/media/asimov-legs.gif" width="600" controls></video>

<p align="center">
  <a href="https://asimov.inc">Website</a>
  - <a href="https://discord.gg/HzDfGN7kUw">Community</a>
  - <a href="https://asimov.inc/early">Support</a>
</p>

## Specifications
- [12 DOF actuation, 6 DOF per leg](https://github.com/asimovinc/asimov-v0/tree/main/mechanical)
- Articulated toe
- RSU (Revolute Spherical Universal) [ankle mechanism](https://github.com/asimovinc/asimov-v0/tree/main/mechanical)
- [MJF 3D printing compatible](https://github.com/asimovinc/asimov-v0/tree/main/sim-model)

## Left Leg

| Name         | Joint  | Min | Max | Peak Torque |
|--------------|------- |-----|-----|------------|
| L_Hip_Pitch  | Hip flexion/extension | -120° | +57° | 120 Nm |
| L_Hip_Roll   | Hip abduction/adduction | -45° | +45° | 90 Nm |
| L_Hip_Yaw    | Hip rotation | -45° | +45° | 60 Nm |
| L_Knee_Pitch | Knee flexion/extension | 0° | +86° | 75 Nm |
| L_Ankle_A    | Ankle dorsi/plantarflexion | -70° | +70° | 36 Nm |
| L_Ankle_B    | Ankle inversion/eversion | -70° | +70° | 36 Nm |

## Right Leg

| Name         | Joint | Min | Max | Peak Torque |
|--------------|-------|-----|-----|------------|
| R_Hip_Pitch  | Hip flexion/extension | -57° | +120° | 120 Nm |
| R_Hip_Roll   | Hip abduction/adduction | -45° | +45° | 90 Nm |
| R_Hip_Yaw    | Hip rotation | -45° | +45° | 60 Nm |
| R_Knee_Pitch | Knee flexion/extension | -86° | 0° | 75 Nm |
| R_Ankle_A    | Ankle dorsi/plantarflexion | -70° | +70° | 36 Nm |
| R_Ankle_B    | Ankle inversion/eversion | -70° | +70° | 36 Nm |

## Motors

- Motors from [Encos](encos.cn)

| Joint | Model |
|-------|-------|
| Pitch      | EC-A6416-P2-25   |
| Roll       | EC-A5013-H17-100 |
| Yaw        | EC-A3814-H14-107 |
| Knee_Pitch | EC-A4315-P2-36   |
| Ankle_A    | EC-A4310-P2-36   |
| Ankle_B    | EC-A4310-P2-36   |

## Support the project
Asimov is Menlo Research's open-source humanoid robot:
- If you want to support development: [asimov.inc/early](https://asimov.inc/early)
- For partnerships: hello@menlo.ai
