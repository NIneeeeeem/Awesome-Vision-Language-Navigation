# 🛡️ Safety Navigation Survey

<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/Back-Main%20README-1F6FEB?logo=github&logoColor=white" alt="Back to README"></a>
  <a href="bib/awesome_vln.bib"><img src="https://img.shields.io/badge/All%20Bib-8B5E3C?logo=bookstack&logoColor=white" alt="All bib"></a>
  <a href="README.md#-understanding-the-error"><img src="https://img.shields.io/badge/Core%20Repo%20Track-Error-C2410C?logo=shield&logoColor=white" alt="Error section"></a>
</p>

This page reorganizes the repository's **safety-related navigation literature** into a dedicated survey view.

The main emphasis is still:
- `human-robot safety in shared spaces`,
- `socially compliant / human-aware navigation`,
- `crowd interaction, comfort, and preference-aware behavior`.

At the same time, the page now also includes:
- `attack-related papers`,
- `robustness and recovery papers`,
- `uncertainty, deviation, and collision-avoidance papers`

because these are also part of the broader safety story for embodied navigation.

## Scope
| Primary Focus | Also Included |
|------|------|
| social navigation | adversarial attacks |
| human-aware motion | robustness and recovery |
| crowd-aware safety | uncertainty-aware navigation |
| preference and dialogue | failure diagnosis and correction |
| socially compliant deployment | safe continuous control |

## Reading Order
1. Start with the surveys and benchmarks to understand the task boundaries.
2. Then read the human-aware and socially compliant methods.
3. Finish with broader safety, robustness, and attack papers to cover the full safety landscape.

