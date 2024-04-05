# 实验

## 通用教程

**常用单词：** `Experiments / Experiment / Experiment & Analysis`

**常见结构：** 

- **实验设置：** 介绍实验的基础设置，包括：数据集、模型、评价指标、对比方法、实验细节等，常用单词：`Experimental Settings / Setup / Experimental Setup`。注意：有的论文会直接省略实验设置，同时把实验设置下面的二级标题提到一级标题。
  - **模型：** `Model / Backbone Models / Model Architecture` 或 `victim Models / victim 3D DNNs / Target Model` （攻击论文常用）
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


## 攻击类论文教程

攻击类的论文，除了可以使用上述的通用教程之外，还可以使用基于下列调整的内容：

- **模型：** 除了常规的单词表达外，还常用 `Target Models` （目标模型）、 `Victim Models` （受害者模型）等词汇。
- **实验设置/实验细节：** 除了常规的单词表达外，还常用 `Attack Settings` （攻击设置）。
- **实验结果分析：** 常常需要包括 `Attack Effectiveness` （攻击有效性）和 `Attack Stealthiness` （攻击隐蔽性）。
- **反防御方法（安全论文特有）：** 常用  `Countermeasure / Defense Experiments / Resistance to Backdoor Defenses`  等词汇。

**模板：**

- **Backdoor Attacks via Machine Unlearning.** *AAAI, 2024.*

  ```
  4. Experiments
    4.1. Experimental Settings
    	4.1.1. Datasets and Models
    	4.1.2. Parameter and Attack Settings（Parameter类似Implementation部分；Attack Settings则是介绍攻击相关设置）
    	4.1.3. Baseline and Evaluation Metrics
    4.2. Results for the Attack without Poisoning（不中毒的表现）
    4.3. Results for the Attack with Poisoning（中毒的表现）
    4.4. Results for the Black-box Setting
  ```

- **Beyond Traditional Threats: A Persistent Backdoor Attack on Federated Learning.** *AAAI, 2024.*

  ```
  4. Experiment & Analysis
    4.1. Experiment Setup
      4.1.1. Datasets & Model Architecture
      4.1.2. Parameters for training
      4.1.3. Evaluation Metric
    4.2. Full Combination Backdoor Attack vs. Distributed Backdoor Attack
    4.3. Why FCBA Attack Persistence Is High?
    4.4. Analysis of Crucial Factors in FCBA
    4.5. Robustness of FCBA
  ```

- **COMBAT: Alternated Training for Effective Clean-Label Backdoor Attacks.** *AAAI, 2024.*

  ```
  4. Experiments
    4.1. Experimental Setup
    4.2. Attack Experiments
      4.2.1. White-box settings
      4.2.2. Black-box settings
    4.3. Defense Experiments
      4.3.1. Frequency-based defense
      4.3.2. Neural Cleanse
      4.3.3. Fine-pruning
      4.3.4. STRIP
      4.3.5. GradCAM inspection
    4.4. Role of the Adversarial Avoidance Loss
    4.5. Ablation Studies
      4.5.1. Alternated training
      4.5.2. Performance w.r.t poisoning rates
  ```

- **Conditional Backdoor Attack via JPEG Compression.** *AAAI, 2024.*

  ```
  4. Evaluation
    4.1. Experimental Settings
      4.1.1. Dataset
      4.1.2. Compared Backdoor Attacks
    4.2. Attack Effectiveness（攻击有效性）
    4.3. Attack Stealthiness（攻击隐蔽性）
    4.4. Resistance to Backdoor Defenses
      4.4.1. Neural Cleanse
      4.4.2. STRIP
      4.4.3. I-BAU
      4.4.4. ANP
      4.4.5. Denoising by Compression
    4.5. Pseudo Triggering
    4.6. Ablation Studies
      4.6.1. Impact of the Joint Optimization Process
      4.6.2. Impact of the Hyperparameters X and and Y
  ```

- **Invisible Backdoor Attack against 3D Point Cloud Classifier in Graph Spectral Domain.** *AAAI, 2024.*

  ```
  4. Experiments
    4.1. Experiments Setting（实验设置）
      4.1.1. Datasets and victim 3D DNNs（Victim受害者模型）
      4.1.2. Baseline 3D Backdoor Attacks
    4.2. Attack Experiments（攻击实验）
      4.2.1. Attack Effectiveness
      4.2.2. Attack Stealthiness
      4.2.3. Human Inspection
      4.2.4. All-to-all Attack
    4.3. Defense Experiments（防御实验）
      4.3.1. Resistance to STRIP
      4.3.2. Resistance to Saliency-based Defense
      4.3.3. Resistance to Data Augmentation
      4.3.4. Resistance to SOR
      4.3.5. Resistance to SSD
    4.4. Ablation Experiments（消融实验）
      4.4.1. Poison Rate X and Target Class Y
      4.4.2. Necessity for Implanting Backdoor Trigger in Graph
      4.4.3. Spectral Domain
  ```

- **Personalization as a Shortcut for Few-Shot Backdoor Attack against Text-to-Image Diffusion Models.** *AAAI, 2024.*

  ```
  4. Experiments
    4.1. Experimental Setup
      4.1. Target model（指：攻击的模型）
      4.2. Evaluation metric
      4.3. Implementation details
    4.2. Empirical Study of Identifier
    4.3. Evaluation Effectiveness of Backdoor
    4.4. Evaluation Integrity of Backdoor
  ```

- **Temporal-Distributed Backdoor Attack against Video Based Action Recognition.** *AAAI, 2024.*

  ```
  4. Experiments
    4.1. Experimental Setup
    4.2. Attack Effectiveness（攻击有效性）
    4.3. Resistance to Backdoor Defenses
    4.4. Resistance to Human Observers
    4.5. Collateral Damage
    4.6. Case Study: ASR v.s. Influential Factors
      4.6.1. Poisoning Ratio
      4.6.2. Frequency
      4.6.3. Number of perturbed components
      4.6.4. Perturbation magnitude
  ```

  
