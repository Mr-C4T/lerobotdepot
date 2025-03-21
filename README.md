![](media/lerobotdepot_v2.png)

LeRobotDepot is a community-driven repository listing open-source hardware, components, and 3D-printable projects compatible with the LeRobot library. It helps users easily discover, build, and contribute to affordable, accessible robotics solutions powered by state-of-the-art AI.

## Table of Contents

- [5 DOF arms](#5-dof-arms)
  - [TheRobotStudio/SO-ARM100](#therobotstudioso-arm100)
  - [jess-moss/koch-v1-1](#jess-mosskoch-v1-1)
  - [jess-moss/moss-robot-arms](#jess-mossmoss-robot-arms)
- [6 DOF arms](#6-dof-arms)
  - [ajinkyagorad/SO-ARM107](#ajinkyagoradso-arm107)
  - [SAM arm](#sam-arm)
- [Mobile robot arms](#mobile-robot-arms)
  - [SIGRobotics-UIUC/LeKiwi](#sigrobotics-uiuc-lekiwi)
  - [timqian/bambot](#timqianbambot)
- [Grippers](#grippers)
  - [pollen-robotics/PincOpen](#pollen-roboticspincopen)
  - [Chojins/LeRobot-S0-100-Models](#chojinslerobot-s0-100-models)
  - [Gripper accessories](#gripper-accessories)
- [Task kits](#task-kits)
  - [cgreer/robot-task-kit](#cgreerrobot-task-kit)
  - [Hugging Face rectangular prism](#hugging-face-rectangular-prism)
- [Track Axis](#track-axis)
  - [avenhaus/SO-ARM100-Track-Axis](#avenhausso-arm100-track-axis)
- [Full body robot (currently only torso and arms)](#full-body-robot-currently-only-torso-and-arms)
  - [TheRobotStudio/HOPEJr](#therobotstudiohopejr)
- [operation](#finger-teleoperation)
  - [max-titov/finger-tracker](#max-titovfinger-tracker)
- [Two legs robot](#two-legs-robot)
  - [apirrone/Open_Duck_Mini](#apirroneopen-duck-mini)
- [Cameras and mounts](#cameras-and-mounts)
  - [Cameras](#cameras)
  - [SO-ARM100 compatible](#so-arm100-compatible)
  - [Koch-V1-1 compatible](#koch-v1-1-compatible)
- [Footnotes](#footnotes)


# 5 DOF arms:

## [TheRobotStudio/SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100)

The 5V version is the first recommendation to start with LeRobot.

<img src="https://raw.githubusercontent.com/TheRobotStudio/SO-ARM100/refs/heads/main/media/Leader_And_Follower.jpg" width="400">

### Price:
|                           | US    | EU    | RMB       |
|---------------------------|-------|-------|-----------|
| Follower and Leader arms  | $232  | 244€  | ￥1343.16 |
| One Arm                   | $123  | 128€  | ￥682.23  |

### Motor Types:
- STS3215 7.4V or,
- STS3215 12V<sup>[1](#myfootnote1)</sup>.

The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can buy the 12V version.

### Kits
You can find kits for the SO100 arms here:
- Seeed Studio [Bazaar](https://www.seeedstudio.com/SO-ARM100-3D-printed-Enclosure-p-6409.html) or [Taobao](https://item.taobao.com/item.htm?id=878010637397&skuId=5915703371829&spm=a213gs.v2success.0.0.4cbf4831mkqWLn).
- [WOWROBO](https://shop.wowrobo.com/products/so-arm100-diy-kit-assembled-version) (They include **assembled** versions!)

Additionally, you can find the SO100 follower arm kit (without the leader arm) on [Phospho](https://robots.phospho.ai). It can be especially useful if you own a VR headset.

### Accessories

- [SO100 arm electronics mounting cover](https://grabcad.com/library/so100-arm-electronics-mounting-cover-and-stereo-cam-holder-1)

## [jess-moss/koch-v1-1](https://github.com/jess-moss/koch-v1-1)
If you want to familiarise yourself with more industry standard Dynamixel servo motors, this project could be a good starting point. Compared to the SO-ARM100, you will have less torque and a more limited range of movement from its base.

<img src="https://raw.githubusercontent.com/jess-moss/koch-v1-1/refs/heads/main/pictures/Follower_And_Leader_Arm.jpg" width="400">

### Price:
|                         | US    | EU    | UK    | RMB  | JPY   |
|-------------------------|-------|-------|-------|------|-------|
| Follower and Leader arms| $477  | 673€  | 507£  | ¥3947 | ¥22439 |
| Leader Arm              | $278  | 368€  | £285  | ¥2251 | ¥15446 |
| Follower Arm            | $199  | 305€  | £222  | ¥1696 | ¥6993  |

### Motor Types:
- Dynamixel XL430
- Dynamixel XL330-M288-T
- Dynamixel XL330-M077-T

### Kits
- Robotic arm inspired by Kochv-1-1: [WOWROBO Twinarm](https://shop.wowrobo.com/products/wowrobo-twinarm-robotic-arm-set-inspired-by-koch-v1-1)
- Gripper with Camera kit for Koch-v1-1: [WOWROBO Gripper-Camera Kit](https://shop.wowrobo.com/products/gripper-camera-kit-for-koch-v1-1)
- Haptic sensors for Koch-v1-1 gripper: [Enhanced AnySkin](https://shop.wowrobo.com/products/enhanced-anyskin-premium-crafted-editionwowskin)

## [jess-moss/moss-robot-arms](https://github.com/jess-moss/moss-robot-arms)
The moss-robot-arms project is similar to the SO-ARM100 but uses only the gripper as a 3D printed part. It is recommended to build or purchase the SO100 arm instead. While the Moss v1 robot is still supported, it will be deprecated. Additionally, 3D-printed parts for the SO-ARM100 are now available for purchase if you don't have a printer.

<img src="https://raw.githubusercontent.com/jess-moss/moss-robot-arms/refs/heads/main/pictures/Render.png" width="400">

### Price:
|                           | US    | EU    | RMB       |
|---------------------------|-------|-------|-----------|
| Follower and Leader arms  | $288  | 274€  | ￥1631.46 |
| One Arm                   | $159  | 153€  | ￥868.13  |

### Motor Types:
- STS3215 7.4V or,
- STS3215 12V<sup>[1](#myfootnote1)</sup>.

# 6 DOF arms:

### [ajinkyagorad/SO-ARM107](https://github.com/ajinkyagorad/Lerobot-SO100-Arm/tree/777a90975373a8f5e9e56d468a24ab3dc5916ea4/hardware)

SO-ARM100 leader and follower arms with an extra joint using 7 STS3215 servos.

<img src="media/so-arm-107-dof.jpg" width="400">

### SAM arm

Developed by the community around the [SimpleAutomation repository](https://github.com/SimpleAutomationOrg/SimpleAutomation), this refined version of the SO-ARM100 offers enhanced movement precision and a gripper specifically optimized for handling small objects.

<img src="media/SAM_arm.png" width="400">

- [Discord Channel](https://t.co/pPVt7dVbnJ)
- [Discorn message on Bill Of Materials](https://discord.com/channels/1306427593586901092/1308906584239243274/1324588976312684595)
- [Discorn message on Beta v1.1 STEP files](https://discord.com/channels/1306427593586901092/1308906584239243274/1336551154368253972)

### Price:
|                           | US    |
|---------------------------|-------|
| Follower and Leader arms  | ± $450|

### Motor Types:
- STS3215 12V

# Mobile robot arms

## [SIGRobotics-UIUC/LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)
Mobile version of the SO-ARM100.

<p>
  <img src="https://raw.githubusercontent.com/SIGRobotics-UIUC/LeKiwi/refs/heads/main/media/lekiwi_cad_v1.png" width="300">
  <img src="https://raw.githubusercontent.com/SIGRobotics-UIUC/LeKiwi/refs/heads/main/media/lekiwi_real.jpg" width="300">
</p>
### Price:

| Price              | US      | EU      |
|--------------------|---------|---------|
| 12V                | $488.21 | €542.56 |
| 5V                 | $524.95 | €525.9  |
| Base only (5V)     | $251.95 | €306.9  |
| Base only (12V)    | $257.43 | €305    |
| Base only wired    | $174    | €233.3  |

### Motor Types:
- STS3215 7.4V or,
- STS3215 12V<sup>[1](#myfootnote1)</sup>.

## [timqian/bambot](https://github.com/timqian/bambot)

Mobile version of the SO-ARM100 with two arms.

<img alt="Bambot, open source, low-cost humanoid ($300)" src="https://github.com/user-attachments/assets/4f8a76e4-33a7-4e55-b779-dc22edda8c1b" width="400">

### Price:
|                           | US    | EU    | RMB       |
|---------------------------|-------|-------|-----------|
| Total                     | ~$300 | ~€300 | ~￥2000  |

### Motor Types:
- STS3215 12V.

# Grippers

## [pollen-robotics/PincOpen](https://github.com/pollen-robotics/PincOpen)

Parallel-finger gripper compatible with SO-ARM100.

<img src="https://raw.githubusercontent.com/pollen-robotics/PincOpen/refs/heads/main/assets/images/pincopen_onshape.png" width="400">

### Price:
~25€

### Motor Types:
- STS3215 7.4V or,
- STS3215 12V<sup>[1](#myfootnote1)</sup>.

## [Chojins/LeRobot-S0-100-Models](https://github.com/Chojins/LeRobot-S0-100-Models)

Precise gripper compatible with SO-ARM100.

<img src="media/so-100_chojins_gripper.png" width="400">

## Gripper accessories

- **Self-Fusing Silicone Rubber** to increase friction on gripper: [3M Product Page](https://www.3m.com/3M/en_US/p/d/b00011950/)
  
  <img src="media/self_fusing_silicone_rubber.png" width="400">

- **Tactil sensor**: [WOWROBO Tactil Sensor](https://shop.wowrobo.com/products/enhanced-anyskin-premium-crafted-editionwowskin)

# Task kits

## [cgreer/robot-task-kit](https://github.com/cgreer/robot-task-kit)

- "T" for push T task.
- A "toaster" with 2 pieces of "toast".
- A paper towel base & rod + paper towel roll.
- Cube.
- Ring.

<img src="media/task_kit.png" width="400">

## [Hugging Face rectangular prism](https://github.com/jess-moss/koch-v1-1/tree/main/hardware/extras/STL)

<img src="media/huggingface_rectangular_prism.jpeg" width="400">

# Track Axis

## [avenhaus/SO-ARM100-Track-Axis](https://github.com/avenhaus/SO-ARM100-Track-Axis)

<img src="https://raw.githubusercontent.com/avenhaus/SO-ARM100-Track-Axis/refs/heads/main/Images/Arm.jpg" width="400">

# Full body robot (currently only torso and arms)

## [TheRobotStudio/HOPEJr](https://github.com/TheRobotStudio/HOPEJr)

<p>
  <img src="media/hopejr_arm.png" width="300">
  <img src="media/hopejr_torso_and_arms.png" width="300">
</p>

# Finger Teleoperation

## [max-titov/finger-tracker](https://github.com/max-titov/finger-tracker)

Hardware that attaches to the back of your hand and fingertips that tracks 16 degrees of freedom.

<p>
  <img src="https://raw.githubusercontent.com/max-titov/finger-tracker/refs/heads/main/media/overview.jpeg" width="300">
  <img src="https://raw.githubusercontent.com/max-titov/finger-tracker/refs/heads/main/media/hand_stand.jpeg" width="300">
</p>

# Two legs robot

## [apirrone/Open_Duck_Mini](https://github.com/apirrone/Open_Duck_Mini)

Miniature version of the BDX Droid by Disney.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/1cec3e46-de46-4abb-9c9e-20f936f15121" alt="1" width="250"></td>
    <td><img src="https://github.com/user-attachments/assets/d2588204-32db-47c1-9ac5-2d2f71dbb98a" alt="2" width="250"></td>
    <td><img src="https://github.com/user-attachments/assets/94fbd245-655e-4465-a727-950a89ff02c2" alt="3" width="250"></td>
  </tr>
</table>

# Cameras and mounts

## Cameras

| Name                     | Price Range | Link | Resolution | FPS  | Wide Angle                                   | Microphone |
|--------------------------|-------------|------|------------|------|----------------------------------------------|------------|
| Innomaker 1080P USB2.0     | ± $18, 16€  | [Innomaker Link](https://www.inno-maker.com/product-category/products/uvc-cameras/low-cost/) | 1920×1080  | 30   | Fov(D) = 130° <br> Fov(H) = 103°              | No         |
| Innomaker 720p USB2.0      | ± $10, 14€  | [Innomaker Link](https://www.inno-maker.com/product-category/products/uvc-cameras/low-cost/) | 1280×720   | 30   | FOV (D) = 120° <br> FOV (H) = 102°             | No         |
| Innomaker OV9281 USB 2.0   | ± $36, 42€  | [Innomaker Link](https://www.inno-maker.com/product/u20cam-9281m/) | 1280×800   | 120  | FOV Up to 148°                               | No         |
| Vinmooog Webcam          | ± $14, 12€  | [Amazon Link](https://www.amazon.nl/-/en/Microphone-Adjustable-Conference-Streaming-Compatible/dp/B0BG1YJWFN/) | 1920×1080  | N/A  | N/A                                          | Yes        |

### Others
- https://www.amazon.co.uk/ELP-Conferencing-Fisheye-0-01Lux-Computer/dp/B08Y1KY5T9?th=1
- https://www.amazon.com/dp/B07CSJN2KH

## SO-ARM100 compatible
- [Mount for innomaker 1080P USB2.0](https://github.com/TheRobotStudio/SO-ARM100/blob/main/Optional/Camera_Holder_Alternate_MF)
- [Mount for Vinmooog Webcam](https://github.com/TheRobotStudio/SO-ARM100/tree/main/Optional/Camera_Holder)
- [Mount for Intel realsense support](https://www.thingiverse.com/thing:6981459)

## Koch-V1-1 compatible
<img src="media/camera_mount_koch.png" width="300">

[Discord Message source](https://discord.com/channels/1216765309076115607/1243077809828790363/1311493401157304350) 

# Footnotes

<a name="myfootnote1">1</a>: The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can buy the 12V version.