## Recent Check
- Re-checked on `2026-04-15` against the latest safety-related papers already merged into `README.md`, with a targeted pass over recent `VLN`, `AVLN`, and embodied-navigation entries.
- This pass adds two recent missing papers to this themed page: [AURA: Multimodal Shared Autonomy for Real-World Urban Navigation](https://arxiv.org/abs/2604.01659) (`2026-04-02`) and [OnFly: Onboard Zero-Shot Aerial Vision-Language Navigation toward Safety and Efficiency](https://arxiv.org/abs/2603.10682) (`2026-03-11`).
- It also backfills [Safety of Embodied Navigation: A Survey](https://arxiv.org/abs/2508.05855) because it directly frames attacks, robustness, and evaluation concerns for safe embodied navigation.
- [DyGeoVLN: Infusing Dynamic Geometry Foundation Model into Vision-Language Navigation](https://arxiv.org/abs/2603.21269), published on `2026-03-22`, is still treated as adjacent robustness work rather than a direct safety or social-navigation paper, so it remains outside this themed page.

## 1. Surveys and Benchmarks
*Best starting point for a related-work section on safety, social navigation, or human-aware embodied navigation.*

| Date | Paper Title | Main README Category | Venue | Resources |
|------|-------------|----------------------|-------|-----------|
| 2025-12-28 | [MUSON: A Reasoning-oriented Multimodal Dataset for Socially Compliant Navigation in Urban Environments](https://arxiv.org/abs/2512.22867) | Foundation & Benchmark | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_22867.bib) |
| 2025-12-10 | [LISN: Language-Instructed Social Navigation with VLM-based Controller Modulating](https://arxiv.org/abs/2512.09920) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_09920.bib) |
| 2025-09-10 | [SocialNav-SUB: Benchmarking VLMs for Scene Understanding in Social Robot Navigation](https://arxiv.org/abs/2509.08757) | Foundation & Benchmark | CoRL2025 | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/michaelmunje/SocialNavSUB) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2509_08757.bib) |
| 2025-08-07 | [Safety of Embodied Navigation: A Survey](https://arxiv.org/abs/2508.05855) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2508_05855.bib) |
| 2025-03-18 | [HA-VLN 2.0: An Open Benchmark and Leaderboard for Human-Aware Navigation in Discrete and Continuous Environments with Dynamic Multi-Human Interactions](https://arxiv.org/abs/2503.14229) | Foundation & Benchmark | - | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/F1y1113/HA-VLN) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_14229.bib) |
| 2024-06-04 | [CoNav: A Benchmark for Human-Centered Collaborative Navigation](https://arxiv.org/abs/2406.02425) | Foundation & Benchmark | - | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/Li-ChangHao/CoNav_Supplementary) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2406_02425.bib) |
| 2023-11-12 | [A Survey on Socially Aware Robot Navigation: Taxonomy and Future Challenges](https://arxiv.org/abs/2311.06922) | Foundation & Benchmark | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2311_06922.bib) |
| 2023-06-20 | [HabiCrowd: A High Performance Simulator for Crowd-Aware Visual Navigation](https://arxiv.org/abs/2306.11377) | Foundation & Benchmark | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2306_11377.bib) |
| 2023-04-12 | [NaviSTAR: Socially Aware Robot Navigation with Hybrid Spatio-Temporal Graph Transformer and Preference Learning](https://arxiv.org/abs/2304.05979) | Foundation & Benchmark | IROS2023 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2304_05979.bib) |
| 2021-06-22 | [A Survey on Human-aware Robot Navigation](https://arxiv.org/abs/2106.11650) | Foundation & Benchmark | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2106_11650.bib) |

## 2. Human-Aware and Socially Compliant Methods
*Papers directly about safe behavior around people, crowds, and human social expectations.*

| Date | Paper Title | Main README Category | Venue | Resources |
|------|-------------|----------------------|-------|-----------|
| 2026-03-24 | [Enhanced Dynamic Window Approach for Socially Compliant Robot Navigation](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2026.1769678/full) | Understanding the Reality | Frontiers in Robotics and AI 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/doi_10_3389_frobt_2026_1769678.bib) |
| 2026-03-21 | [E-SocialNav: Efficient Socially Compliant Navigation with Language Models](https://arxiv.org/abs/2603.20664) | Understanding the Reality | ICASSP2026 | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/Dr-LingXiao/ESocialNav) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_20664.bib) |
| 2026-03-18 | [Interpreting Context-Aware Human Preferences for Multi-Objective Robot Navigation](https://arxiv.org/abs/2603.17510) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_17510.bib) |
| 2026-03-16 | [NavThinker: Action-Conditioned World Models for Coupled Prediction and Planning in Social Navigation](https://arxiv.org/abs/2603.15359) | Understanding the Decision | - | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/hutslib/NavThinker) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_15359.bib) |
| 2026-03-12 | [Enhancing Lightweight Vision Language Models through Group Competitive Learning for Socially Compliant Navigation](https://arxiv.org/abs/2603.11447) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_11447.bib) |
| 2026-03-12 | [Autonomous robots with socially-aware navigation using memory-assisted deep reinforcement learning](https://www.nature.com/articles/s41598-026-42026-9) | Understanding the Reality | Scientific Reports 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/doi_10_1038_s41598_026_42026_9.bib) |
| 2026-03-11 | [A Causal Approach to Predicting and Improving Human Perceptions of Social Navigation Robots](https://arxiv.org/abs/2603.11290) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_11290.bib) |
| 2026-03-05 | [A General Social Cost Layer for Robotic Navigation Planning](https://link.springer.com/article/10.1007/s12369-026-01384-0) | Understanding the Reality | International Journal of Social Robotics 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/doi_10_1007_s12369_026_01384_0.bib) |
| 2026-03-02 | [CHOP: Counterfactual Human Preference Labels Improve Obstacle Avoidance in Visuomotor Navigation Policies](https://arxiv.org/abs/2603.02004) | Understanding the Error | - | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/gershom96/CHOP) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_02004.bib) |
| 2026-03-01 | [DHRN: A robot autonomous navigation method in crowds based on heterogeneous framework](https://www.sciencedirect.com/science/article/pii/S0925231225030474) | Understanding the Reality | Neurocomputing 2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/doi_10_1016_j_neucom_2025_132375.bib) |
| 2026-02-28 | [Optimal-Horizon Social Robot Navigation in Heterogeneous Crowds](https://arxiv.org/abs/2603.00507) | Understanding the Decision | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_00507.bib) |
| 2026-02-11 | [Safe mobility support system using crowd mapping and avoidance route planning using VLM](https://arxiv.org/abs/2602.10910) | Understanding the Error | RCAR2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_10910.bib) |
| 2025-12-10 | [LISN: Language-Instructed Social Navigation with VLM-based Controller Modulating](https://arxiv.org/abs/2512.09920) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2512_09920.bib) |
| 2025-11-26 | [SocialNav: Training Human-Inspired Foundation Model for Socially-Aware Embodied Navigation](https://arxiv.org/abs/2511.21135) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2511_21135.bib) |
| 2025-11-15 | [SocialNav-Map: Dynamic Mapping with Human Trajectory Prediction for Zero-Shot Social Navigation](https://arxiv.org/abs/2511.12232) | Understanding the Reality | - | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/linglingxiansen/SocialNav-Map) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2511_12232.bib) |
| 2025-10-27 | [Deductive Chain-of-Thought Augmented Socially-aware Robot Navigation World Model](https://arxiv.org/abs/2510.23509) | Understanding the Future | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2510_23509.bib) |
| 2025-06-04 | [LaF-GRPO: In-Situ Navigation Instruction Generation for the Visually Impaired via GRPO with LLM-as-Follower Reward](https://arxiv.org/abs/2506.04070) | Understanding the Reality | AAAI2026 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2506_04070.bib) |
| 2025-03-26 | [Perspective-Shifted Neuro-Symbolic World Models: A Framework for Socially-Aware Robot Navigation](https://arxiv.org/abs/2503.20425) | Understanding the Future | RO-MAN2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_20425.bib) |
| 2025-03-12 | [ViLAM: Distilling Vision-Language Reasoning into Attention Maps for Social Robot Navigation](https://arxiv.org/abs/2503.09820) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_09820.bib) |
| 2025-03-04 | [LLM-Glasses: GenAI-driven Glasses with Haptic Feedback for Navigation of Visually Impaired People](https://arxiv.org/abs/2503.16475) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2503_16475.bib) |
| 2024-09-26 | [GSON: A Group-based Social Navigation Framework with Large Multimodal Model](https://arxiv.org/abs/2409.18084) | Understanding the Reality | RA-L2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2409_18084.bib) |
| 2024-09-20 | [OLiVia-Nav: An Online Lifelong Vision Language Approach for Mobile Robot Social Navigation](https://arxiv.org/abs/2409.13675) | Understanding the History | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2409_13675.bib) |
| 2024-09-08 | [Socially-Aware Robot Navigation Enhanced by Bidirectional Natural Language Conversations Using Large Language Models](https://arxiv.org/abs/2409.04965) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2409_04965.bib) |
| 2024-06-27 | [Human-Aware Vision-and-Language Navigation: Bridging Simulation to Reality with Dynamic Human Interactions](https://arxiv.org/abs/2406.19236) | Understanding the Reality | NeurIPS2024 | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/lpercc/HA3D_simulator) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2406_19236.bib) |
| 2024-04-08 | [MeSA-DRL: Memory-Enhanced Deep Reinforcement Learning for Advanced Socially Aware Robot Navigation in Crowded Environments](https://arxiv.org/abs/2404.05203) | Understanding the History | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2404_05203.bib) |
| 2024-03-30 | [VLM-Social-Nav: Socially Aware Robot Navigation through Scoring using Vision-Language Models](https://arxiv.org/abs/2404.00210) | Understanding the Reality | RA-L2024 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2404_00210.bib) |
| 2024-03-22 | [Unifying Large Language Model and Deep Reinforcement Learning for Human-in-Loop Interactive Socially-aware Navigation](https://arxiv.org/abs/2403.15648) | Understanding the Decision | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2403_15648.bib) |
| 2023-11-06 | [Safe-VLN: Collision Avoidance for Vision-and-Language Navigation of Autonomous Robots Operating in Continuous Environments](https://arxiv.org/abs/2311.02817) | Understanding the Error | RA-L2024 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2311_02817.bib) |
| 2022-01-03 | [Feedback-efficient Active Preference Learning for Socially Aware Robot Navigation](https://arxiv.org/abs/2201.00469) | Understanding the Decision | IROS2022 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2201_00469.bib) |

## 3. Broader Safety, Robustness, and Attacks
*These papers are not all social-navigation papers, but they are important for a complete safety reading path.*

| Date | Paper Title | Main README Category | Venue | Resources |
|------|-------------|----------------------|-------|-----------|
| 2026-04-02 | [AURA: Multimodal Shared Autonomy for Real-World Urban Navigation](https://arxiv.org/abs/2604.01659) | Understanding the Reality | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2604_01659.bib) |
| 2026-03-16 | [Trajectory-Diversity-Driven Robust Vision-and-Language Navigation](https://arxiv.org/abs/2603.15370) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_15370.bib) |
| 2026-03-13 | [HaltNav: Reactive Visual Halting over Lightweight Topological Priors for Robust Vision-Language Navigation](https://arxiv.org/abs/2603.12696) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_12696.bib) |
| 2026-03-11 | [OnFly: Onboard Zero-Shot Aerial Vision-Language Navigation toward Safety and Efficiency](https://arxiv.org/abs/2603.10682) | Understanding the Reality | - | [![Code](https://img.shields.io/badge/Code-181717?logo=github&logoColor=white)](https://github.com/Robotics-STAR-Lab/OnFly) [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2603_10682.bib) |
| 2026-02-06 | [Nipping the Drift in the Bud: Retrospective Rectification for Robust Vision-Language Navigation](https://arxiv.org/abs/2602.06356) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2602_06356.bib) |
| 2025-11-17 | [Shedding Light on VLN Robustness: A Black-box Framework for Indoor Lighting-based Adversarial Attack](https://arxiv.org/abs/2511.13132) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2511_13132.bib) |
| 2025-10-06 | [Efficient Navigation in Unknown Indoor Environments with Vision-Language Models](https://arxiv.org/abs/2510.04991) | Understanding the Error | OWN@IROS2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2510_04991.bib) |
| 2025-09-30 | [AdaNav: Adaptive Reasoning with Uncertainty for Vision-Language Navigation](https://arxiv.org/abs/2509.24387) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2509_24387.bib) |
| 2025-09-08 | [Test-Time Adaptation for Online Vision-Language Navigation with Feedback-Based Reinforcement Learning](https://proceedings.mlr.press/v267/kim25ad.html) | Understanding the Error | ICML2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/2025-test-time-adaptation-for-online-vision-language-navigat.bib) |
| 2025-06-20 | [VLM-Empowered Multi-Mode System for Efficient and Safe Planetary Navigation](https://arxiv.org/abs/2506.16703) | Understanding the Error | IROS2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2506_16703.bib) |
| 2025-01-27 | [Robust Mobile Robot Path Planning via LLM-Based Dynamic Waypoint Generation](https://arxiv.org/abs/2501.15901) | Understanding the Error | ESWA2025 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2501_15901.bib) |
| 2024-07-31 | [Navigating Beyond Instructions: Vision-and-Language Navigation in Obstructed Environments](https://arxiv.org/abs/2407.21452) | Understanding the Error | ACMMM2024 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2407_21452.bib) |
| 2024-03-15 | [Mind the Error! Detection and Localization of Instruction Errors in Vision-and-Language Navigation](https://arxiv.org/abs/2403.10700) | Understanding the Error | IROS2024 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2403_10700.bib) |
| 2024-03-09 | [Towards Deviation-Robust Agent Navigation via Perturbation-Aware Contrastive Learning](https://arxiv.org/abs/2403.05770) | Understanding the Error | TPAMI2023 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2403_05770.bib) |
| 2023-11-22 | [Fast-Slow Test-Time Adaptation for Online Vision-and-Language Navigation](https://arxiv.org/abs/2311.13209) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2311_13209.bib) |
| 2023-11-06 | [Safe-VLN: Collision Avoidance for Vision-and-Language Navigation of Autonomous Robots Operating in Continuous Environments](https://arxiv.org/abs/2311.02817) | Understanding the Error | RA-L2024 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2311_02817.bib) |
| 2022-11-27 | [Navigation as Attackers Wish? Towards Building Robust Embodied Agents under Federated Learning](https://arxiv.org/abs/2211.14769) | Understanding the Error | - | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2211_14769.bib) |
| 2022-06-12 | [Consistent Attack: Universal Adversarial Perturbation on Embodied Vision Navigation](https://arxiv.org/abs/2206.05751) | Understanding the Error | PRL2023 | [![Bib](https://img.shields.io/badge/Bib-8B5E3C?logo=bookstack&logoColor=white)](bib/entries/arxiv_2206_05751.bib) |

## Notes
- `Main README Category` tells you where the paper currently lives in [README.md](README.md).
- Several papers appear to straddle social navigation and broader safety. That overlap is intentional.
- Newly searched social-navigation papers have now been merged into the main repository and no longer live in a separate “external only” list.
