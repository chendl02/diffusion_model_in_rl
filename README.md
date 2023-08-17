# Diffusion Model in RL

We follow the idea of [this repo](https://github.com/opendilab/awesome-diffusion-model-in-rl/tree/main).

This is a collection of research papers for **Diffusion Model in Robot Learning**.
And the repository will be continuously updated to track the frontier of Diffusion RL.


## Table of Contents

- [Papers](#papers)

  - [Arxiv](#arxiv)
  - [ICML 2023](#icml-2023)
  - [ICLR 2023](#iclr-2023)
  - [ICRA 2023](#icra-2023)
  - [Neurips 2022](#neurips-2022)
  - [ICML 2022](#icml-2022)
  - [Misc](#Misc)


## Papers

```
format:
- [title](paper link) [links]
  - author1, author2, and author3...
  - publisher
  - key 
  - code 
  - experiment environment
```

### Arxiv

- [Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/abs/2303.04137)
  - Cheng Chi, Siyuan Feng, Yilun Du, Zhenjia Xu, Eric Cousineau, Benjamin Burchfiel, Shuran Song
  - Key: Robot Manipulation
  - ExpEnv: Robomimic, Push-T, Multimodal Block Pushing, Franka Kitchen

- [Diffusion-based Generation, Optimization, and Planning in 3D Scenes](https://arxiv.org/abs/2301.06015)
  - Siyuan Huang, Zan Wang, Puhao Li, Baoxiong Jia, Tengyu Liu, Yixin Zhu, Wei Liang, Song-Chun Zhu
  - Key: 3D Scene Understanding, Optimization, Planning
  - Code: [official](https://github.com/scenediffuser/Scene-Diffuser)
  - ExpEnv: [ScanNet](http://www.scan-net.org/), [MultiDex](https://github.com/tengyu-liu/GenDexGrasp), [PROX](https://prox.is.tue.mpg.de/index.html)

- [Goal-Conditioned Imitation Learning using Score-based Diffusion Policies](https://arxiv.org/abs/2302.01877)
  - Zhixuan Liang, Yao Mu, Mingyu Ding, Fei Ni, Masayoshi Tomizuka, Ping Luo
  - Key: Goal-Conditioned Imitation Learning, Robotics
  - ExpEnv: CALVIN, Block-Push, Relay Kitchen

- ✅[Learning Universal Policies via Text-Guided Video Generation](https://arxiv.org/pdf/2302.00111.pdf)
  - Yilun Du, Mengjiao Yang, Bo Dai...
  - Key: Cast the sequential decision making problem as a text-conditioned video generation problem.
  - ExpEnv

### ICML 2023

- [Contrastive Energy Prediction for Exact Energy-Guided Diffusion Sampling in Offline Reinforcement Learning](https://arxiv.org/abs/2304.12824)
  - Cheng Lu, Huayu Chen, Jianfei Chen, Hang Su, Chongxuan Li, Jun Zhu
  - Publisher:  ICML 2023 (long talk)
  - Key: Offline RL, Constrained Policy Optimization
  - Code: [official](https://github.com/ChenDRAG/CEP-energy-guided-diffusion)
  - ExpEnv: [MuJoco](https://github.com/openai/mujoco-py), [D4RL](https://github.com/rail-berkeley/d4rl)

- [Discrete Diffusion Reward Guidance Methods for Offline Reinforcement Learning](https://openreview.net/pdf?id=s4cSgzGudq) 
  - Matthew Coleman, Olga Russakovsky, Christine Allen-Blanchette, Ye Zhu
  - Publisher: ICML 2023 Workshop SODS
  - Key:  Reduced dimension, Discrete tasks
  - ExpEnv: [D4RL](https://github.com/rail-berkeley/d4rl)

- ✅[AdaptDiffuser: Diffusion Models as Adaptive Self-evolving Planners](https://arxiv.org/abs/2304.02532)
  - Moritz Reuss, Maximilian Li, Xiaogang Jia, Rudolf Lioutikov
  - Publisher:  ICML 2023 (oral)
  - Key: Planning, Generalizability
  - ExpEnv: Maze2D, MuJoCo, KUKA Robot

### ICLR 2023

- [Is Conditional Generative Modeling all you need for Decision-Making?](https://arxiv.org/abs/2211.15657)
  - Anurag Ajay, Yilun Du, Abhi Gupta, Joshua Tenenbaum, Tommi Jaakkola, Pulkit Agrawal
  - Publisher: ICLR 2023
  - Key: Offline RL, Generative Model, Policy Optimization
  - Code: [official](https://github.com/anuragajay/decision-diffuser/tree/main/code)
  - ExpEnv: [D4RL](https://github.com/rail-berkeley/d4rl)

- [Imitating Human Behaviour with Diffusion Models](https://arxiv.org/abs/2301.10677)
  - Tim Pearce, Tabish Rashid, Anssi Kanervisto, Dave Bignell, Mingfei Sun, Raluca Georgescu, Sergio Valcarcel Macua, Shan Zheng Tan, Ida Momennejad, Katja Hofmann, Sam Devlin
  - Publisher: ICLR 2023
  - Key: Offline RL, Policy Optimization, Imitation Learning
  - ExpEnv: Claw, Kitchen, CSGO

- [Offline Reinforcement Learning via High-Fidelity Generative Behavior Modeling](https://arxiv.org/abs/2209.14548)
  - Huayu Chen, Cheng Lu, Chengyang Ying, Hang Su, Jun Zhu
  - Publisher: ICLR 2023
  - Key: Offline RL, Generative models
  - Code: [official](https://github.com/ChenDRAG/SfBC)
  - ExpEnv: [D4RL](https://github.com/rail-berkeley/d4rl)

### ICRA 2023

- [Guided Conditional Diffusion for Controllable Traffic Simulation](https://arxiv.org/abs/2210.17366)
  - Ziyuan Zhong, Davis Rempe, Danfei Xu, Yuxiao Chen, Sushant Veer, Tong Che, Baishakhi Ray, Marco Pavone
  - Publisher: ICRA 2023
  - Key: Traffic Simulation, Multi-Agent
  - ExpEnv: [nuScenes](https://github.com/nutonomy/nuscenes-devkit)

### Neurips 2022

- [Diffusion Policies as an Expressive Policy Class for Offline Reinforcement Learning](https://arxiv.org/abs/2208.06193)
  - Zhendong Wang, Jonathan J Hunt, Mingyuan Zhou
  - Publisher:  Neurips Deep RL Workshop 2022
  - Key: Offline RL, Policy Optimization
  - Code: [official](https://github.com/zhendong-wang/diffusion-policies-for-offline-rl), [unofficial](https://github.com/twitter/diffusion-rl)
  - ExpEnv: [MuJoco](https://github.com/openai/mujoco-py), [D4RL](https://github.com/rail-berkeley/d4rl)

### ICML 2022

- ✅[Planning with Diffusion for Flexible Behavior Synthesis](https://arxiv.org/abs/2205.09991)
  - Michael Janner, Yilun Du, Joshua B. Tenenbaum, Sergey Levine
  - Publisher:  ICML 2022 (long talk)
  - Key: Offline RL,  Model-based RL, Trajectory Optimization
  - Code: [official](https://github.com/jannerm/diffuser)
  - ExpEnv: [MuJoco](https://github.com/openai/mujoco-py), [D4RL](https://github.com/rail-berkeley/d4rl)


### Misc

- [Structured Denoising Diffusion Models in Discrete State-Spaces](https://arxiv.org/abs/2208.06193)
  - Zhendong Wang, Jonathan J Hunt, Mingyuan Zhou
  - Publisher:  Neurips Deep RL Workshop 2022
  - Key: Offline RL, Policy Optimization
  - Code: [official](https://github.com/google-research/google-research/tree/master/d3pm)
