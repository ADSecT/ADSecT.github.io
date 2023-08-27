# Introduction
- Researchers have proposed a variety of novel attacks against DNN models for computer vision [3, 21, 27, 33, 34, 54, 58], natural language processing [5, 10, 44, 60], reinforcement learning [25, 53, 65], etc. However, there are no studies investigating the backdoor opportunity against the lane detection systems.
  - **来源：** Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving
  - **备注：** 研究人员已经对CV、RL、NLP等领域提出了后门攻击的方法，然而还没有调查对车道线检测系统的后门攻击相关的研究。【新方法用在老场景中】
- Besides, the physical triggers used to attack face classification models cannot be applied to lane detection due to the semantic differences between these two scenarios.  The physical triggers need to be carefully redesigned.
  - **来源：** Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving
  - **备注：** 介绍与已有方法的不同之处，已有方法虽然也实现了后门攻击但没法迁移到车道线检测系统中，因此针对车道线检测系统的后门攻击需要仔细重新设计。【】
