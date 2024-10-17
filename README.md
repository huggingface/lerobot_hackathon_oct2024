<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="media/lerobot-logo-thumbnail.png">
    <source media="(prefers-color-scheme: light)" srcset="media/lerobot-logo-thumbnail.png">
    <img alt="LeRobot, Hugging Face Robotics Library" src="media/lerobot-logo-thumbnail.png" style="max-width: 100%;">
  </picture>
  <br/>
  <br/>
</p>

<h1 align="center">
    <p>LeRobot Hackathon • October 2024</p>
</h1>

We’re excited to hold our first hackathon, happening on the weekend of October 26-27, both online and in-person in Toulouse, France!

## Venue for in-person participants

_**TODO**_

## Agenda

The event will run across two days: Saturday 26 and Sunday 27 October. On each day we will get started at 08:30 CST and we'll need to finish up and vacate the premises by 17:00.

We will run several streams of activities in parallel (streams are color coded in the table below). You may pick and choose according to your preferences and available resources. Unless otherwise stated, the activities are available to both in-person and online participants (the latter via live-streaming and Discord chats).

Stream # | What? | When? | Prerequisites | Resources
| - |  - | - | - | - |
A | **Robot Assembly**: We will work through assembling one of the [LeRobot kits](#robot-assembly) with you. | Saturday AM | We will lend out 25 Moss v1 to in-person participants. Otherwise, please bring your own robot parts for one of the [LeRobot kits](#robot-assembly). | [See below](#robot-assembly) for more information on the available kits, including links to assembly instructions.
A | **Teleoperation**: We will use the LeRobot library to teleoperate the follower arm by manually controlling the leader arm. | Saturday PM | A fully assembled and functional robot from one of the [LeRobot kits](#robot-assembly) | Full tutorial: [LeRobot: Getting Started with Real-World Robots](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md)
A | **Dataset Recording**: You will learn how to record a dataset. This dataset will be used by those going on to train an imitation learning policy. | Saturday PM | Complete the Teleoperation ↖️ activity with us, or make sure you have it working in advance. | Full tutorial: [LeRobot: Getting Started with Real-World Robots](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md)
A | **Imitation Learning - Training**: We will show you how to launch training for a policy. You will aim to have a policy trained by next morning. | Saturday PM | You have recorded a LeRobot dataset. | Full tutorial: [LeRobot: Getting Started with Real-World Robots](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md)
A | **Imitation Learning - Evaluation**: We will run our trained policy on the real robot and try to report on a performance metric. | Sunday AM | You have trained a trained policy and access to a setup very similar to the one you had for dataset collection. | Full tutorial: [LeRobot: Getting Started with Real-World Robots](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md)
B | **RL in Sim** | Sunday AM | TODO | TODO 
C | **Real world RL** | Saturday AM | TODO | TODO 


### Robot Assembly

We will be assembling our robots together. Choose from any of these 5 DoF + gripper robots:

_**TODO**: Better tag lines to explain to someone why they would choose one over the other._

- Koch v1.1: The original [Koch robot](https://github.com/AlexanderKoch-Koch/low_cost_robot) with minor adjustments by LeRobot. Powered by Dynamixel motors (€650 + 3D printing costs)
  - End-to-end tutorial: https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md
  - Assembly tutorials: https://www.youtube.com/watch?v=8nQIg9BwwTk
- Moss v1: Brand-new LeRobot design. Minimal 3D printing required. Powered by Feetech motors (€270 + 3D printing costs).
- SO-100: Brand-new LeRobot design. Powered by Feetech motors (€230 + 3D printing costs).


## Communication channels

