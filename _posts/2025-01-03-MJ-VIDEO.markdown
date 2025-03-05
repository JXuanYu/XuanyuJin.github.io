---
layout: post
title:  "MJ-Video: Fine-Grained Benchmarking and Rewarding Video Preferences in Video Generation"
date:   2025-01-03 18:56:33 +00:00
image: /images/MJ-bench.png
categories: research
authors: "Haibo Tong, Zhaoyang Wang, Zhaorun Chen, <strong>Haonian Ji</strong>, Shi Qiu, Siwei Han, Kexin Geng, Zhongkai Xue, Yiyang Zhou, Peng Xia, Mingyu Ding, Rafael Rafailov, Chelsea Finn, Huaxiu Yao"
venue: "arXiv"
arxiv: https://arxiv.org/abs/2502.01719
code: https://github.com/aiming-lab/MJ-Video
website: https://aiming-lab.github.io/MJ-VIDEO.github.io/
---
Recent advancements in video generation have significantly improved the ability to synthesize videos from text instructions. However, existing models still struggle with key challenges such as instruction misalignment, content hallucination, safety concerns, and bias. Addressing these limitations, we introduce MJ-BENCH-VIDEO, a large-scale video preference benchmark designed to evaluate video generation across five critical aspects: Alignment, Safety, Fineness, Coherence & Consistency, and Bias & Fairness. This benchmark incorporates 28 fine-grained criteria to provide a comprehensive evaluation of video preference. Building upon this dataset, we propose MJ-VIDEO, a Mixture-of-Experts (MoE)-based video reward model designed to deliver fine-grained reward. MJ-VIDEO can dynamically select relevant experts to accurately judge the preference based on the input text-video pair. This architecture enables more precise and adaptable preference judgments. Through extensive benchmarking on MJ-BENCH-VIDEO, we analyze the limitations of existing video reward models and demonstrate the superior performance of MJ-VIDEO in video preference assessment, achieving 17.58% and 15.87% improvements in overall and fine-grained preference judgments, respectively. Additionally, introducing MJ-VIDEO for preference tuning in video generation enhances the alignment performance.
