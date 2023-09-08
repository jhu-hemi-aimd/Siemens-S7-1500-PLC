---
title: "Applied Controls Demo"
date: 2023-09-01T16:52:52-04:00
---

# Instructions

1. Turn on the power switch.

![system_PWR_switch](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_system_pwr_switch.png?classes=center)

The HMI will turn on automatically. PLC will be waiting for the robots to boot up.

1. Turn on all UR10e robots with their power buttons. Make sure no e-stop buttons are pressed on any of the pendants. Wait unitl all robots boot completely. It should show "PROFIsafe Emergency Stop" warning on the pendants.

1. Start all the robots. Make sure all the robots are at their home positions. If not, you won't be able to start the demo. To Home the robot, turn the Robot Auto/Manual mode to OFF. Go to the robot, it should be on Manual mode. Go to Move tab, home the robot.

1. Press the `Safety Reset` button. This should remove the PROFISAFE warning on the screen.

1. Go back to ALL robots and press the circle on the bottom left corner (It should say Power Off). Initialize ALL robots (The 3rd circle out of 5 on the screen should be green, the last two will still be gray)

1. Press the `Safety Reset` button. At this point you should hear the air return to the machine and the `Safety Reset` button should disappear.

1. Preset the blue Reset button (this will reset the conveyors so that they can move). Or go to `Conveyor`, then click `Realign` to align the conveyor.

1. Hit the `Start` button on ALL the robots.  This will make their brakes release and you should hear cracking noises from the robots.

1. Press the play button on ALL robots.

![HMI_control_main](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_control_main.png?classes=center)

![HMI_safety_robot_auto_manual](https://jhu-hemi-aimd.github.io/Siemens-S7-1500-PLC/applied-controls-demo/images/figure_safety_robot_auto_manual_mode.png?classes=center)

Note: When you press the Applied Controls logo, the configuration page will show up.


