<div align="center">
    <img src="assets/nvwa.png" height="90" alt="Logo">
    <h3 style="font-size: 50pt;" align=center><strong>Nüwa</strong></h2>
  </a>
</div>

<div align=center>
<h2 style="font-size: 50pt;" align=center><strong>Towards Large Language Model to Be a Traditional Chinese Medicine Doctor</strong></h2>
</div>

### 📖 Introduction
we introduce Nüwa, a comprehensive Traditional Chinese Medicine LLM that encompasses the entire training pipeline from Continuous Pre-training and Supervised Instruction Fine-tuning to Reinforcement Learning from AI Feedback. Nuwa outperforms other open-source Chinese medical LLMs within TCM domain, thanks in part to our construction of a large-scale TCM training corpus and TCM dialogue dataset.

<div align="center">
<img src="assets/flowchart.png" width="100%" height="100%">
</div>

### 🔥 News and Updates

✅ [2024/08/15] Nüwa starts releasing dataset, code, etc.

✅ [2024/08/01] Nüwa TCM repo is created.

### 📚 Data

- `data/pretrain`: Contains part of TCM corpus for continuous pre-training the model.

- `data/finetune`: Contains part of TCM-QR for supervised instruction fine-tuning the model.

- `data/reward`: Contains samples for training the reward model.

### ⭐ Code Structure
Training Stage:

| Stage                            |  Python script                                                                                                           | Shell script                                                                        |                      
|:--------------------------------|:------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------|
| Stage 1: Continue Pre-training   |  pretraining.py                     | run_pt.sh   | 
| Stage 2: Supervised Instruction Fine-tuning | supervised_finetuning.py            | run_sft.sh  | 
| Stage 3: Reward Modeling        | reward_modeling.py                  | run_rm.sh   | 
| Stage 4: Reinforcement Learning |  rl_training.py                      | run_rl.sh| 


### ⚙️ Getting Started

### 🐌 Quick Start





