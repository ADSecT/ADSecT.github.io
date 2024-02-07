# 总结

**单词：** 总结使用固定单词 `Conclusion`。

**组成：** 总结部分不需要再阐述研究背景了，直接从方法、实验和结论进行总结即可。

**时态：** 注意总结的时态问题，常使用 `一般过去时` 。

**模板：**

- **Untargeted Backdoor Attack Against Object Detection.** *ICASSP, 2023.*
  - **原文：** In this paper, we revealed the backdoor threats in object detection by introducing a simple yet effective poison-only untargeted attack. Speciﬁcally, we removed the bounding boxes of a few randomly selected objects after adding pre-deﬁned trigger patterns to the center of object areas.   We demonstrated that our attack is effective and stealthy under both digital and physical settings.   We also showed that our method is resistant to potential backdoor defenses.   Our method can serve as a useful tool to examine the backdoor robustness of object detectors, leading to the design of more secure models.
  - **解析：**
    - **第1句话：** `In this paper` 开头，开门见山的方式介绍本文的工作，即：揭示（revealed）了在目标检测领域也存在后门的威胁。
    - **第2-4句话：** 使用 `Specifically` 展开介绍，介绍了具体的后门攻击方法， 证明 `demonstrated` 了在数字世界和物理世界的有效性，同时 `showed` 展示了这种攻击方法能够对抗现有的后门攻击方法。
    - **第5句话：** 升华部分，不是为了攻击而攻击，攻击是为了发现、检查模型存在的问题、漏洞、缺陷，进而来设计更安全的模型。
