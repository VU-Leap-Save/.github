Welcome to the Vanderbilt Leap-Save github!

## System Requirements For the Deployed System
* Operating System: Ubuntu 22.04
* As of 11/13/2024, the amount of RAM and VRAM used by the robot controllers, user study data collection, and Unity game are as follows.  
| | RAM | VRAM |
|-|-----|------|
| Unity Game | 5.5 GB | 1.3 GB
| Robot Controller + User Study Data Collection | 2.2 GB | 0.69 GB |
| **TOTAL** | **7.7 GB** | **1.94 GB** |

## Primary Repos for Deployed System
* [`Unity_visualizer`](https://github.com/VU-Leap-Save/Unity_visualizer): Main unity simulation of the liver deformation models, textures, and tool interactions
* [`robot_controller`](https://github.com/VU-Leap-Save/robot_controller): Main ROS 2 high-level controllers for the haptic devices
* [`teensy_low_level_control`](https://github.com/VU-Leap-Save/teensy_low_level_control): Joint level control code for the robot that runs on a Teensy 4.1 microcontroller
* [`user_study_data_collection`](https://github.com/VU-Leap-Save/user_study_data_collection): ROS 2 tools for user study data collection
 
## Rules for contributors
1. Your main/master branch should contain tested and working code. Keep experimental/in-development code in branches.
2. Use pull requests and request code reviews from team members before merging code into main/master.
3. Every repository should have a README or wiki that contains: 
   1. List of dependencies and target platforms
   2. Installation instructions
   3. A quickstart guide (i.e. instructions for running the code)
4. Every repository should have a `.gitignore` file.
5. Recommended: Create a style guide and code standards document for your repo/team. For example, see the [`robot_controller` wiki](https://github.com/VU-Leap-Save/robot_controller/wiki/Conventions-and-Style-Guide) 
 
