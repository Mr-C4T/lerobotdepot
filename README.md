![](media/lerobotdepot_v2.png)

LeRobotDepot is a community-driven repository listing open-source hardware, components, and 3D-printable projects compatible with the LeRobot library. It helps users easily discover, build, and contribute to affordable, accessible robotics solutions powered by state-of-the-art AI.


# 6 DOF arms:

## [TheRobotStudio/SO-ARM100](https://github.com/TheRobotStudio/SO-ARM100)

The 5v version is the first recommandation to start with LeRobot.

![](https://raw.githubusercontent.com/TheRobotStudio/SO-ARM100/refs/heads/main/media/Leader_And_Follower.jpg)

### BOM:
| | US | EU | RMB |
|-|----|----|-----|
| Follower and Leader arms | $232 | 244€ | ￥1343.16 | 
| One Arm| $123 | 128€ | ￥682.23 |

### Motor Types:
- STS3215 7.4V or,
- STS3215 12V<sup>[1](#myfootnote1)</sup>.

The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can buy the 12V version.

### Kits
You can find kits for the SO100 arms here:
- Seeed studio [Bazaar](https://www.seeedstudio.com/SO-ARM100-3D-printed-Enclosure-p-6409.html) or [Taobao](https://item.taobao.com/item.htm?id=878010637397&skuId=5915703371829&spm=a213gs.v2success.0.0.4cbf4831mkqWLn).

- [WOWROBO](https://shop.wowrobo.com/products/so-arm100-diy-kit-assembled-version) (They include **assembled** versions!)

Additionally you can find SO100 follower arm kit (without leader arm) on [Phospho](https://robots.phospho.ai). It can be especially useful if you own a VR headset.

## [jess-moss/koch-v1-1](https://github.com/jess-moss/koch-v1-1)
If you want to familiarise with more industry standard Dynamixel servo motors. This could a a good project to start with. Compared to the SO-ARM100, you will have less torkes and a more limited range of movement from his base.

![](https://raw.githubusercontent.com/jess-moss/koch-v1-1/refs/heads/main/pictures/Follower_And_Leader_Arm.jpg)

### BOM:
| | US | EU | UK | RMB | JPY |
|-|----|----|-----|----|-----|
| Follower and Leader arms | 477$ | 673€ | 507£ | ¥3947 | ¥22439
| leader Arm| $278 | 368€ | £285 | ¥2251 | ¥15446
| Follower Arm | $199 | 305€ | £222 | ¥1696 | ¥6993

### Motor Types:

- Dynamixel XL430
- Dynamixel XL330-M288-T
- Dynamixel XL330-M077-T

### Kits

- Robotic arm inspired by Kocchv1-1: https://shop.wowrobo.com/products/wowrobo-twinarm-robotic-arm-set-inspired-by-koch-v1-1
- Gripper with Camera kit for koch-v1-1: https://shop.wowrobo.com/products/gripper-camera-kit-for-koch-v1-1
- Haptic sensors for koch-v1-1 gripper: https://shop.wowrobo.com/products/enhanced-anyskin-premium-crafted-editionwowskin

## [jess-moss/moss-robot-arms](https://github.com/jess-moss/moss-robot-arms)
The moss-robot-arms is similar to the SO-ARM100 but use only the gripper as 3D printed part. It is recommanded to build or purchase the SO100 arm instead. While the Moss v1 robot is still supported, it will be deprecated. Additionally, 3D-printed parts for the SO-ARM100 are now available for purchase if you don't have a printer.

![](https://raw.githubusercontent.com/jess-moss/moss-robot-arms/refs/heads/main/pictures/Render.png)

### BOM:
| | US | EU | RMB |
|-|----|----|-----|
| Follower and Leader arms | $288 | 274€ | ￥1631.46 | 
| One Arm| $159 | 153€ | ￥868.13 |

### Motor Types:
- STS3215 7.4V or,
- STS3215 12V<sup>[1](#myfootnote1)</sup>.

# 7 DOF arms:

### [ajinkyagorad/SO-ARM107](https://github.com/ajinkyagorad/Lerobot-SO100-Arm/tree/777a90975373a8f5e9e56d468a24ab3dc5916ea4/hardware)

SP-ARM100 leader and follower arms with extra joint using 7 STS3215 servos. 

![](media/so-arm-107-dof.jpg)

# Mobile robot arms
## [SIGRobotics-UIUC/LeKiwi](https://github.com/SIGRobotics-UIUC/LeKiwi)

<img src="https://raw.githubusercontent.com/SIGRobotics-UIUC/LeKiwi/refs/heads/main/media/lekiwi_cad_v1.png" width=400/> <img src="https://raw.githubusercontent.com/SIGRobotics-UIUC/LeKiwi/refs/heads/main/media/lekiwi_real.jpg" width=400/> 

## [timqian/bambot](https://github.com/timqian/bambot)

<img alt="Bambot, open source, low-cost humanoid \($300\)" src="https://github.com/user-attachments/assets/4f8a76e4-33a7-4e55-b779-dc22edda8c1b" width="400" style="height:auto;" >    


# Grippers
## [pollen-robotics/PincOpen](https://github.com/pollen-robotics/PincOpen)
![](https://raw.githubusercontent.com/pollen-robotics/PincOpen/refs/heads/main/assets/images/pincopen_onshape.png)
## [Chojins/LeRobot-S0-100-Models](https://github.com/Chojins/LeRobot-S0-100-Models)
![/media/so-100_chojins_gripper.png](/media/so-100_chojins_gripper.png)

# gripper accessories
- **Self-Fusing Silicone Rubber** to increase friction on gripper: https://www.3m.com/3M/en_US/p/d/b00011950/
![media/self_fusing_silicone_rubber.png](media/self_fusing_silicone_rubber.png)

- **Tactil sensor**: https://shop.wowrobo.com/products/enhanced-anyskin-premium-crafted-editionwowskin


# Task kits

## [cgreer/robot-task-kit](https://github.com/cgreer/robot-task-kit)

- "T" for push T task.
- A "toaster" w/ 2 pieces of "toast".
- A paper towel base&rod + paper towel roll (humanity must master this! We can do it!)
- Cube
- Ring

![](https://private-user-images.githubusercontent.com/735814/393558723-e0b855b5-bdc8-4799-8afc-ec64faba91f2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDI0NTYxMTUsIm5iZiI6MTc0MjQ1NTgxNSwicGF0aCI6Ii83MzU4MTQvMzkzNTU4NzIzLWUwYjg1NWI1LWJkYzgtNDc5OS04YWZjLWVjNjRmYWJhOTFmMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjUwMzIwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI1MDMyMFQwNzMwMTVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jZTYyYWRlY2M5YjNhODA4Y2NlNGVkOWUwZGQxYjYwNzVhYTUzZTk2MDllM2M2ODQ2NzU3NzIwYzRmZTk2ZTA2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.7yZFgY0g8ikCTwPWcEtYCJSWpsIeLx1CnNUoh3kpifo)

## [Huggingface rectangular prism](https://github.com/jess-moss/koch-v1-1/tree/main/hardware/extras/STL)

![](media/huggingface_rectangular_prism.jpeg)
 

# Track Axis
## [avenhaus/SO-ARM100-Track-Axis](https://github.com/avenhaus/SO-ARM100-Track-Axis)

![](https://raw.githubusercontent.com/avenhaus/SO-ARM100-Track-Axis/refs/heads/main/Images/Arm.jpg)

# Full body robot (currently only torso and arms)

## [TheRobotStudio/HOPEJr](https://github.com/TheRobotStudio/HOPEJr)

<img src="media/hopejr_arm.png" height=300/> <img src="media/hopejr_torso_and_arms.png" height=300/> 


# Finger Teleoperation

## [max-titov/finger-tracker](https://github.com/max-titov/finger-tracker)

Hardware that attaches to the back of your hand and fingertips that tracks 16 degrees of freedom.

<p float="left">
  <img src="https://raw.githubusercontent.com/max-titov/finger-tracker/refs/heads/main/media/overview.jpeg" width="300" />
  <img src="https://raw.githubusercontent.com/max-titov/finger-tracker/refs/heads/main/media/hand_stand.jpeg" width="300" /> 
</p>

# Mobile robot

## [apirrone/Open_Duck_Mini](apirrone/Open_Duck_Mini)

Miniature version of the BDX Droid by Disney.

<table>
  <tr>
    <td> <img src="https://github.com/user-attachments/assets/1cec3e46-de46-4abb-9c9e-20f936f15121" alt="1" width="300px" ></td>
    <td> <img src="https://github.com/user-attachments/assets/d2588204-32db-47c1-9ac5-2d2f71dbb98a" alt="2" width="300px" ></td>
    <td> <img src="https://github.com/user-attachments/assets/94fbd245-655e-4465-a727-950a89ff02c2" alt="3" width="300px" ></td>
   </tr> 
</table>

# Cameras and mounts
- https://github.com/TheRobotStudio/SO-ARM100/blob/main/Optional/Camera_Holder_Alternate_MF
https://github.com/TheRobotStudio/SO-ARM100/tree/main/Optional/Camera_Holder


# Footnotes

<a name="myfootnote1">1</a>: The 7.4V has a stall torque of 16.5kg.cm at 6V (and likely slightly less for a 5V power supply). The 12V version has a stall torque of 30kg.cm. While we found the 7.4V to be sufficient, if you would like more powerful motors you can buy the 12V version

