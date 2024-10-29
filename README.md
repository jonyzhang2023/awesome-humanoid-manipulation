# awesome-humanoid-manipulation 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)


A curated list of awesome papers and resources on **humanoid manipuation**, or humanoid robot-object interaction. This repo is inspired by [awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning).

_Note_: We also included papers on the relevant topics: 

1. Bimanual multi-fingered manipulation
2. Dual-arm manipulation with other end effectors ([#1](https://github.com/Tsunami-kun/awesome-humanoid-manipulation/issues/1))
3. humanoid or digital human manipulation in physically based animation.

---

## Contents
- [Humanoid Models](#Models)
  - [Humanoids](#Humanoids)
  - [Dexterous Hands](#DexterousHands)
  - [Dual-Arm Robots](#DualArmRobots)
- [Workshops](#Workshops)
- [Projects](#Projects)
- [Papers](#Papers)
  - [Humanoid Robot Manipulation](#HumanoidRobotManipulation)
  - [Bimanual Dexterous Multi-Fingered Manipulation](#BimanualDexterousMulti-FingeredManipulation)
  - [Dual-Arm Manipulation with Other End Effectors](#DualArmManipulationwithOtherEndEffectors)
  - [Physically Simulated HOI Animations](#PhysicallySimulatedHumanoidAnimations)


<a name="Models" />

## Robot Models

<a name="Humanoids" />

### Humanoids

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| H1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/h1_description), [USD](https://github.com/unitreerobotics/unitree_model/tree/main/H1/usd) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| G1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/g1_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| GR-1 | FFTAI | [URDF](https://github.com/FFTAI/Wiki-GRx-Models/tree/master/GRX/GR1), [MJCF](https://github.com/FFTAI/wiki-mjcf/) | GPL-3.0 | ✔️ | ✔️ | ✔️ |
| Digit | Agility Robotics | [URDF](https://github.com/adubredu/DigitRobot.jl/tree/main/urdf) | ✖️ | ✔️ | ✔️ | ✔️ |

<a name="DexterousHands" />

### Dexterous Hands

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| Ability Hand | PSYONIC, Inc. | [MJCF](https://github.com/psyonicinc/ability-hand-api/tree/master/URDF/mujoco), [URDF](https://github.com/psyonicinc/ability-hand-api/tree/master/URDF) | ✖️ | ✔️ | ✔️ | ✖️ |
| Allegro Hand | Wonik Robotics | [URDF](https://github.com/RobotLocomotion/models/tree/master/allegro_hand_description/urdf), [MJCF](https://github.com/shadow-robot/sr_common/tree/6fcee98982499a645c0812a89b6e70a920f2ed33/sr_description/mujoco_models) | BSD | ✔️ | ✔️ | ✔️ |
| Shadow Hand | Shadow Robot | [URDF](https://github.com/shadow-robot/sr_common/tree/noetic-devel/sr_description/mujoco_models/urdfs), [MJCF](https://github.com/google-deepmind/mujoco_menagerie/tree/main/wonik_allegro) | BSD | ✔️ | ✔️ | ✔️ |

<a name="DualArmRobots" />

### Dual-Arm Robots

| Name | Maker | Formats | License | Visuals | Inertias | Collisions |
|------|-------|---------|---------|---------|----------|------------|
| YuMi | ABB | [URDF](https://github.com/OrebroUniversity/yumi/tree/master/yumi_description) | BSD-2-Clause | ✔️ | ✔️ | ✔️ |
| Dual iiwa 14 | KUKA | [URDF](https://github.com/RobotLocomotion/models/blob/master/iiwa_description/urdf/dual_iiwa14_polytope_collision.urdf), [Xacro](https://github.com/RobotLocomotion/models/blob/master/iiwa_description/urdf/dual_iiwa14_polytope_collision.urdf.xacro) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |



<a name="Workshops" />

## Workshops

CORL 2024 [[Workshop on Whole-body Control and Bimanual Manipulation: Applications in Humanoids and Beyond](https://wcbm-workshop.github.io/)]

<a name="Projects" />

## Projects

Lerobot [[LeRobot: State-of-the-art AI for real-world robotics](https://github.com/huggingface/lerobot)]

<a name="Papers" />

## Papers

YYYY.MM is the date when paper appears on arxiv.org (if available).

<a name="HumanoidRobotManipulation" />

### Humanoid Robot Manipulation

- [2024.10] OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation [**IL**] [[project](https://ut-austin-rpl.github.io/OKAMI/)] [[paper](http://arxiv.org/abs/2410.11792)] 

- [2024.10] Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies [**IL**] [**diffusion**] [[project](https://humanoid-manipulation.github.io/)] [[paper](https://arxiv.org/abs/2410.10803)] [[code(Learning)](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)][[code(Teleop)](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)]

- [2024.08] RP1M: A Large-Scale Motion Dataset for Piano Playing with Bi-Manual Dexterous Robot Hands [**IL**] [[project](https://rp1m.github.io/)] [[paper](https://arxiv.org/abs/2408.11048)] [[code](https://github.com/google-research/robopianist)]

- [2024.07] Open-TeleVision Teleoperation with Immersive Active Visual Feedback [**IL**] [[project](https://robot-tv.github.io/)] [[paper](https://arxiv.org/abs/2407.01512)] [[code](https://github.com/OpenTeleVision/TeleVision)]

- [2024.07] GRUtopia: Dream General Robots in a City at Scale [**benchmark**] [[doc](https://grutopia.github.io/)] [[paper](https://arxiv.org/abs/2407.10943)] [[project&code](https://github.com/OpenRobotLab/GRUtopia)]

- [2024.07] BiGym: A Demo-Driven Mobile Bi-Manual Manipulation Benchmark [**benchmark**] [[project](https://chernyadev.github.io/bigym)] [[paper](https://arxiv.org/abs/2407.07788)] [[code](https://github.com/YanjieZe/Humanoid-Teleoperation)]

- [2024.06] HumanPlus: Humanoid Shadowing and Imitation from Humans [**IL**] [[project](https://humanoid-ai.github.io/)] [[paper](https://arxiv.org/abs/2406.10454)] [[code](https://github.com/MarkFzp/humanplus)]

- [2024.06] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning [**benchmark**] [[project](https://omni.human2humanoid.com/)] [[paper](https://arxiv.org/abs/2406.08858)] [[code](https://github.com/LeCAR-Lab/human2humanoid)]

- [2024.03] HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation [**benchmark**] [[project](https://humanoid-bench.github.io/)] [[paper](https://arxiv.org/abs/2403.10506)] [[code](https://github.com/carlosferrazza/humanoid-bench)]


<a name="BimanualDexterousMulti-FingeredManipulation" />

### Bimanual Dexterous Multi-Fingered Manipulation

- [2024.10] Learning Diverse Bimanual Dexterous Manipulation Skills From Human [**IL**] [[project](https://sites.google.com/view/bidexhd)] [[paper](https://arxiv.org/abs/2410.02477)]

- [2024.08] ACE: A Cross-platform Visual-Exoskeletons for Low-Cost Dexterous Teleoperation [**teleop**] [[project](https://ace-teleop.github.io/)] [[paper](https://arxiv.org/abs/2408.11805)][[code](https://github.com/ACETeleop/ACETeleop)]
   
- [2024.07] Bunny-Vision Pro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning [**IL**] [[project](https://dingry.github.io/projects/bunny_visionpro)] [[paper](https://arxiv.org/abs/2407.03162)][[code](https://github.com/Dingry/BunnyVisionPro)]

- [2024.04] Learning Visuotactile Skills with Two Multifingered Hands [**IL**] [**touch**] [[project](https://toruowo.github.io/hato/)] [[paper](http://arxiv.org/abs/2404.16823)][[code](https://github.com/toruowo/hato)]

- [2024.03] DexCap: Scalable and Portable Mocap Data
Collection System for Dexterous Manipulation [**IL**] [[project](https://dex-cap.github.io/)] [[paper](https://arxiv.org/abs/2403.07788)][[code](https://github.com/j96w/DexCap)]
 
- [CORL 2024] Bimanual Dexterity for Complex Tasks [**IL**] [[project](https://bidex-teleop.github.io/)] [[paper](https://openreview.net/pdf?id=55tYfHvanf)]



<a name="DualArmManipulationwithOtherEndEffectors" />

### Dual-Arm Manipulation with Other End Effectors

- [2024.10] RDT-1B: a Diffusion Foundation Model for Bimanual Manipulation [**IL**] [[github](https://github.com/thu-ml/RoboticsDiffusionTransformer)] [[paper](https://arxiv.org/pdf/2410.07864)] [[project](https://rdt-robotics.github.io/rdt-robotics/)]

- [2024.10] ALOHA Unleashed: A Simple Recipe for Robot Dexterity [**IL**] [[project](https://aloha-unleashed.github.io/)] [[paper](https://arxiv.org/abs/2410.13126)]

- [2024.09] ReKep: Spatio-Temporal Reasoning of Relational Keypoint Constraints for Robotic Manipulation [**VLM**] [[project](https://rekep-robot.github.io/)] [[paper](https://rekep-robot.github.io/rekep.pdf)][[code](https://github.com/huangwl18/ReKep)]
  
- [2024.07] VoxAct-B: Voxel-Based Acting and Stabilizing Policy for Bimanual Manipulation [**IL**] [**VLM**] [[project](https://github.com/VoxAct-B/voxactb)] [[paper](https://arxiv.org/abs/2407.04152)][[code](https://github.com/VoxAct-B/voxactb)]

- [2024.07] PerAct2: Benchmarking and Learning for Robotic Bimanual Manipulation Tasks [**IL**] [[project](https://bimanual.github.io/)] [[paper](https://arxiv.org/abs/2407.00278)][[code](https://github.com/markusgrotz/peract_bimanual)]

- [2024.01] Mobile ALOHA: Learning Bimanual Mobile Manipulation with Low-Cost Whole-Body Teleoperation [**IL**] [[project](https://mobile-aloha.github.io/)] [[paper](http://arxiv.org/abs/2401.02117)][[code(learning)](https://github.com/MarkFzp/act-plus-plus)] [[code(hardware)](https://github.com/MarkFzp/mobile-aloha)]


<a name="PhysicallySimulatedHumanoidAnimations" />

### Physically Simulated Humanoid Animations and Digital Human-Object Interaction

- [2024.10] Autonomous Character-Scene Interaction Synthesis from Text Instruction [**mocap**] [[project](https://lingomotions.com/)] [[paper](https://arxiv.org/abs/2410.03187)]

- [2024.07] Grasping Diverse Objects with Simulated Humanoids [**RL**] [[project](https://www.zhengyiluo.com/Omnigrasp-Site/)] [[paper](https://arxiv.org/abs/2407.11385)]

- [2024.06] Human-Object Interaction from Human-Level Instructions [**LLM**] [[project](https://hoifhli.github.io/)] [[paper](https://arxiv.org/abs/2406.17840)]


- [2024.06] CooHOI: Learning Cooperative Human-Object Interaction with Manipulated Object Dynamics [**RL**] [[project](https://gao-jiawei.com/Research/CooHOI/)] [[paper](https://arxiv.org/abs/2406.14558)]

- [2024.06] CORE4D: A 4D Human-Object-Human Interaction Dataset for Collaborative Object REarrangement [**mocap**] [[project](https://core4d.github.io/)] [[paper](https://arxiv.org/pdf/2406.19353)][[code](https://github.com/leolyliu/CORE4D-Instructions)]

- [2024.04] HOI-M3: Capture Multiple Humans and Objects Interaction within Contextual Environment [**mocap**] [[project](https://juzezhang.github.io/HOIM3_ProjectPage/)] [[paper](https://arxiv.org/pdf/2404.00299.pdf)][[code](https://github.com/Juzezhang/NeuralDome_Toolbox)]

- [2024.03] AnySkill: Learning Open-Vocabulary Physical Skill for Interactive Agents [**RL**] [[project](https://anyskill.github.io/)] [[paper](https://arxiv.org/abs/2403.12835)][[code](https://github.com/jiemingcui/anyskill)]
