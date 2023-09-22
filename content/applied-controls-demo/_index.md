---
title: "Applied Controls Demo"
date: 2023-09-01T16:52:52-04:00
---

# Instructions

1. Turn on the power switch.

![system_PWR_switch](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_system_pwr_switch.png?classes=center)

The HMI will turn on automatically. PLC will be waiting for the robots to boot up.

2. Turn on all UR10e robots with their power buttons. Make sure no e-stop buttons are pressed on any of the pendants. Wait unitl all robots boot completely. It should show "PROFIsafe Emergency Stop" warning on the pendants.

1. Start all the robots. Make sure all the robots are at their home positions. If not, you won't be able to start the demo. To Home the robot, turn the Robot Auto/Manual mode to OFF. Go to the robot, it should be on Manual mode. Go to Move tab, home the robot.

1. Press the `Safety Reset` button. This should remove the PROFISAFE warning on the screen.

1. Go back to ALL robots and press the circle on the bottom left corner (It should say Power Off). Initialize ALL robots (The 3rd circle out of 5 on the screen should be green, the last two will still be gray)

1. Press the `Safety Reset` button. At this point you should hear the air return to the machine and the `Safety Reset` button should disappear.

1. Preset the blue Reset button (this will reset the conveyors so that they can move). Or go to `Conveyor`, then click `Realign` to align the conveyor.

1. Hit the `Start` button on ALL the robots. The robot should start up (This will make their brakes release and you should hear cracking noises from the robots).

1. Go to the PLC HMI main page. It should look like this:

![HMI_control_main](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_control_main.png?classes=center)

10. Click `Safety`, it will take you to the Robot Auto/Manual page like this:

![HMI_safety_robot_auto_manual](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_safety_robot_auto_manual_mode.png?classes=center)

11. Switch all the robots Auto/Manual mode to ON. This will put all the robots in Automatic mode.

1. Go to each pendant and switch the robot mode to Remote Control (top right). This will allow the PLC to control the robot remotely.

1. Make sure all the Stations are enabled. `Load` the Manual Sample Load with `Demo` as follows:

![HMI_stations](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_stations.png?classes=center)

![HMI_demo_dance](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_demo_dance.png?classes=center)

14. Now if you click `Start` on the HMI, the system should start running the demo. You can stop the demo by pressing the `Stop` button on the HMI.

Note: When you press the Applied Controls logo, the configuration page will show up.


