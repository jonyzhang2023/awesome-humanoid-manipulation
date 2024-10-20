# awesome-humanoid-manipulation 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)


A curated list of awesome papers and resources on **humanoid manipuation**, or humanoid robot-object interaction. This repo is inspired by [awesome-humanoid-learning](https://github.com/jonyzhang2023/awesome-humanoid-learning).

_Note_: We also included papers on two relevant topics: 1) Bimanual multi-fingered manipulation 2) humanoid manipulation in physically based animation.

---

## Contents
- [Humanoid Models](#Models)
  - [Humanoids](#Humanoids)
  - [Dexterous Hands](#DexterousHands) 
- [Workshops](#Workshops)
- [Papers](#Papers)
  - [Humanoid Robot Manipulation](#HumanoidRobotManipulation)
  - [Bimanual Dexterous Multi-Fingered Manipulation](#BimanualDexterousMulti-FingeredManipulation)
  - [Physically Simulated Humanoid Animations](#PhysicallySimulatedHumanoidAnimations)


<a name="Models" />

## Robot Models

<a name="Humanoids" />

### Humanoids

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| H1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/h1_description), [USD](https://github.com/unitreerobotics/unitree_model/tree/main/H1/usd) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| G1 | Unitree | [URDF & MJCF](https://github.com/unitreerobotics/unitree_ros/tree/master/robots/g1_description) | BSD-3-Clause | ✔️ | ✔️ | ✔️ |
| GR-1 | FFTAI | [URDF](https://github.com/FFTAI/Wiki-GRx-Models/tree/master/GRX/GR1), [MJCF](https://github.com/FFTAI/wiki-mjcf/) | GPL-3.0 | ✔️ | ✔️ | ✔️ |


<a name="DexterousHands" />

### Dexterous Hands

| Name | Maker | Formats | License | Meshes | Inertias | Collisions |
|------|-------|---------|---------|--------|----------|------------|
| Ability Hand | PSYONIC, Inc. | [MJCF](https://github.com/psyonicinc/ability-hand-api/tree/master/URDF/mujoco), [URDF](https://github.com/psyonicinc/ability-hand-api/tree/master/URDF) | ✖️ | ✔️ | ✔️ | ✖️ |
| Allegro Hand | Wonik Robotics | [URDF](https://github.com/RobotLocomotion/models/tree/master/allegro_hand_description/urdf), [MJCF](https://github.com/shadow-robot/sr_common/tree/6fcee98982499a645c0812a89b6e70a920f2ed33/sr_description/mujoco_models) | BSD | ✔️ | ✔️ | ✔️ |
| Shadow Hand | Shadow Robot | [URDF](https://github.com/shadow-robot/sr_common/tree/noetic-devel/sr_description/mujoco_models/urdfs), [MJCF](https://github.com/google-deepmind/mujoco_menagerie/tree/main/wonik_allegro) | BSD | ✔️ | ✔️ | ✔️ |

<a name="Workshops" />

## Workshops

CORL 2024 [[Workshop on Whole-body Control and Bimanual Manipulation: Applications in Humanoids and Beyond](https://wcbm-workshop.github.io/)]

ECCV 2024 [[1st Workshop on Cooperative Intelligence for Embodied AI](https://coop-intelligence.github.io/)]

<a name="Papers" />

## Papers

YYYY.MM is the date when paper appears on arxiv.org (if available).

<a name="HumanoidRobotManipulation" />

### Humanoid Robot Manipulation

- [2024.10] OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation [**IL**] [[project](https://ut-austin-rpl.github.io/OKAMI/)] [[paper](http://arxiv.org/abs/2410.11792)] 

- [2024.10] Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies [**IL**] [**diffusion**] [[project](https://humanoid-manipulation.github.io/)] [[paper](https://arxiv.org/abs/2410.10803)] [[code(Learning)](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)][[code(Teleop)](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)]

- [2024.07] Open-TeleVision Teleoperation with Immersive Active Visual Feedback [**IL**] [[project](https://robot-tv.github.io/)] [[paper](https://arxiv.org/abs/2407.01512)] [[code](https://github.com/OpenTeleVision/TeleVision)]

- [2024.07] GRUtopia: Dream General Robots in a City at Scale [**benchmark**] [[doc](https://grutopia.github.io/)] [[paper](https://arxiv.org/abs/2407.10943)] [[project&code](https://github.com/OpenRobotLab/GRUtopia)]

- [2024.07] BiGym: A Demo-Driven Mobile Bi-Manual Manipulation Benchmark [**benchmark**] [[project](https://chernyadev.github.io/bigym)] [[paper](https://arxiv.org/abs/2407.07788)] [[code](https://github.com/YanjieZe/Humanoid-Teleoperation)]

- [2024.06] HumanPlus: Humanoid Shadowing and Imitation from Humans [**IL**] [[project](https://humanoid-ai.github.io/)] [[paper](https://arxiv.org/abs/2406.10454)] [[code](https://github.com/MarkFzp/humanplus)]

- [2024.06] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning [**benchmark**] [[project](https://omni.human2humanoid.com/)] [[paper](https://arxiv.org/abs/2406.08858)] [[code](https://github.com/LeCAR-Lab/human2humanoid)]

- [2024.03] HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation [**benchmark**] [[project](https://humanoid-bench.github.io/)] [[paper](https://arxiv.org/abs/2403.10506)] [[code](https://github.com/carlosferrazza/humanoid-bench)]


<a name="BimanualDexterousMulti-FingeredManipulation" />

### Bimanual Dexterous Multi-Fingered Manipulation

- [2024.10] Learning Diverse Bimanual Dexterous Manipulation Skills From Human [**IL**] [[project](https://sites.google.com/view/bidexhd)] [[paper](https://arxiv.org/abs/2410.02477)]
 
- [2024.07] Bunny-Vision Pro: Real-Time Bimanual Dexterous Teleoperation for Imitation Learning [**IL**] [[project](https://dingry.github.io/projects/bunny_visionpro)] [[paper](https://arxiv.org/abs/2407.03162)][[code](https://github.com/Dingry/BunnyVisionPro)]

- [2024.03] DexCap: Scalable and Portable Mocap Data
Collection System for Dexterous Manipulation [**IL**] [[project](https://dex-cap.github.io/)] [[paper](https://arxiv.org/abs/2403.07788)][[code](https://github.com/j96w/DexCap)]
 
- [CORL 2024] Bimanual Dexterity for Complex Tasks [**IL**] [[project](https://bidex-teleop.github.io/)] [[paper](https://openreview.net/pdf?id=55tYfHvanf)]


<a name="PhysicallySimulatedHumanoidAnimations" />

### Physically Simulated Humanoid Animations

- [2024.07] Grasping Diverse Objects with Simulated Humanoids [**RL**] [[project](https://www.zhengyiluo.com/Omnigrasp-Site/)] [[paper](https://arxiv.org/abs/2407.11385)]

