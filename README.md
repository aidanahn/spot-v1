# spot-v1

## Table of Contents
1. [Description](#description)
2. [Milo](#milo-wip)
3. [Fastener List](#fastener-list)
4. [Printing List](#printing-list)
5. [Printing Orientations](#printing-orientations)
6. [License](#license)

## Description
A fast and reliable 4WD 3D-printable RC car design

Assembly: [Onshape Link](https://cad.onshape.com/documents/7f341d22941a2e14df29ce4a/w/e412618fee4bd938372718a9/e/cd4b9ad8284ddeb69a4dfc13?renderMode=0&uiState=69179513c6ca6b3e90eb09f7)

## Milo (WIP)
Track & Field pacer designed to run consistent lap times and help with pacing during training (Uses the same car design from Spot V1).

Check the project out here: (https://github.com/aidanahn/pacer_v3_control)

## Fastener List
| Quantity | Size | Length | Head | Type |
| -------- | ---- | ------ | ---- | ---- |
| 20 | M3 | 16mm | Socket Head | Screw |
| 18 | M3 | 12mm | Socket Head | Screw |
| 12 | M3 | 12mm | Button Head | Screw |
| 2 | M3 | 20mm | Socket Head | Screw |
| 11 | M3 | 25mm | Socket Head | Screw |
| 8 | M3 | 35mm | Socket Head | Screw |
| 6 | M3 | | | Washer |
| 16 | M3 | 4mm | Socket Head | Screw |
| 12 | M3 | | | Nut |
| 4 | M3 | 8mm | Button Head | Screw |
| 4 | M3 | 16mm | Button Head | Screw |
| 4 | M4 | 20mm | Socket Head | Screw |
| 4 | M4 | | | Nylon Locknut |

## Printing List
| Quantity | Part Name | Description |
| -------- | --------- | ----------- |
| 1 | [Front Chassis](cad/Front_Chassis.step) | Main structural front frame holding servo, steering linkages, and front suspension system|
| 1 | [Rear Chassis](cad/Rear_Chassis.step) | Main structural rear frame holding motor, belt drive, and rear suspension system|
| 1 | [Right Reinforcement Beam](cad/Right_Reinforcement_Beam.step) | Connects front chassis to rear chassis |
| 1 | [Left Reinforcement Beam](cad/Left_Reinforcement_Beam.step) | Connects front chassis to rear chassis |
| 2 | [Lower Differential Case](cad/Lower_Differential_Case.step) | Protective housing for differential |
| 2 | [Upper Differential Case](cad/Upper_Differential_Case.step) | Protective housing for differential |
| 2 | [Upper Control Arm Bracket](cad/Upper_Control_Arm_Bracket.step) | Mounting bracket for the upper control arms to attach to the chassis |
| 4 | [Upper Control Arm](cad/Upper_Control_Arm.step) | Upper suspension arm that connects uprights to the chassis |
| 1 | [Rear Left Lower Control Arm](cad/Rear_Left_Lower_Control_Arm.step) | Lower suspension arm that connects uprights to the chassis |
| 1 | [Rear Right Lower Control Arm](cad/Rear_Right_Lower_Control_Arm.step) | Lower suspension arm that connects uprights to the chassis |
| 1 | [Front Left Lower Control Arm](cad/Front_Left_Lower_Control_Arm.step) | Lower suspension arm that connects uprights to the chassis |
| 1 | [Front Right Lower Control Arm](cad/Front_Right_Lower_Control_Arm.step) | Lower suspension arm that connects uprights to the chassis |
| 1 | [Electronics Bed](cad/Electronics_Bed.step) | Strengthens connection between front and rear chassis and acts as mounting plate for electronics (ESC, reciever, LiPo, etc) |
| 4 | [Differential Drive Cup Adapter](cad/Differential_Drive_Cup_Adapter.step) | Adapter between differential output and drive cup |
| 4 | [Differential Drive Cup](cad/Differential_Drive_Cup.step) | Cup that connects differential output to drive the wheels |
| 2 | [Front Upright](cad/Front_Upright.step) | Front wheel carrier that allows the steering knuckles to pivot and houses the wheel drive cup |
| 2 | [Rear Upright](cad/Rear_Upright.step) | Rear wheel carrier housing the wheel drive cup |
| 2 | [Pinion Carrier](cad/Pinion_Carrier.step) | Holds differential pinion gears in place |
| 1 | [Left Steering Knuckle](cad/Left_Steering_Knuckle.step) | Allows wheels to pivot for steering input |
| 1 | [Right Steering Knuckle](cad/Right_Steering_Knuckle.step) | Allows wheels to pivot for steering input |
| 1 | [Servo Mount](cad/Servo_Mount.step) | Holds servo securely in place |
| 1 | [Servo Steering Linkage](cad/Servo_Steering_Linkage.step) | Transmits servo power to the steering bar |
| 1 | [Steering Bar](cad/Steering_Bar.step) | Main steering bar linking left and right wheels |
| 1 | [Steering Linkage](cad/Steering_Linkage.step) | Follows same motion as the steering linkage to keep the steering bar in place |
| 4 | [Wheel Drive Cup](cad/Wheel_Drive_Cup.step) | Connects wheel hubs to the differential output cups |
| 4 | [Wheel Hub](cad/Wheel_Hub.step) | Mounting point for wheels |
| 1 | [Steering Mount](cad/Steering_Mount.step) | Allows the steering linkage to pivot around its axis |
| 4 | [Dogbone](cad/Dogbone.step) | Transfers power directly from the differential drive cup to the wheel drive cup |

## Printing Orientations
### Front Chassis
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Front Chassis](print-orientation-previews/front-chassis.png)

### Rear Chassis
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Rear Chassis](print-orientation-previews/rear-chassis.png)

### Right Reinforcement Beam
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Right Reinforcement Beam](print-orientation-previews/right-reinforcement-beam.png)

### Left Reinforcement Beam
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Left Reinforcement Beam](print-orientation-previews/left-reinforcement-beam.png)

### Lower Differential Case
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Lower Differential Case](print-orientation-previews/lower-differential-case.png)

### Upper Differential Case
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Upper Differential Case](print-orientation-previews/upper-differential-case.png)

### Upper Control Arm Bracket
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Upper Control Arm Bracket](print-orientation-previews/upper-control-arm-bracket.png)

### Upper Control Arm
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Upper Control Arm](print-orientation-previews/upper-control-arm.png)

