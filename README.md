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

<h2 align="center">
    <p>(WORK IN PROGRESS)</p>
</h2>

We’re excited to hold our first Hackathon, happening on the weekend of October 26-27, both online and in-person in Toulouse, France! This document will be your central resource for everything related to the Hackathon. For any other questions please reach out to the community on the [LeRobot Discord server](https://discord.gg/8uHu9JqVnm).

## Venue for in-person participants

_**TODO**. Add address of the venue plus any instructions on how to find the entrance, how to get in, and how to find our specific room._

## Agenda

The event will run across two days: Saturday 26 and Sunday 27 October. On each day we will get started at 08:45 CST and we'll need to finish up and vacate the premises by 19:00 (but you may have homework to do!).

We will run a main stream of activities and alternate streams that may run in parallel with activities from other streams. You may pick and choose according to your preferences and available resources. Unless otherwise stated, the activities are available to both in-person and online participants (the latter via live-streaming and Discord chats).

What? | When? | Link to [LeRobot Discord](https://discord.gg/8uHu9JqVnm) channel | Prerequisites | Resource
|  - | - | - | - | - |
***Robot Assembly**: We will work through assembling one of the [LeRobot kits](#robot-assembly) with you. | Saturday AM | [#assembly](https://discord.com/channels/1216765309076115607/1296485594096209964) | We will lend out 25 Moss v1 to in-person participants. Otherwise, please bring your own robot parts for one of the [LeRobot kits](#robot-assembly). | [See below](#robot-assembly) for more information on the available kits, including links to assembly instructions.
**Configuration + Teleoperation**: We will use the LeRobot library to configure, calibrate, and teleoperate the follower arm by manually controlling the leader arm. | Saturday PM | [#general](https://discord.com/channels/1216765309076115607/1296485441108840510) | A fully assembled and functional robot from one of the [LeRobot kits](#robot-assembly) | [Tutorial section on teleoperation](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md#2-configure-motors-calibrate-arms-teleoperate-your-koch-v11) • [LeRobot's teleoperation script](https://github.com/huggingface/lerobot/blob/main/lerobot/scripts/control_robot.py)
**Dataset Recording**: You will learn how to record a dataset. This dataset will be used by those going on to train an imitation learning policy. | Saturday PM | [#general](https://discord.com/channels/1216765309076115607/1296485441108840510) | Complete the "Configuration + Teleoperation" ↖️ activity with us, or make sure you have it working in advance. | [Tutorial section on dataset recording](https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md#3-record-your-dataset-and-visualize-it) • [LeRobot's dataset recording script](https://github.com/huggingface/lerobot/blob/main/lerobot/scripts/control_robot.py)
**Imitation Learning - Training**: We will show you how to launch training for an ACT policy. You will aim to have a policy trained by next morning. You may be interested in trying another one of the available LeRobot policies, or bringing your own in a fork! | Saturday PM | [#imitation-learning](https://discord.com/channels/1216765309076115607/1296485698467008573) | You have recorded a LeRobot dataset. | [ACT paper](https://arxiv.org/abs/2304.13705) • [LeRobot ACT code](https://github.com/huggingface/lerobot/tree/main/lerobot/common/policies/act) • [LeRobot paper discussion on ACT](https://www.youtube.com/watch?v=ft73x0LfGpM) • [LeRobot training script](https://github.com/huggingface/lerobot/blob/main/lerobot/scripts/train.py)
**Imitation Learning - Evaluation**: We will run our trained policy on the real robot and try to report on a performance metric. | Sunday AM | [#imitation-learning](https://discord.com/channels/1216765309076115607/1296485698467008573) | You have a trained policy and access to a setup very similar to the one you had for dataset collection. | [LeRobot's real world policy rollout script](https://github.com/huggingface/lerobot/blob/main/lerobot/scripts/control_robot.py)
*(Alternate stream)* **RL in Sim**: Train a reinforcement learning based model in a simulation environment. | Sunday AM / PM | [#reinforcement-learning](https://discord.com/channels/1216765309076115607/1296485640640270337) | TODO | TODO 
*(Alternate stream)* **Real world RL**: Train a reinforcement learning based model in the real world. | Sunday AM / PM| [#reinforcement-learning](https://discord.com/channels/1216765309076115607/1296485640640270337) | TODO | TODO 


### *Robot Assembly

We will be assembling our robots together. Choose from any of these 5 DoF + gripper robots:

_**TODO**: Better tag lines to explain to someone why they would choose one over the other._

- Koch v1.1: The original [Koch robot](https://github.com/AlexanderKoch-Koch/low_cost_robot) with minor adjustments by LeRobot. Powered by Dynamixel motors (€650 + 3D printing costs)
  - End-to-end tutorial: https://github.com/huggingface/lerobot/blob/main/examples/7_get_started_with_real_robot.md
  - Assembly tutorials: https://www.youtube.com/watch?v=8nQIg9BwwTk
- Moss v1: Brand-new LeRobot design. Minimal 3D printing required. Powered by Feetech motors (€270 + 3D printing costs).
- SO-100: Brand-new LeRobot design. Powered by Feetech motors (€230 + 3D printing costs).




