# Experiments

## 1.章节结构

AI方向论文的章节结构：

```
4 Experiments
4.1. Experimental Settings/Setup（实验环境）
	4.1.1. Datasets
	4.1.2. Evaluation Metrics/Metrics
	※4.1.3. Methods for Comparison（介绍对比的方法）
	4.1.3. Implementation（实验环境的一些设计，实验细节）
※4.2. Comparison with Baseline Methods（和Baseline的对比，验证优越性）
4.3. Ablation Study/Studies（消融实验）
※4.4. Cross Dataset Generalization（跨数据集评估）
```



## 2.Evaluation Metrics（评价指标）

**常用词：** Evaluation Metrics、Metrics



**开门见山型：** 介绍评价指标/介绍评价指标+评估内容

- We adopt six classical metrics, including xx1, xx2, xx3, xx4, xx5 and xx6 for our evaluations. 
- We utilize the COCO-style mean Average Precision (mAP) as the evaluation metrics.
- We utilize the COCO-style mean Average Precision (mAP) as the evaluation metrics to assess the performance of our proposed method on different pedestrian detectors. 



**创新型：** 要介绍相关工作评价指标的不适用，然后提出自己的评价指标

- In classification-based tasks, the performance of backdoor attacks is usually measured by Benign Accuracy (BA) and Attack Success Rate (ASR), which are calculated based on the classification accuracy. However, such metrics may be not suitable to evaluate the backdoor attack performance in the xxx task, where the model output for one image is a set of continuous points.（介绍相关工作的评价指标 + However转折 + 介绍不适用的原因）













