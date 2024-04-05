# 实验

**常用单词：** `Experiments / Experiment`

**常见结构：** 

- **实验设置：** 介绍实验的基础设置，包括：数据集、模型、评价指标、对比方法、实验细节等，常用单词：`Experimental Settings / Setup / Experimental Setup`。注意：有的论文会直接省略实验设置，同时把实验设置下面的二级标题提到一级标题。
  - **模型：** `Model / Backbone Models`
  - **数据集：** `Datasets`
  - **评价指标：** `Evaluation Metrics / Metrics`
  - **对比方法：** `Methods for Comparison`
  - **实验细节：** `Implementation / Implementation Details`
- **消融实验：** `Ablation Study / Ablation Studies`
- **跨数据集评估：** `Cross Datasets Generalization`
- **方法对比：** `Comparisons with State-of-the-arts / Comparison with Baseline Methods`
- **实验结果分析：** `Main Results / Analysis`

**模板：**

- **Two Heads Are Better than One: Image-Point Cloud Network for Depth-Based 3D Hand Pose Estimation.** *AAAI, 2023.*（AAAI 2023最佳论文奖）

  ```
  4. Experiment
    4.1. Dataset and Evaluation Metrics（数据集和评价指标）
      4.1.1. Single-Hand dataset
      4.1.2. Hand-Object dataset
      一段关于Evaluation Metrics的文字
    4.2. Implementation Details（实验细节）
    4.3. Ablation Study（消融实验）
      4.3.1. Comparing with Different Data Representation
      4.3.2. Effect of 2D-3D Projection
      4.3.3. Effect of Components in Iterative Correction
    4.4. Comparisons with State-of-the-arts（和最新SOTA的比较）
    4.5. Qualitative Results（定性结果）
  ```

- **Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation.** *AAAI, 2023.* （AAAI杰出学生论文奖）

  ```
  4. Experiments
    4.1. Setup
      4.1.1. Dataset
      4.1.2. Task setting
      4.1.3. Implementation Details
    4.2. Performance on Synthesized Domain Shifts（在Synthesized Domain上的性能变化）
    4.3. Performance on Real Domains Shifts（在Real Domains上的性能变化）
    4.4. Analysis
      4.4.1. How do the prompts’ size and location affect the model’s performance?
      4.4.2. What are the contributions of DAP and DSP, respectively?
  ```

- **DropMessage: Unifying Random Dropping for Graph Neural Networks.** *AAAI, 2023.*  （AAAI 2023 杰出论文奖）

  ```
  4. Experiments
    4.1. Experimental Setup（实验设置部分）
      4.1.1. Datasets
      4.1.2. Baseline Methods
      4.1.3. Backbone Models
    4.2. Comparison Results（对比分析）
      4.2.1. Effect of random dropping methods
      4.2.2. Comparison of different dropping methods
    4.3. Additional Results（实验结果分析）
      4.3.1. Robustness analysis
      4.3.2. Over-smoothing analysis
      4.3.3. Training process analysis
      4.3.4. Information diversity analysis
  ```

  