### Lower Control Arm
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Lower Control Arm](print-orientation-previews/lower-control-arm.png)

### Electronics Bed
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Electronics Bed](print-orientation-previews/electronics-bed.png)

### Differential Drive Cup Adapter
**Recommended Print Settings:**
- **Layer Height:** 0.1mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Automatic)
- **Material:** PETG

![Differential Drive Cup Adapter](print-orientation-previews/differential-drive-cup-adapter.png)

### Differential Drive Cup
**Recommended Print Settings:**
- **Layer Height:** 0.1mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Automatic)
- **Material:** PETG

![Differential Drive Cup](print-orientation-previews/differential-drive-cup.png)

### Front Upright
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Front Upright](print-orientation-previews/front-upright.png)

### Rear Upright
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Rear Upright](print-orientation-previews/rear-upright.png)

### Pinion Carrier
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Pinion Carrier](print-orientation-previews/pinion-carrier.png)

### Steering Knuckle
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Steering Knuckle](print-orientation-previews/steering-knuckle.png)

### Servo Mount
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Manual)
- **Material:** PETG

![Servo Mount](print-orientation-previews/servo-mount.png)

### Servo Steering Linkage
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Servo Steering Linkage](print-orientation-previews/servo-steering-linkage.png)

### Steering Bar
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Steering Bar](print-orientation-previews/steering-bar.png)

### Steering Linkage
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Steering Linkage](print-orientation-previews/steering-linkage.png)

### Wheel Drive Cup
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Automatic)
- **Material:** PETG

![Wheel Drive Cup](print-orientation-previews/wheel-drive-cup.png)

### Wheel Hub
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Wheel Hub](print-orientation-previews/wheel-hub.png)

### Steering Mount
**Recommended Print Settings:**
- **Layer Height:** 0.2mm
- **Infill:** 30% (Gyroid)
- **Supports:** No
- **Material:** PETG

![Steering Mount](print-orientation-previews/steering-mount.png)

### Dogbone
**Recommended Print Settings:**
- **Layer Height:** 0.1mm
- **Infill:** 30% (Gyroid)
- **Supports:** Yes (Automatic)
- **Material:** PETG

![Steering Mount](print-orientation-previews/dogbone.png)

## License
This work is licensed under a [MIT License](LICENSE).
