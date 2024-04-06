# 相关工作

## 模块介绍

**单词：** 固定使用单词 `Related Work`。

**组成：** 

- **数量：** 一般来说，每篇论文可以由1-3个相关工作组成；
- **段落：** 每个相关工作中主要分为2个自然段，第一段介绍相关工作，第二段用一句话总结；
- **内容：** 内容上可以分为两种形式：①介绍已有工作，然后引出本文与已有工作的不同之处；②介绍相关工作，引出本文想表达的"言外之意"。

## 通用模板

- **BadDet: Backdoor Attacks on Object Detection.** *ECCV, 2022.*
  - **原文：** **Object Detection.** In the deep learning, object detection models can be categorized into two-stage detectors and one-stage detectors [41]. The former first find a region of interest and then classify it, including SPPNet [12], Faster-RCNN [28], Feature Pyramid Networks (FPN) [16], etc.  The latter directly predict class probabilities and bounding box coordinates, including YOLO[26], Single Shot MultiBox Detector (SSD) [20], RetinaNet [17], etc.  In the experiments, we consider typical object detection models from both categories, which are Faster-RCNN and YOLOv3.
  - **解析：** 本文是一篇针对目标检测的后门攻击论文。在相关工作中，有Backdoor Attack和Object Detection两部分。在Object Detection中，首先介绍目标检测（Object Detection）模型的分类和特点；然后介绍"言外之意"，即：在实验中，作者考虑了两个类别的典型目标检测模型，即Faster-RCNN和YOLOv3。
