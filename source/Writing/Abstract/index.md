# Abstract

4段论，分别是：研究背景（Background）、研究现状（Status）、主要方法（Method）、结论（Conclusions）

## 1.Background（研究背景）

把问题放在一个广泛的背景下，突出研究的目的。

- DNN models <u>are vulnerable to different types of adversarial attacks</u>, which <u>pose significant risks to the security and safety of</u> the vehicles and passengers.（……容易受到各种各样的对抗性攻击，这对……构成了重大安全风险。）—— **[2022-ACM MM] Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving.**



## 2.Status（研究现状）

介绍与现有工作的不同之处或尚未解决的问题。

- <u>Although lots of efforts has been devoted to</u> the investigation of the backdoor attack to conventional computer vision tasks, its practicality and applicability to the autonomous driving scenario <u>is rarely explored</u>, especially in the physical world.（尽管……已经进行了大量的研究，但是……方面仍然很少被探索。）—— **[2022-ACM MM] Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving.**

## 3.Method（主要方法）

简要描述应用的主要方法或处理方法。





## 4.Conclusions（实验结论）

指出主要结论或实验解释。



## 5.模板

**结构：** 背景介绍+存在问题+最新工作+最新工作存在问题+主要方法+实验结论

**文献：** **Computation and Data Efficient Backdoor Attacks.** *ICCV, 2023.*

**原文：**

```
Backdoor attacks against deep neural network (DNN) models have been widely studied. Various attack techniques have been proposed for different domains and paradigms, e.g., image, point cloud, natural language processing, transfer learning, etc. The most widely-used way to embed a backdoor into a DNN model is to poison the training data. They usually randomly select samples from the benign training set for poisoning, without considering the distinct contribution of each sample to the backdoor effectiveness, making the attack less optimal.

A recent work [40] proposed to use the forgetting score to measure the importance of each poisoned sample and then filter out redundant data for effective backdoor training. However, this method is empirically designed without theoretical proofing. It is also very time-consuming as it needs to go through several training stages for data selection. To address such limitations, we propose a novel confidence-based scoring methodology, which can efficiently measure the contribution of each poisoning sample based on the distance posteriors. We further introduce a greedy search algorithm to find the most informative samples for backdoor injection more promptly. Experimental evaluations on both 2D image and 3D point cloud classification tasks show that our approach can achieve comparable performance or even surpass the forgetting score-based searching method while requiring only several extra epochs’ computation of a standard training process. Our code can be found at https://github.com/WU-YU-TONG/ computational_efficient_backdoor.
```

**解析：**

- **背景介绍：** Backdoor attacks against deep neural network (DNN) models have been widely studied. Various attack techniques have been proposed for different domains and paradigms, e.g., image, point cloud, natural language processing, transfer learning, etc. The most widely-used way to embed a backdoor into a DNN model is to poison the training data.【背景介绍：1）该工作被广泛研究了；2）举例说明，针对不同领域提出了许多工作； 3）最常见的工作是XXX工作——引出本文要研究的内容】

- **存在问题：** They usually randomly select samples from the benign training set for poisoning, <u>without considering the distinct contribution of each sample to the backdoor effectiveness, making the attack less optimal.</u> 【存在问题：没有考虑每个样本对后门有效性的贡献，导致攻击不理想。】
- **最新工作：** <u>A recent work [40] proposed</u> to use the forgetting score to measure the importance of each poisoned sample and then filter out redundant data for effective backdoor training.【最新工作是[40]这篇文献工作】
- **最新工作存在的问题：** 



