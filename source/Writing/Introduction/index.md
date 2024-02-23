# 引言

**单词：** 引言部分，使用固定单词 `Introduction`。

**组成：** 一般来说，学术论文的引言分为4个主要的段落，分别是：

- **第一段：背景介绍（Background）：** 引言的开始部分通常会介绍研究领域的背景和重要性，说明该研究领域的现状和存在的问题。
- **第二段：研究现状（Related Work）：** 介绍研究现状，重点介绍目前问题解决的程度或者尚未解决的问题，目的是引出自己的研究目标和方法。
- **第三段：方法（Methods）：** 介绍你所采用的研究方法或者技术。
- **第四段：结果与结论（Results and Conclusions）**： 介绍实验的内容、主要结果以及得出的结论，这部分可能包括一些关键的发现或者研究的意义。
- **第五段：贡献总结（Contributions）：** 总结本文章的贡献，大约2-3个点。

## 研究现状

**如何表明本文与之前工作的不同之处？**

- **Moiré Backdoor Attack (MBA): A Novel Trigger for Pedestrian Detectors in the Physical World.** *ACM MM, 2023.*
  - While current methods have primarily focused on backdoor attacks for traffic sign recognition [5, 6, 18], image classification [30, 31, 33, 48], and face recognition [3, 14, 41], <font color="red">there has been little exploration into</font> backdoor attacks against pedestrian detection [21, 22]. Therefore, in this paper, we aim to evaluate security and identify potential risks by exploring physical backdoor attacks on this safety-critical task.【目前的方法主要集中在交通标志识别、图像分类和人脸识别的后门攻击上，对行人检测的后门攻击的探索很少(little exploration into)。】
- **Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving.** *ACM MM, 2022.*
  - Researchers have proposed a variety of novel attacks against DNN models for computer vision [3, 21, 27, 33, 34, 54, 58], natural language processing [5, 10, 44, 60], reinforcement learning [25, 53, 65], etc. <font color="red">However, there are no studies investigating</font> the backdoor opportunity against the lane detection systems.【研究人员提出了各种针对计算机视觉，自然语言处理，强化学习等DNN模型的新攻击。然而，还没有研究调查(there are mo studies investigating)针对车道检测系统的后门机会。】



## 贡献总结

**如何引出论文的贡献？**

- **Moiré Backdoor Attack (MBA): A Novel Trigger for Pedestrian Detectors in the Physical World.** *ACM MM, 2023.*
  - Our contributions can be summarized as follows:
- **TEDAug: A Text-driven Augmentation for Pedestrian Detection.**
  - Our main contributions are summarized as follows:
- **Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving.** *ACM MM, 2022.*
  - To summarize, we make the following contributions:



**如何展示这是一篇开山之作？**

- **Moiré Backdoor Attack (MBA): A Novel Trigger for Pedestrian Detectors in the Physical World.** *ACM MM, 2023.*
  - <font color="red">To our knowledge</font>, we are<font color="red"> the first to</font> use Moiré patterns as triggers for physical backdoor attacks. 【据我们所知(To our knowledge)，我们是第一个(the first to)使用摩尔纹(Moiré)模式作为物理后门攻击触发器的。】
- **Untargeted Backdoor Attack Against Object Detection.** *ICASSP, 2023.*
  - <font color="red">To the best of our knowledge</font>, this is the ﬁrst backdoor attack against this mission-critical task.【据我们所知(To the best of our knowledge)，这是针对这项关键任务的第一次(the first)后门攻击。】



**如何表明做了大量充足的实验？**

- **Moiré Backdoor Attack (MBA): A Novel Trigger for Pedestrian Detectors in the Physical World.** *ACM MM, 2023.*
  - <font color="red">Through comprehensive experimentation on</font> two pedestrian detectors and two <font color="red">benchmark datasets</font>, our proposed MBA demonstrates <font color="red">outstanding</font> attack effectiveness and stealthiness in both digital and physical space. 【通过在两个行人检测器和两个基准数据集上的综合实验(comprehensive experimentation)，所提出的MBA在数字和物理空间中都展示了出色的(outstanding)攻击有效性(effectiveness)和隐蔽性(stealthiness)。】

