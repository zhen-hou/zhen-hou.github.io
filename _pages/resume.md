---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
published: false
---

{% include base_path %}

I am a Ph.D. student in Statistics at the Hong Kong University of Science and Technology (HKUST). My work focuses on statistical inference under distribution shift, kernel methods, uncertainty quantification, and model reliability. I also build reproducible experiments to study large language model architectures, post-training, and evaluation.

## Education

**Hong Kong University of Science and Technology** — Ph.D. student in Statistics<br>
2023–present · Advisor: Prof. Dong Xia

Research areas: statistical inference under covariate shift, RKHS-based nonparametric regression, kernel methods, and bootstrap methods, with a focus on finite-sample error and out-of-sample reliability.

**Nankai University** — Bachelor's degree in Mathematics<br>
2019–2023 · Shiing-Shen Chern Class, Tianjin, China

Overall GPA: 3.87/4.00 (rank: 2/26); major GPA: 3.90/4.00 (rank: 2/26).

## Research and Projects

### Statistical Inference under Distribution Shift

HKUST · Advisor: Prof. Dong Xia · 2023–present

- Study nonparametric estimation and inference when the training and target distributions differ, including the effects of covariate shift on estimation error, confidence sets, and out-of-sample reliability.
- Analyze estimation accuracy and generalization error for distributed computation under distribution shift, and establish finite-sample and nonasymptotic error bounds.
- Develop bootstrap-based inference for kernel methods under covariate shift to quantify uncertainty in model reliability assessments.

See [Publications]({{ base_path }}/publications/) for current papers and preprints.

### Large Language Model Reproducibility Project

Architecture efficiency, post-training, evaluation, and training systems

- Build reproducible PyTorch experiments with scripts, unit tests, numerical results, plots, and reports, using synthetic or local data.
- Implement causal MHA/MQA/GQA, analyze KV-cache memory, and study RoPE scaling and a Mini-MoE Transformer, including expert utilization, routing entropy, and capacity trade-offs.
- Implement a tiny decoder-only language model and character-level tokenizer; reproduce response-only SFT, DPO, and toy GRPO-style optimization on synthetic statistical and causal reasoning tasks.
- Build a local evaluation framework inspired by OpenCompass, covering reasoning, long-context retrieval, JSON format adherence, refusal behavior, unsupported assertions, bootstrap confidence intervals, and judge agreement.
- Develop a formula-based memory simulator for DDP, FSDP/ZeRO, tensor/pipeline/sequence parallelism, MoE expert parallelism, activation checkpointing, mixed precision, optimizer states, and KV-cache.

### ULA Step-size Selection and Convergence Analysis

HKUST · Advisor: Prof. Tong Zhang · July–August 2022

- Study convergence of the unadjusted Langevin algorithm (ULA), including the relationship between step size, discretization error, convergence rate, and stability.
- Derive conditions for optimal step-size selection in a Gaussian setting and investigate sensitivity of sampling error to hyperparameters.
- Implement simulations to compare numerical error curves with theoretical predictions.

### LSTM-based Clinical Time-series Prediction

Beijing Computational Science Research Center · Advisor: Prof. Qi Wang · July–August 2021

- Contribute to data cleaning, sequence construction, LSTM training, and evaluation for predicting the dynamics of Fspn, Ftot, and VTe in patients with sepsis.
- Analyze prediction lag and model sensitivity in clinical time-series tasks.
- Recognized as an outstanding intern (top 20%).

## Skills

- **Statistical methods:** nonasymptotic generalization analysis, uncertainty quantification, statistical inference, kernel methods, bootstrap, Bayesian posterior sampling, and hyperparameter sensitivity analysis.
- **LLM experiments:** Transformer architectures, sparse MoE routing, SFT, DPO, toy GRPO-style optimization, and local evaluation; familiarity with distributed training concepts and memory analysis.
- **Programming:** Python, PyTorch, NumPy, pandas, R, and C++.
- **Mathematics:** probability, linear algebra, functional analysis, stochastic processes, convex optimization, and stochastic optimization.

## Teaching

Teaching assistant at HKUST:

- **MATH 2411 — Applied Statistics:** Spring 2024–2026.
- **MATH 3033 — Real Analysis:** Fall 2024–2025.

## Honors and Awards

- HKUST RedBird Ph.D. Award, 2023.
- Nankai University Gongneng Scholarship (top 5%), 2020 and 2021.
- Nankai University Zhide Scholarship, 2020.
- First Prize, National College Student Mathematics Competition, Category A, 2020.
