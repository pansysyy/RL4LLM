# RL4LLM: A Technical Trajectory from Alignment to Reasoning

<p align="center">
  <strong><a href="https://github.com/pansysyy/RL4LLM/blob/main/view.pdf">➡️ Click Here to Read the Full Survey (PDF) ⬅️</a></strong>
</p>

<p align="center">
  <strong><a href="https://huggingface.co/spaces/pansysy/my-technical-blog/blob/main/RL4LLM.md">➡️ Click Here to Read the blog (preview of markdown) ⬅️</a></strong>
</p>

This repository contains our comprehensive technical survey on the evolution of Reinforcement Learning for Large Language Models (RL4LLM). This work provides a first-principles review of the key technical trajectory from PPO to DPO, IPO, and GRPO.

---

## Abstract

Reinforcement Learning from Human Feedback (RLHF), particularly since the application of the Proximal Policy Optimization (PPO) algorithm, has become a core paradigm for enhancing the capabilities of Large Language Models (LLMs). However, the classic RLHF pipeline, exemplified by PPO, relies on complex online sampling and multiple separate models, leading to high training costs and process instability. To address these issues, Direct Preference Optimization (DPO) and its variants, such as Identity Preference Optimization (IPO), have been proposed. Through an elegant mathematical transformation, they convert the complex reinforcement learning problem into an efficient, supervised-like loss function, thereby bypassing the explicit modeling of a reward model. Furthermore, to tackle the challenges of reasoning-intensive tasks, Group Relative Policy Optimization (GRPO) was introduced, exploring an alternative Reinforcement Learning for LLM (RL4LLM) path by replacing the value model with intra-group reward normalization. Although these methods are continuously evolving, their theoretical underpinnings are deeply intertwined. This paper provides a systematic, first-principles review of this key technical trajectory from PPO to DPO and GRPO. We deeply analyze the core motivations and optimization objectives of each algorithm, complete with detailed mathematical derivations, offering a clear and insightful analytical perspective for understanding and applying state-of-the-art LLM alignment techniques.

---

## Key Contributions

*   **In-depth Analysis of PPO**: A detailed breakdown of the PPO algorithm within the RLHF context, from its high-level methodology to implementation details.
*   **From RLHF to DPO/IPO**: A rigorous, step-by-step mathematical derivation showing how DPO reframes the RL problem and how IPO addresses its limitations.
*   **Introduction to GRPO**: A clear explanation of the motivation and mechanics behind GRPO, a novel approach for reasoning-intensive tasks.
*   **Unified Perspective**: A structured comparison of these core paradigms and a discussion of open research questions in the field of RL4LLM.

## Citation

If you find this survey useful in your research, we would appreciate a citation. You can use the following BibTeX entry:

```bibtex
@misc{wang2024rl4llm,
  author       = {Haiquan Wang},
  title        = {{RL4LLM: A Technical Trajectory from Alignment to Reasoning}},
  year         = {2025},
  howpublished = {\url{https://github.com/pansysyy/RL4LLM/blob/main/view.pdf}},
  note         = {Accessed: 2025-08-20}
}
```

# Feedback and Contact
We welcome any feedback or questions! Please feel free to open an issue in this repository or contact the author at wanghaiquan693@gmail.com.
