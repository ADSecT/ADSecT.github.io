# 摘要

## 模块说明

**单词：** 固定使用 `Abstract` 。

**组成：** 一般来说，学术论文的摘要分为4个主要组成部分，分别是：

- **背景（Background）：** 摘要的开始部分通常会介绍研究领域的背景和重要性，说明该研究领域的现状和存在的问题。

- **目的（Purpose）：** 接着是介绍研究的目的，即你的研究想要解决的问题或者探讨的内容。这部分通常涉及到研究的目标和研究问题。

- **方法（Methods）：** 摘要中会简要介绍你所采用的研究方法或者技术。这包括研究的设计、实验方法、数据收集和分析方法等。
- **结果与结论（Results and Conclusions）：** 最后一部分会提到研究的主要结果和得出的结论，这部分可能包括一些关键的发现或者研究的意义。

## 通用模板

**模板一：** 大背景+存在的问题+具体最近的1篇工作（是怎么解决该问题的）+然而该工作还存在什么问题（或还没有解决的问题）+引出本文的方法和实验

- **Computation and Data Efficient Backdoor Attacks.** *ICCV, 2023.*

  - **原文：** Backdoor attacks against deep neural network (DNN) models have been widely studied. Various attack techniques have been proposed for different domains and paradigms, e.g., image, point cloud, natural language processing, transfer learning, etc. The most widely-used way to embed a backdoor into a DNN model is to poison the training data. They usually randomly select samples from the benign training set for poisoning, without considering the distinct contribution of each sample to the backdoor effectiveness, making the attack less optimal.

    A recent work [40] proposed to use the forgetting score to measure the importance of each poisoned sample and then filter out redundant data for effective backdoor training. However, this method is empirically designed without theoretical proofing. It is also very time-consuming as it needs to go through several training stages for data selection. To address such limitations, we propose a novel confidence-based scoring methodology, which can efficiently measure the contribution of each poisoning sample based on the distance posteriors. We further introduce a greedy search algorithm to find the most informative samples for backdoor injection more promptly. Experimental evaluations on both 2D image and 3D point cloud classification tasks show that our approach can achieve comparable performance or even surpass the forgetting score-based searching method while requiring only several extra epochs’ computation of a standard training process. Our code can be found at [https://github.com/WU-YU-TONG/computational_efficient_backdoor](https://github.com/WU-YU-TONG/computational_efficient_backdoor).

  - **解析：**

    - **背景：** <font color="red">Backdoor attacks</font> against deep neural network (DNN) models have been widely studied. 【第1-2句：常见套话，XX工作被广泛研究了，并存在不同领域】Various attack techniques have been proposed for different domains and paradigms, e.g., image, point cloud, natural language processing, transfer learning, etc. <font color="red">The most widely-used way</font> to embed a backdoor into a DNN model is to <font color="red">poison the training data</font>.【第3句：引出子领域：backdoor attack中的poison the training data分支】 They usually randomly select samples from the benign training set for poisoning, <font color="red">without considering</font> the distinct contribution of each sample to the backdoor effectiveness, making the attack less optimal.【第4句：介绍poison the training data工作的局限性】
    - **目的：** <font color="red">A recent work [40] proposed</font> to use the forgetting score to measure the importance of each poisoned sample and then filter out redundant data for effective backdoor training.【第5句：引出最新的工作是如何应对的】 <font color="red">However</font>, this method is empirically designed without theoretical proofing. It is also very time-consuming as it needs to go through several training stages for data selection.【第6-7句：点出最新工作仍然存在的问题（当然也是作者在本文要解决的问题）】
    - **方法：** <font color="red">To address such limitations</font>, we propose a novel confidence-based scoring methodology, which can efficiently measure the contribution of each poisoning sample based on the distance posteriors. We further introduce a greedy search algorithm to find the most informative samples for backdoor injection more promptly. 【第8-9句：简要概括本文的方法】
    - **结果：** <font color="red">Experimental evaluations on both 2D image and 3D point cloud classification tasks show that</font> our approach can achieve comparable performance or even surpass the forgetting score-based searching method while requiring only several extra epochs’ computation of a standard training process. 【第10句：总结实验结果】Our code can be found at [https://github.com/WU-YU-TONG/computational_efficient_backdoor](https://github.com/WU-YU-TONG/computational_efficient_backdoor).【第11句：可有可无，公开源码链接】

**模板二：** 大背景+存在的问题+宏观介绍目前存在的问题（尽管已经有工作，但还存在什么问题/还没解决/忽略了什么/重点在哪儿/）+引出本文的方法和实验

- **Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving.** *ACM MM, 2022*

  - **原文：** Modern autonomous vehicles adopt state-of-the-art DNN models to interpret the sensor data and perceive the environment. However, DNN models are vulnerable to different types of adversarial attacks, which pose significant risks to the security and safety of the vehicles and passengers. One prominent threat is the backdoor attack, where the adversary can compromise the DNN model by poisoning the training samples. Although lots of effort has been devoted to the investigation of the backdoor attack to conventional computer vision tasks, its practicality and applicability to the autonomous driving scenario is rarely explored, especially in the physical world.

    In this paper, we target the lane detection system, which is an indispensable module for many autonomous driving tasks, e.g., navigation, lane switching. We design and realize the first physical backdoor attacks to such system. Our attacks are comprehensively effective against different types of lane detection algorithms. Specifically, we introduce two attack methodologies (poison-annotation and clean-annotation) to generate poisoned samples. With those samples, the trained lane detection model will be infected with the backdoor, and can be activated by common objects (e.g., traffic cones) to make wrong detections, leading the vehicle to drive off the road or onto the opposite lane. Extensive evaluations on public datasets and physical autonomous vehicles demonstrate that our backdoor attacks are effective, stealthy and robust against various defense solutions. Our codes and experimental videos can be found in https://sites.google.com/view/lane-detection-attack/lda.

  - **解析：** 

