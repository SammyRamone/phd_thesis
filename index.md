## Learning Motion Skills for a Humanoid Robot

This page aggregates all videos and links for my PhD thesis titled "Learning Motion Skills for a Humanoid Robot".

### Videos

#### Hardware
- [Overview](https://www.youtube.com/watch?v=UsH6QIKzr7Q)

#### Fall Managemen
- [HCM & fall robustness](https://cloud.mafiasi.de/s/zoPP4HTf7sa46S3)

#### OptiQuint
- [Generalization](https://cloud.mafiasi.de/s/kTjaEpwyqqi2oyG)
- [On RoboCup competition](https://cloud.mafiasi.de/s/3QPJFkaLab7XDEY)
- [More videos from RoboCup competitions](https://cloud.mafiasi.de/s/6Gc3fXdyW6Pdoj7)
- [Manual controlled walking example](https://cloud.mafiasi.de/s/CDenApyigfBf226)
- [Winning push-recovery challenge](https://cloud.mafiasi.de/s/qik7DWatawgyaGt)
- [Extract from HLVS final](https://cloud.mafiasi.de/s/WwM9A4XgyFpEwiA)
- [Example from HLVS](https://cloud.mafiasi.de/s/Mz93nnqrLKgnMJ2)
- [Usage in Running Robot Competition](https://cloud.mafiasi.de/s/q4zQo7JJ8rEfZcT)
- [Walking on stairs in Running Robot Competition](https://cloud.mafiasi.de/s/Xt233Se8eyKJnY2)

#### DeepQuintic
- [Choice of action space]()
- [Network initialization training](https://cloud.mafiasi.de/s/S5TXddAcmDzDpZt)
- [Network initialization result]()
- [Network initialization result with Walker2DPybulletEnv](https://cloud.mafiasi.de/s/teSjfMrR4ptoGoW)
- [Adaptive Phase](https://cloud.mafiasi.de/s/gn5Qdg38BLME4iA)
- [Usage of Arms](https://cloud.mafiasi.de/s/wjLS7fLHfMziYt7)
- [Quality of Reference Motion](https://cloud.mafiasi.de/s/gtbRemqY7twSwYt)
- [Generalization to different robots](https://cloud.mafiasi.de/s/2dCyTAENn5xqYaf)
- [Transfer to Webots and ROS](https://cloud.mafiasi.de/s/FggQK6H989f5KDT)
- [Transfer to real robot](https://cloud.mafiasi.de/s/2zM37Jdnok2dcpE)


### Links

#### Hardware
- Model
  - [Onshape Model](https://cad.onshape.com/documents/8c6aa9a8917f764cb7039c2d/w/af71e5083243affec9ac82a8/e/e42d9814ef6f704f62b6758c)
  - [Wolfgang-OP URDF](https://github.com/bit-bots/wolfgang_robot/tree/master/wolfgang_description)
  - [Wolfgang-OP MoveIt config](https://github.com/bit-bots/wolfgang_robot/tree/master/wolfgang_moveit_config)
- Simulation Environment
  - [Wolfgang-OP PyBullet Simulation](https://github.com/bit-bots/wolfgang_robot/tree/master/wolfgang_pybullet_sim)
  - [Wolfgang-OP Webots Simulation](https://github.com/bit-bots/wolfgang_robot/tree/master/wolfgang_webots_sim)
- Electronics
  - [CORE](https://github.com/bit-bots/wolfgang_core)
  - [IMU Module](https://github.com/bit-bots/bitbots_imu_dxl)
  - [FPS Module](https://github.com/bit-bots/bit_foot)
  - [CVSU](https://github.com/bit-bots/wolfgang_constant_voltage)
- Hardware Interface
  - Modified DXL Communcation [SDK](https://github.com/bit-bots/DynamixelSDK) and [Library](https://github.com/bit-bots/dynamixel-workbench)
  - [Hardware Interface](https://github.com/bit-bots/bitbots_lowlevel)
- [Other robot models](https://github.com/bit-bots/humanoid_robots_ros2)

#### Fall Management
- [DSD](https://github.com/bit-bots/dynamic_stack_decider) (made in cooperation with Martin Poppinga, Timon Engelke, and Finn-Thorben Sell)
- [HCM](https://github.com/bit-bots/bitbots_motion/tree/master/bitbots_hcm)

#### OptiQuint
- [Tutorial](https://bit-bots.github.io/quintic_walk/)
- [Spline library](https://github.com/bit-bots/bitbots_motion/tree/master/bitbots_splines) (based on work of team Rhoban. Refactored by Timon Engelke and Finn-Thorben Sell)
- [Parameter Optimization](https://github.com/bit-bots/parallel_parameter_search)
- [Walk skill](https://bit-bots.github.io/quintic_walk/)
- [Odometry](https://github.com/bit-bots/bitbots_motion/tree/master/bitbots_odometry)
- [Stand-up Skill](https://github.com/bit-bots/bitbots_motion/tree/master/bitbots_dynamic_kick) (in cooperation with Sebastian Stelter)
- [Kick Skill](https://github.com/bit-bots/bitbots_motion/tree/master/bitbots_dynamic_kick) (made by Timon Engelke, Finn-Thorben Sell, and Frederico Bormann)

#### DeepQuintic
- [DeepQuintic Walk](https://github.com/bit-bots/deep_quintic)
- [RL Motion Runner](https://github.com/bit-bots/bitbots_motion/tree/master/bitbots_rl_motion)
- [stable-baselines3](https://github.com/SammyRamone/stable-baselines3) (used PPO implementation)
- [rl-baselines3-zoo](https://github.com/SammyRamone/rl-baselines3-zoo) (training and hyperparameter optimization)
