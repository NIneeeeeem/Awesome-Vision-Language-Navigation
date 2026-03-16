<div align="center">
    <h1>🧭 Awesome Vision-Language Navigation</h1>
</div>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="MIT License"></a>
    <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome"></a>
</p>

A curated list of **Vision-Language Navigation (VLN)** research papers focusing on LLM/VLM-based approaches. This repository systematically categorizes works into six key directions: **Decision**, **Error**, **Future**, **History**, and **Reality**.

## 📖 News
**[2026/03/16]** Initial release with 315 papers!

## 🌟 Overview
- [📖 News](#-news)
- [🌟 Overview](#-overview)
- [🤝 Contributing](#-contributing)
- [📚 Foundation & Benchmark](#-foundation--benchmark)
- [🎯 Understanding the Decision](#-understanding-the-decision)
- [⚠️ Understanding the Error](#-understanding-the-error)
- [🔮 Understanding the Future](#-understanding-the-future)
- [💾 Understanding the History](#-understanding-the-history)
- [🤖 Understanding the Reality](#-understanding-the-reality)

## 🤝 Contributing
We warmly welcome contributions via **pull request**. Please follow the instruction in **CONTRIBUTING.md**.

---

## 📚 Foundation & Benchmark
*Datasets, benchmarks, surveys, and early works (before 2022)*

| Date | Paper Title | Code |
|------|-------------|------|
| 2026-02-27 | [EmCoop: A Framework and Benchmark for Embodied Cooperation Among LLM Agents](https://arxiv.org/abs/2603.00349) | - |
| 2025-04-20 | [A Framework for Benchmarking and Aligning Task-Planning Safety in LLM-Based Embodied Agents](https://arxiv.org/abs/2504.14650) | - |
| 2024-12-17 | [SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents](https://arxiv.org/abs/2412.13178) | [GitHub](https://github.com/shengyin1224/SafeAgentBench) |
| 2024-10-09 | [Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology](https://arxiv.org/abs/2410.07087) | - |
| 2024-06-04 | [CoNav: A Benchmark for Human-Centered Collaborative Navigation](https://arxiv.org/abs/2406.02425) | [GitHub](https://github.com/Li-ChangHao/CoNav_Supplementary) |
| 2024-02-22 | [Vision-Language Navigation with Embodied Intelligence: A Survey](https://arxiv.org/abs/2402.14304) | - |
| 2023-11-01 | [Advances in Embodied Navigation Using Large Language Models: A Survey](https://arxiv.org/abs/2311.00530) | - |
| 2022-03-20 | [CoWs on Pasture: Baselines and Benchmarks for Language-Driven Zero-Shot Object Navigation](https://arxiv.org/abs/2203.10421) | [GitHub](https://github.com/real-stanford/cow) |
| 2022-02-04 | [A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility](https://arxiv.org/abs/2202.02312) | - |
| 2021-11-18 | [Simple but Effective: CLIP Embeddings for Embodied AI](https://arxiv.org/abs/2111.09888) | - |
| 2021-11-14 | [Curriculum Learning for Vision-and-Language Navigation](https://arxiv.org/abs/2111.07228) | - |
| 2021-10-27 | [SOAT: A Scene- and Object-Aware Transformer for Vision-and-Language Navigation](https://arxiv.org/abs/2110.14143) | - |
| 2021-10-12 | [Rethinking the Spatial Route Prior in Vision-and-Language Navigation](https://arxiv.org/abs/2110.05728) | - |
| 2021-09-16 | [ROS-X-Habitat: Bridging the ROS Ecosystem with Embodied AI](https://arxiv.org/abs/2109.07703) | [GitHub](https://github.com/facebookresearch/habitat-lab) |
| 2021-08-26 | [Vision-Language Navigation: A Survey and Taxonomy](https://arxiv.org/abs/2108.11544) | - |
| 2021-08-10 | [Embodied BERT: A Transformer Model for Embodied, Language-guided Visual Task Completion](https://arxiv.org/abs/2108.04927) | - |
| 2021-08-05 | [Communicative Learning with Natural Gestures for Embodied Navigation Agents with Human-in-the-Scene](https://arxiv.org/abs/2108.02846) | - |
| 2021-07-15 | [Neighbor-view Enhanced Model for Vision and Language Navigation](https://arxiv.org/abs/2107.07201) | - |
| 2021-07-13 | [How Much Can CLIP Benefit Vision-and-Language Tasks?](https://arxiv.org/abs/2107.06383) | - |
| 2021-06-22 | [A Survey on Human-aware Robot Navigation](https://arxiv.org/abs/2106.11650) | - |
| 2021-05-25 | [VISITRON: Visual Semantics-Aligned Interactively Trained Object-Navigator](https://arxiv.org/abs/2105.11589) | - |
| 2021-05-13 | [Episodic Transformer for Vision-and-Language Navigation](https://arxiv.org/abs/2105.06453) | - |
| 2021-04-28 | [Pushing it out of the Way: Interactive Visual Navigation](https://arxiv.org/abs/2104.14040) | - |
| 2021-04-09 | [The Road to Know-Where: An Object-and-Room Informed Sequential BERT for Indoor Vision-Language Navigation](https://arxiv.org/abs/2104.04167) | - |
| 2021-03-30 | [Diagnosing Vision-and-Language Navigation: What Really Matters](https://arxiv.org/abs/2103.16561) | - |
| 2021-03-30 | [Visual Room Rearrangement](https://arxiv.org/abs/2103.16544) | - |
| 2021-03-01 | [CrossMap Transformer: A Crossmodal Masked Path Transformer Using Double Back-Translation for Vision-and-Language Navigation](https://arxiv.org/abs/2103.00852) | - |
| 2021-01-19 | [A modular vision language navigation and manipulation framework for long horizon compositional tasks in indoor environment](https://arxiv.org/abs/2101.07891) | - |
| 2020-12-09 | [Topological Planning with Transformers for Vision-and-Language Navigation](https://arxiv.org/abs/2012.05292) | - |
| 2020-11-15 | [ArraMon: A Joint Navigation-Assembly Instruction Interpretation Task in Dynamic Environments](https://arxiv.org/abs/2011.07660) | - |
| 2020-10-15 | [Room-Across-Room: Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding](https://arxiv.org/abs/2010.07954) | - |
| 2020-07-14 | [Explore and Explain: Self-supervised Navigation and Recounting](https://arxiv.org/abs/2007.07268) | - |
| 2020-07-01 | [Multimodal Text Style Transfer for Outdoor Vision-and-Language Navigation](https://arxiv.org/abs/2007.00229) | - |
| 2020-06-01 | [Translating Natural Language Instructions for Behavioral Robot Navigation with a Multi-Head Attention Mechanism](https://arxiv.org/abs/2006.00697) | - |
| 2020-05-06 | [Diagnosing the Environment Bias in Vision-and-Language Navigation](https://arxiv.org/abs/2005.03086) | - |
| 2020-04-30 | [Improving Vision-and-Language Navigation with Image-Text Pairs from the Web](https://arxiv.org/abs/2004.14973) | - |
| 2020-04-06 | [Sub-Instruction Aware Vision-and-Language Navigation](https://arxiv.org/abs/2004.02707) | - |
| 2019-12-06 | [VALAN: Vision and Language Agent Navigation](https://arxiv.org/abs/1912.03241) | - |
| 2019-11-27 | [Multimodal Attention Networks for Low-Level Vision-and-Language Navigation](https://arxiv.org/abs/1911.12377) | - |
| 2019-11-18 | [Vision-Language Navigation with Self-Supervised Auxiliary Reasoning Tasks](https://arxiv.org/abs/1911.07883) | - |
| 2019-10-24 | [Cross-Lingual Vision-Language Navigation](https://arxiv.org/abs/1910.11301) | - |
| 2019-08-09 | [Transferable Representation Learning in Vision-and-Language Navigation](https://arxiv.org/abs/1908.03409) | - |
| 2019-05-31 | [Multi-modal Discriminative Model for Vision-and-Language Navigation](https://arxiv.org/abs/1905.13358) | - |
| 2019-05-29 | [Stay on the Path: Instruction Fidelity in Vision-and-Language Navigation](https://arxiv.org/abs/1905.12255) | - |
| 2019-04-02 | [Habitat: A Platform for Embodied AI Research](https://arxiv.org/abs/1904.01201) | [GitHub](https://github.com/facebookresearch/habitat-lab) |
| 2019-01-10 | [Self-Monitoring Navigation Agent via Auxiliary Progress Estimation](https://arxiv.org/abs/1901.03035) | - |
| 2018-08-31 | [Gibson Env: Real-World Perception for Embodied Agents](https://arxiv.org/abs/1808.10654) | [GitHub](https://github.com/StanfordVL/GibsonEnv) |

## 🎯 Understanding the Decision
*Action prediction, decision making, policy learning, and chain-of-thought navigation*

| Date | Paper Title | Code |
|------|-------------|------|
| 2026-03-07 | [VLN-Cache: Enabling Token Caching for VLN Models with Visual/Semantic Dynamics Awareness](https://arxiv.org/abs/2603.07080) | - |
| 2026-02-07 | [LCLA: Language-Conditioned Latent Alignment for Vision-Language Navigation](https://arxiv.org/abs/2602.07629) | - |
| 2025-12-31 | [VLN-MME: Diagnosing MLLMs as Language-guided Visual Navigation agents](https://arxiv.org/abs/2512.24851) | - |
| 2025-12-26 | [LongFly: Long-Horizon UAV Vision-and-Language Navigation with Spatiotemporal Context Integration](https://arxiv.org/abs/2512.22010) | - |
| 2025-12-02 | [SeeNav-Agent: Enhancing Vision-Language Navigation with Visual Prompt and Step-Level Policy Optimization](https://arxiv.org/abs/2512.02631) | - |
| 2025-11-21 | [Progress-Think: Semantic Progress Reasoning for Vision-Language Navigation](https://arxiv.org/abs/2511.17097) | - |
| 2025-09-24 | [Boosting Zero-Shot VLN via Abstract Obstacle Map-Based Waypoint Prediction with TopoGraph-and-VisitInfo-Aware Prompting](https://arxiv.org/abs/2509.20499) | - |
| 2025-09-02 | [Plan Verification for LLM-Based Embodied Task Completion Agents](https://arxiv.org/abs/2509.02761) | - |
| 2025-08-21 | [AeroDuo: Aerial Duo for UAV-based Vision and Language Navigation](https://arxiv.org/abs/2508.15232) | - |
| 2025-06-24 | [Learning Instruction-Following Policies through Open-Ended Instruction Relabeling with Large Language Models](https://arxiv.org/abs/2506.20061) | - |
| 2025-05-27 | [PartInstruct: Part-level Instruction Following for Fine-grained Robot Manipulation](https://arxiv.org/abs/2505.21652) | - |
| 2025-03-14 | [Aerial Vision-and-Language Navigation with Grid-based View Selection and Map Construction](https://arxiv.org/abs/2503.11091) | - |
| 2024-12-16 | [Embodied CoT Distillation From LLM To Off-the-shelf Agents](https://arxiv.org/abs/2412.11499) | - |
| 2024-12-02 | [Collaborative Instance Object Navigation: Leveraging Uncertainty-Awareness to Minimize Human-Agent Dialogues](https://arxiv.org/abs/2412.01250) | - |
| 2024-11-26 | [LLM-Based Offline Learning for Embodied Agents via Consistency-Guided Reward Ensemble](https://arxiv.org/abs/2411.17135) | - |
| 2024-11-12 | [Zero-shot Object-Centric Instruction Following: Integrating Foundation Models with Traditional Navigation](https://arxiv.org/abs/2411.07848) | - |
| 2024-11-08 | [End-to-End Navigation with Vision Language Models: Transforming Spatial Reasoning into Question-Answering](https://arxiv.org/abs/2411.05755) | - |
| 2024-11-07 | [MPVO: Motion-Prior based Visual Odometry for PointGoal Navigation](https://arxiv.org/abs/2411.04796) | - |
| 2024-10-18 | [Vision-Language Navigation with Energy-Based Policy](https://arxiv.org/abs/2410.14250) | - |
| 2024-10-11 | [Exploring Spatial Representation to Enhance LLM Reasoning in Aerial Vision-Language Navigation](https://arxiv.org/abs/2410.08500) | - |
| 2024-10-09 | [Embodied Agent Interface: Benchmarking LLMs for Embodied Decision Making](https://arxiv.org/abs/2410.07166) | - |
| 2024-07-30 | [Autonomous Improvement of Instruction Following Skills via Foundation Models](https://arxiv.org/abs/2407.20635) | - |
| 2024-07-17 | [NavGPT-2: Unleashing Navigational Reasoning Capability for Large Vision-Language Models](https://arxiv.org/abs/2407.12366) | [GitHub](https://github.com/GengzeZhou/NavGPT) |
| 2024-07-10 | [Mobility VLA: Multimodal Instruction Navigation with Long-Context VLMs and Topological Graphs](https://arxiv.org/abs/2407.07775) | - |
| 2024-06-03 | [Augmented Commonsense Knowledge for Remote Object Grounding](https://arxiv.org/abs/2406.01256) | - |
| 2024-04-12 | [TDANet: Target-Directed Attention Network For Object-Goal Visual Navigation With Zero-Shot Ability](https://arxiv.org/abs/2404.08353) | - |
| 2024-02-05 | [VLN-Video: Utilizing Driving Videos for Outdoor Vision-and-Language Navigation](https://arxiv.org/abs/2402.03561) | - |
| 2023-12-14 | [Promptable Behaviors: Personalizing Multi-Objective Rewards from Human Preferences](https://arxiv.org/abs/2312.09337) | - |
| 2023-10-11 | [LangNav: Language as a Perceptual Representation for Navigation](https://arxiv.org/abs/2310.07889) | - |
| 2023-08-09 | [Bird&#039;s-Eye-View Scene Graph for Vision-Language Navigation](https://arxiv.org/abs/2308.04758) | - |
| 2023-05-26 | [NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models](https://arxiv.org/abs/2305.16986) | [GitHub](https://github.com/GengzeZhou/NavGPT) |
| 2023-04-11 | [Improving Vision-and-Language Navigation by Generating Future-View Image Semantics](https://arxiv.org/abs/2304.04907) | - |
| 2023-03-15 | [Lana: A Language-Capable Navigator for Instruction Following and Generation](https://arxiv.org/abs/2303.08409) | - |
| 2022-10-30 | [Towards Versatile Embodied Navigation](https://arxiv.org/abs/2210.16822) | - |
| 2022-03-22 | [HOP: History-and-Order Aware Pre-training for Vision-and-Language Navigation](https://arxiv.org/abs/2203.11591) | - |
| 2021-12-08 | [Contrastive Instruction-Trajectory Learning for Vision-Language Navigation](https://arxiv.org/abs/2112.04138) | - |
| 2021-04-21 | [Hierarchical Cross-Modal Agent for Robotics Vision-and-Language Navigation](https://arxiv.org/abs/2104.10674) | - |
| 2020-11-26 | [A Recurrent Vision-and-Language BERT for Navigation](https://arxiv.org/abs/2011.13922) | - |
| 2020-11-14 | [Few-shot Object Grounding and Mapping for Natural Language Robot Instruction Following](https://arxiv.org/abs/2011.07384) | - |
| 2020-09-16 | [Generative Language-Grounded Policy in Vision-and-Language Navigation with Bayes&#039; Rule](https://arxiv.org/abs/2009.07783) | - |
| 2020-09-07 | [Integrating Egocentric Localization for More Realistic Point-Goal Navigation Agents](https://arxiv.org/abs/2009.03231) | - |
| 2020-07-15 | [Active Visual Information Gathering for Vision-Language Navigation](https://arxiv.org/abs/2007.08037) | - |
| 2020-07-11 | [Evolving Graphical Planner: Contextual Global Planning for Vision-and-Language Navigation](https://arxiv.org/abs/2007.05655) | - |
| 2020-04-29 | [Improving Target-driven Visual Navigation with Attention on 3D Spatial Relationships](https://arxiv.org/abs/2005.02153) | - |
| 2020-03-01 | [Environment-agnostic Multitask Learning for Natural Language Grounded Navigation](https://arxiv.org/abs/2003.00443) | - |
| 2019-11-18 | [Unsupervised Reinforcement Learning of Transferable Meta-Skills for Embodied Navigation](https://arxiv.org/abs/1911.07450) | - |

## ⚠️ Understanding the Error
*Error recovery, safety navigation, collision avoidance, and risk analysis*

| Date | Paper Title | Code |
|------|-------------|------|
| 2026-03-02 | [CHOP: Counterfactual Human Preference Labels Improve Obstacle Avoidance in Visuomotor Navigation Policies](https://arxiv.org/abs/2603.02004) | [GitHub](https://github.com/gershom96/CHOP) |
| 2026-02-11 | [Safe mobility support system using crowd mapping and avoidance route planning using VLM](https://arxiv.org/abs/2602.10910) | - |
| 2026-02-05 | [VLN-Pilot: Large Vision-Language Model as an Autonomous Indoor Drone Operator](https://arxiv.org/abs/2602.05552) | - |
| 2026-01-29 | [DSCD-Nav: Dual-Stance Cooperative Debate for Object Navigation](https://arxiv.org/abs/2601.21409) | - |
| 2025-12-28 | [MUSON: A Reasoning-oriented Multimodal Dataset for Socially Compliant Navigation in Urban Environments](https://arxiv.org/abs/2512.22867) | - |
| 2025-12-10 | [LISN: Language-Instructed Social Navigation with VLM-based Controller Modulating](https://arxiv.org/abs/2512.09920) | - |
| 2025-11-17 | [Is your VLM Sky-Ready? A Comprehensive Spatial Intelligence Benchmark for UAV Navigation](https://arxiv.org/abs/2511.13269) | - |
| 2025-10-06 | [Efficient Navigation in Unknown Indoor Environments with Vision-Language Models](https://arxiv.org/abs/2510.04991) | - |
| 2025-09-30 | [SafeMind: Benchmarking and Mitigating Safety Risks in Embodied LLM Agents](https://arxiv.org/abs/2509.25885) | - |
| 2025-09-22 | [AD-VF: LLM-Automatic Differentiation Enables Fine-Tuning-Free Robot Planning from Formal Methods Feedback](https://arxiv.org/abs/2509.18384) | - |
| 2025-08-15 | [OVSegDT: Segmenting Transformer for Open-Vocabulary Object Goal Navigation](https://arxiv.org/abs/2508.11479) | - |
| 2025-08-07 | [Safety of Embodied Navigation: A Survey](https://arxiv.org/abs/2508.05855) | - |
| 2025-07-07 | [NavigScene: Bridging Local Perception and Global Navigation for Beyond-Visual-Range Autonomous Driving](https://arxiv.org/abs/2507.05227) | - |
| 2025-06-20 | [VLM-Empowered Multi-Mode System for Efficient and Safe Planetary Navigation](https://arxiv.org/abs/2506.16703) | - |
| 2025-02-23 | [Navigation-GPT: A Robust and Adaptive Framework Utilizing Large Language Models for Navigation Applications](https://arxiv.org/abs/2502.16402) | - |
| 2025-01-27 | [Robust Mobile Robot Path Planning via LLM-Based Dynamic Waypoint Generation](https://arxiv.org/abs/2501.15901) | - |
| 2024-05-27 | [Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-based Decision-Making Systems](https://arxiv.org/abs/2405.20774) | - |
| 2024-02-29 | [DOZE: A Dataset for Open-Vocabulary Zero-Shot Object Navigation in Dynamic Environments](https://arxiv.org/abs/2402.19007) | - |
| 2023-11-06 | [Safe-VLN: Collision Avoidance for Vision-and-Language Navigation of Autonomous Robots Operating in Continuous Environments](https://arxiv.org/abs/2311.02817) | - |
| 2023-06-20 | [HabiCrowd: A High Performance Simulator for Crowd-Aware Visual Navigation](https://arxiv.org/abs/2306.11377) | - |
| 2022-11-27 | [Navigation as Attackers Wish? Towards Building Robust Embodied Agents under Federated Learning](https://arxiv.org/abs/2211.14769) | - |
| 2022-06-12 | [Consistent Attack: Universal Adversarial Perturbation on Embodied Vision Navigation](https://arxiv.org/abs/2206.05751) | - |

## 🔮 Understanding the Future
*World models, diffusion models, future prediction, and imagination-based navigation*

| Date | Paper Title | Code |
|------|-------------|------|
| 2026-03-10 | [ImpedanceDiffusion: Diffusion-Based Global Path Planning for UAV Swarm Navigation with Generative Impedance Control](https://arxiv.org/abs/2603.09031) | - |
| 2026-01-30 | [MapDream: Task-Driven Map Learning for Vision-Language Navigation](https://arxiv.org/abs/2602.00222) | - |
| 2026-01-20 | [FantasyVLN: Unified Multimodal Chain-of-Thought Reasoning for Vision-Language Navigation](https://arxiv.org/abs/2601.13976) | - |
| 2025-12-26 | [Aerial World Model for Long-horizon Visual Generation and Navigation in 3D Space](https://arxiv.org/abs/2512.21887) | - |
| 2025-12-02 | [SwarmDiffusion: End-To-End Traversability-Guided Diffusion for Embodiment-Agnostic Navigation of Heterogeneous Robots](https://arxiv.org/abs/2512.02851) | - |
| 2025-12-01 | [NavForesee: A Unified Vision-Language World Model for Hierarchical Planning and Dual-Horizon Navigation Prediction](https://arxiv.org/abs/2512.01550) | - |
| 2025-11-24 | [UNeMo: Collaborative Visual-Language Reasoning and Navigation via a Multimodal World Model](https://arxiv.org/abs/2511.18845) | - |
| 2025-10-27 | [Deductive Chain-of-Thought Augmented Socially-aware Robot Navigation World Model](https://arxiv.org/abs/2510.23509) | - |
| 2025-10-09 | [Unified World Models: Memory-Augmented Planning and Foresight for Visual Navigation](https://arxiv.org/abs/2510.08713) | - |
| 2025-10-09 | [Dream to Recall: Imagination-Guided Experience Retrieval for Memory-Persistent Vision-and-Language Navigation](https://arxiv.org/abs/2510.08553) | - |
| 2025-10-01 | [VENTURA: Adapting Image Diffusion Models for Unified Task Conditioned Navigation](https://arxiv.org/abs/2510.01388) | - |
| 2025-08-13 | [DAgger Diffusion Navigation: DAgger Boosted Diffusion Policy for Vision-Language Navigation](https://arxiv.org/abs/2508.09444) | - |
| 2025-08-09 | [Imaginative World Modeling with Scene Graphs for Embodied Agent Navigation](https://arxiv.org/abs/2508.06990) | - |
| 2025-08-04 | [MonoDream: Monocular Vision-Language Navigation with Panoramic Dreaming](https://arxiv.org/abs/2508.02549) | - |
| 2025-06-30 | [NavMorph: A Self-Evolving World Model for Vision-and-Language Navigation in Continuous Environments](https://arxiv.org/abs/2506.23468) | [GitHub](https://github.com/Feliciaxyao/NavMorph) |
| 2025-05-28 | [Anomalies by Synthesis: Anomaly Detection using Generative Diffusion Models for Off-Road Navigation](https://arxiv.org/abs/2505.22805) | - |
| 2025-05-09 | [VISTA: Generative Visual Imagination for Vision-and-Language Navigation](https://arxiv.org/abs/2505.07868) | - |
| 2025-03-13 | [PanoGen++: Domain-Adapted Text-Guided Panoramic Environment Generation for Vision-and-Language Navigation](https://arxiv.org/abs/2503.09938) | - |
| 2025-03-11 | [KiteRunner: Language-Driven Cooperative Local-Global Navigation Policy with UAV Mapping in Outdoor Environments](https://arxiv.org/abs/2503.08330) | - |
| 2025-03-04 | [WMNav: Integrating Vision-Language Models into World Models for Object Goal Navigation](https://arxiv.org/abs/2503.02247) | - |
| 2025-02-09 | [DexVLA: Vision-Language Model with Plug-In Diffusion Expert for General Robot Control](https://arxiv.org/abs/2502.05855) | - |
| 2024-11-30 | [Planning from Imagination: Episodic Simulation and Episodic Memory for Vision-and-Language Navigation](https://arxiv.org/abs/2412.01857) | - |
| 2024-10-29 | [Diffusion as Reasoning: Enhancing Object Navigation via Diffusion Model Conditioned on LLM-based Object-Room Knowledge](https://arxiv.org/abs/2410.21842) | - |
| 2023-08-14 | [DREAMWALKER: Mental Planning for Continuous Vision-Language Navigation](https://arxiv.org/abs/2308.07498) | - |
| 2023-05-30 | [PanoGen: Text-Conditioned Panoramic Environment Generation for Vision-and-Language Navigation](https://arxiv.org/abs/2305.19195) | - |
| 2021-05-18 | [Pathdreamer: A World Model for Indoor Navigation](https://arxiv.org/abs/2105.08756) | [GitHub](https://github.com/google-research/pathdreamer) |
| 2017-11-20 | [Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments](https://arxiv.org/abs/1711.07280) | - |

## 💾 Understanding the History
*Memory mechanisms, continual learning, experience replay, and lifelong navigation*

| Date | Paper Title | Code |
|------|-------------|------|
| 2026-03-09 | [CMMR-VLN: Vision-and-Language Navigation via Continual Multimodal Memory Retrieval](https://arxiv.org/abs/2603.07997) | - |
| 2026-03-06 | [Lifelong Embodied Navigation Learning](https://arxiv.org/abs/2603.06073) | [GitHub](https://github.com/WangXudongSIA/Uni-Walker) |
| 2026-02-22 | [WildOS: Open-Vocabulary Object Search in the Wild](https://arxiv.org/abs/2602.19308) | [GitHub](https://github.com/nasa-jpl/nebula2-wildos) |
| 2026-02-02 | [LangMap: A Hierarchical Benchmark for Open-Vocabulary Goal Navigation](https://arxiv.org/abs/2602.02220) | [GitHub](https://github.com/bo-miao/LangMap) |
| 2026-01-13 | [VLingNav: Embodied Navigation with Adaptive Reasoning and Visual-Assisted Linguistic Memory](https://arxiv.org/abs/2601.08665) | [GitHub](https://github.com/wsakobe/VLingNav-web) |
| 2025-12-16 | [History-Enhanced Two-Stage Transformer for Aerial Vision-and-Language Navigation](https://arxiv.org/abs/2512.14222) | - |
| 2025-12-11 | [Efficient-VLN: A Training-Efficient Vision-Language Navigation Model](https://arxiv.org/abs/2512.10310) | - |
| 2025-11-30 | [FOM-Nav: Frontier-Object Maps for Object Goal Navigation](https://arxiv.org/abs/2512.01009) | - |
| 2025-11-17 | [PIGEON: VLM-Driven Object Navigation via Points of Interest Selection](https://arxiv.org/abs/2511.13207) | - |
| 2025-11-10 | [PanoNav: Mapless Zero-Shot Object Navigation with Panoramic Scene Parsing and Dynamic Memory](https://arxiv.org/abs/2511.06840) | - |
| 2025-10-21 | [EfficientNav: Towards On-Device Object-Goal Navigation with Navigation Map Caching and Retrieval](https://arxiv.org/abs/2510.18546) | - |
| 2025-10-16 | [SUM-AgriVLN: Spatial Understanding Memory for Agricultural Vision-and-Language Navigation](https://arxiv.org/abs/2510.14357) | - |
| 2025-09-30 | [OmniNav: A Unified Framework for Prospective Exploration and Visual-Language Navigation](https://arxiv.org/abs/2509.25687) | - |
| 2025-09-28 | [RAVEN: Resilient Aerial Navigation via Open-Set Semantic Memory and Behavior Adaptation](https://arxiv.org/abs/2509.23563) | - |
| 2025-08-07 | [MAG-Nav: Language-Driven Object Navigation Leveraging Memory-Reserved Active Grounding](https://arxiv.org/abs/2508.05021) | - |
| 2025-07-17 | [SE-VLN: A Self-Evolving Vision-Language Navigation Framework Based on Multimodal Large Language Models](https://arxiv.org/abs/2507.13152) | - |
| 2025-07-05 | [Are Learning-Based Approaches Ready for Real-World Indoor Navigation? A Case for Imitation Learning](https://arxiv.org/abs/2507.04086) | - |
| 2025-06-20 | [VLN-R1: Vision-Language Navigation via Reinforcement Fine-Tuning](https://arxiv.org/abs/2506.17221) | [GitHub](https://github.com/Qi-Zhangyang/GPT4Scene-and-VLN-R1) |
| 2025-05-28 | [DORAEMON: Decentralized Ontology-aware Reliable Agent with Enhanced Memory Oriented Navigation](https://arxiv.org/abs/2505.21969) | - |
| 2025-05-16 | [Dynam3D: Dynamic Layered 3D Tokens Empower VLM for Vision-and-Language Navigation](https://arxiv.org/abs/2505.11383) | - |
| 2025-05-09 | [ELA-ZSON: Efficient Layout-Aware Zero-Shot Object Navigation Agent with Hierarchical Planning](https://arxiv.org/abs/2505.06131) | - |
| 2025-05-08 | [CityNavAgent: Aerial Vision-and-Language Navigation with Hierarchical Semantic Planning and Global Memory](https://arxiv.org/abs/2505.05622) | - |
| 2025-05-07 | [Replay to Remember (R2R): An Efficient Uncertainty-driven Unsupervised Continual Learning Framework Using Generative Replay](https://arxiv.org/abs/2505.04787) | [GitHub](https://github.com/airsplay/R2R-EnvDrop) |
| 2025-04-03 | [Multimodal Fusion and Vision-Language Models: A Survey for Robot Vision](https://arxiv.org/abs/2504.02477) | - |
| 2025-03-11 | [Reasoning in visual navigation of end-to-end trained agents: a dynamical systems approach](https://arxiv.org/abs/2503.08306) | - |
| 2025-01-29 | [General Scene Adaptation for Vision-and-Language Navigation](https://arxiv.org/abs/2501.17403) | - |
| 2024-12-12 | [Towards Long-Horizon Vision-Language Navigation: Platform, Benchmark and Method](https://arxiv.org/abs/2412.09082) | - |
| 2024-12-09 | [ManiSkill-HAB: A Benchmark for Low-Level Manipulation in Home Rearrangement Tasks](https://arxiv.org/abs/2412.13211) | - |
| 2024-10-05 | [Semantic Environment Atlas for Object-Goal Navigation](https://arxiv.org/abs/2410.09081) | - |
| 2024-09-20 | [ReMEmbR: Building and Reasoning Over Long-Horizon Spatio-Temporal Memory for Robot Navigation](https://arxiv.org/abs/2409.13682) | - |
| 2024-09-20 | [OLiVia-Nav: An Online Lifelong Vision Language Approach for Mobile Robot Social Navigation](https://arxiv.org/abs/2409.13675) | - |
| 2024-09-04 | [Cog-GA: A Large Language Models-based Generative Agent for Vision-Language Navigation in Continuous Environments](https://arxiv.org/abs/2409.02522) | - |
| 2024-08-08 | [Perceive, Reflect, and Plan: Designing LLM Agent for Goal-Directed City Navigation without Instructions](https://arxiv.org/abs/2408.04168) | - |
| 2024-06-05 | [Balancing Performance and Efficiency in Zero-shot Robotic Navigation](https://arxiv.org/abs/2406.03015) | - |
| 2024-06-03 | [Mobile-Agent-v2: Mobile Device Operation Assistant with Effective Navigation via Multi-Agent Collaboration](https://arxiv.org/abs/2406.01014) | - |
| 2024-05-23 | [Skip-SCAR: Hardware-Friendly High-Quality Embodied Visual Navigation](https://arxiv.org/abs/2405.14154) | - |
| 2024-05-17 | [MC-GPT: Empowering Vision-and-Language Navigation with Memory Map and Reasoning Chains](https://arxiv.org/abs/2405.10620) | - |
| 2024-05-11 | [Memory-Maze: Scenario Driven Benchmark and Visual Language Navigation Model for Guiding Blind People](https://arxiv.org/abs/2405.07060) | - |
| 2024-03-22 | [Unifying Large Language Model and Deep Reinforcement Learning for Human-in-Loop Interactive Socially-aware Navigation](https://arxiv.org/abs/2403.15648) | - |
| 2024-03-22 | [Continual Vision-and-Language Navigation](https://arxiv.org/abs/2403.15049) | - |
| 2024-03-21 | [Volumetric Environment Representation for Vision-Language Navigation](https://arxiv.org/abs/2403.14158) | - |
| 2024-03-15 | [Mind the Error! Detection and Localization of Instruction Errors in Vision-and-Language Navigation](https://arxiv.org/abs/2403.10700) | - |
| 2024-03-15 | [Language to Map: Topological map generation from natural language path instructions](https://arxiv.org/abs/2403.10008) | - |
| 2023-07-24 | [GridMM: Grid Memory Map for Vision-and-Language Navigation](https://arxiv.org/abs/2307.12907) | - |
| 2023-05-19 | [PASTS: Progress-Aware Spatio-Temporal Transformer Speaker For Vision-and-Language Navigation](https://arxiv.org/abs/2305.11918) | - |
| 2023-03-02 | [ESceme: Vision-and-Language Navigation with Episodic Scene Memory](https://arxiv.org/abs/2303.01032) | - |
| 2023-01-30 | [Emergence of Maps in the Memories of Blind Navigation Agents](https://arxiv.org/abs/2301.13261) | - |
| 2022-10-11 | [CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory](https://arxiv.org/abs/2210.05663) | - |
| 2022-10-06 | [Iterative Vision-and-Language Navigation](https://arxiv.org/abs/2210.03087) | - |
| 2022-06-23 | [1st Place Solutions for RxR-Habitat Vision-and-Language Navigation Competition (CVPR 2022)](https://arxiv.org/abs/2206.11610) | [GitHub](https://github.com/google-research-datasets/RxR) |
| 2022-03-10 | [Cross-modal Map Learning for Vision and Language Navigation](https://arxiv.org/abs/2203.05137) | - |
| 2021-11-10 | [Multimodal Transformer with Variable-length Memory for Vision-and-Language Navigation](https://arxiv.org/abs/2111.05759) | - |
| 2021-10-25 | [History Aware Multimodal Transformer for Vision-and-Language Navigation](https://arxiv.org/abs/2110.13309) | - |
| 2021-03-05 | [Structured Scene Memory for Vision-Language Navigation](https://arxiv.org/abs/2103.03454) | - |
| 2020-03-15 | [Vision-Dialog Navigation by Exploring Cross-modal Memory](https://arxiv.org/abs/2003.06745) | - |
| 2018-05-24 | [Been There, Done That: Meta-Learning with Episodic Recall](https://arxiv.org/abs/1805.09692) | - |

## 🤖 Understanding the Reality
*Sim-to-real transfer, real-world deployment, and physical robot navigation*

| Date | Paper Title | Code |
|------|-------------|------|
| 2026-03-10 | [Implicit Geometry Representations for Vision-and-Language Navigation from Web Videos](https://arxiv.org/abs/2603.09259) | - |
| 2026-03-09 | [R2F: Repurposing Ray Frontiers for LLM-free Object Navigation](https://arxiv.org/abs/2603.08475) | - |
| 2026-03-07 | [FreeFly-Thinking : Aligning Chain-of-Thought Reasoning with Continuous UAV Navigation](https://arxiv.org/abs/2603.07181) | - |
| 2026-03-05 | [OpenFrontier: General Navigation with Visual-Language Grounded Frontiers](https://arxiv.org/abs/2603.05377) | - |
| 2026-02-23 | [To Move or Not to Move: Constraint-based Planning Enables Zero-Shot Generalization for Interactive Navigation](https://arxiv.org/abs/2602.20055) | - |
| 2026-02-20 | [CapNav: Benchmarking Vision Language Models on Capability-conditioned Indoor Navigation](https://arxiv.org/abs/2602.18424) | - |
| 2026-02-19 | [What Breaks Embodied AI Security:LLM Vulnerabilities, CPS Flaws,or Something Else?](https://arxiv.org/abs/2602.17345) | - |
| 2026-02-13 | [SignScene: Visual Sign Grounding for Mapless Navigation](https://arxiv.org/abs/2602.12686) | - |
| 2026-02-01 | [Sem-NaVAE: Semantically-Guided Outdoor Mapless Navigation via Generative Trajectory Priors](https://arxiv.org/abs/2602.01429) | - |
| 2026-01-29 | [IROS: A Dual-Process Architecture for Real-Time VLM-Based Indoor Navigation](https://arxiv.org/abs/2601.21506) | - |
| 2026-01-19 | [Spatial-VLN: Zero-Shot Vision-and-Language Navigation With Explicit Spatial Perception and Exploration](https://arxiv.org/abs/2601.12766) | - |
| 2026-01-19 | [AirHunt: Bridging VLM Semantics and Continuous Planning for Efficient Aerial Object Navigation](https://arxiv.org/abs/2601.12742) | - |
| 2026-01-07 | [CoINS: Counterfactual Interactive Navigation via Skill-Aware VLM](https://arxiv.org/abs/2601.03956) | - |
| 2025-12-30 | [RANGER: A Monocular Zero-Shot Semantic Navigation Framework through Contextual Adaptation](https://arxiv.org/abs/2512.24212) | - |
| 2025-12-22 | [IndoorUAV: Benchmarking Vision-Language UAV Navigation in Continuous Indoor Environments](https://arxiv.org/abs/2512.19024) | - |
| 2025-12-14 | [D3D-VLP: Dynamic 3D Vision-Language-Planning Model for Embodied Grounding and Navigation](https://arxiv.org/abs/2512.12622) | - |
| 2025-12-13 | [Floorplan2Guide: LLM-Guided Floorplan Parsing for BLV Indoor Navigation](https://arxiv.org/abs/2512.12177) | - |
| 2025-12-08 | [VLD: Visual Language Goal Distance for Reinforcement Learning Navigation](https://arxiv.org/abs/2512.07976) | - |
| 2025-11-26 | [SocialNav: Training Human-Inspired Foundation Model for Socially-Aware Embodied Navigation](https://arxiv.org/abs/2511.21135) | - |
| 2025-11-17 | [Shedding Light on VLN Robustness: A Black-box Framework for Indoor Lighting-based Adversarial Attack](https://arxiv.org/abs/2511.13132) | - |
| 2025-11-02 | [Fast-SmartWay: Panoramic-Free End-to-End Zero-Shot Vision-and-Language Navigation](https://arxiv.org/abs/2511.00933) | - |
| 2025-10-27 | [HyPerNav: Hybrid Perception for Object-Oriented Navigation in Unknown Environment](https://arxiv.org/abs/2510.22917) | - |
| 2025-10-23 | [VAMOS: A Hierarchical Vision-Language-Action Model for Capability-Modulated and Steerable Navigation](https://arxiv.org/abs/2510.20818) | - |
| 2025-10-22 | [LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision Language Navigation in Continuous Environments](https://arxiv.org/abs/2510.19655) | - |
| 2025-10-22 | [ConvXformer: Differentially Private Hybrid ConvNeXt-Transformer for Inertial Navigation](https://arxiv.org/abs/2510.19352) | - |
| 2025-10-18 | [DIV-Nav: Open-Vocabulary Spatial Relationships for Multi-Object Navigation](https://arxiv.org/abs/2510.16518) | - |
| 2025-10-09 | [An LLM-Powered Cooperative Framework for Large-Scale Multi-Vehicle Navigation](https://arxiv.org/abs/2510.07825) | - |
| 2025-09-26 | [See, Point, Fly: A Learning-Free VLM Framework for Universal Unmanned Aerial Navigation](https://arxiv.org/abs/2509.22653) | - |
| 2025-09-25 | [SLAM-Free Visual Navigation with Hierarchical Vision-Language Perception and Coarse-to-Fine Semantic Topological Planning](https://arxiv.org/abs/2509.20739) | - |
| 2025-09-23 | [OmniVLA: An Omni-Modal Vision-Language-Action Model for Robot Navigation](https://arxiv.org/abs/2509.19480) | - |
| 2025-09-23 | [VLN-Zero: Rapid Exploration and Cache-Enabled Neurosymbolic Vision-Language Planning for Zero-Shot Transfer in Robot Navigation](https://arxiv.org/abs/2509.18592) | - |
| 2025-09-19 | [FiLM-Nav: Efficient and Generalizable Navigation via VLM Fine-tuning](https://arxiv.org/abs/2509.16445) | - |
| 2025-09-17 | [FSR-VLN: Fast and Slow Reasoning for Vision-Language Navigation with Hierarchical Multi-modal Scene Graph](https://arxiv.org/abs/2509.13733) | - |
| 2025-09-15 | [Embodied Navigation Foundation Model](https://arxiv.org/abs/2509.12129) | - |
| 2025-09-13 | [Nav-R1: Reasoning and Navigation in Embodied Scenes](https://arxiv.org/abs/2509.10884) | - |
| 2025-09-12 | [GC-VLN: Instruction as Graph Constraints for Training-free Vision-and-Language Navigation](https://arxiv.org/abs/2509.10454) | - |
| 2025-09-10 | [SocialNav-SUB: Benchmarking VLMs for Scene Understanding in Social Robot Navigation](https://arxiv.org/abs/2509.08757) | - |
| 2025-08-14 | [CorrectNav: Self-Correction Flywheel Empowers Vision-Language-Action Navigation Model](https://arxiv.org/abs/2508.10416) | - |
| 2025-08-13 | [GoViG: Goal-Conditioned Visual Navigation Instruction Generation](https://arxiv.org/abs/2508.09547) | - |
| 2025-08-11 | [SwarmVLM: VLM-Guided Impedance Control for Autonomous Navigation of Heterogeneous Robots in Dynamic Warehousing](https://arxiv.org/abs/2508.07814) | - |
| 2025-08-01 | [UAV-ON: A Benchmark for Open-World Object Goal Navigation with Aerial Agents](https://arxiv.org/abs/2508.00288) | - |
| 2025-07-23 | [PIG-Nav: Key Insights for Pretrained Image Goal Navigation Models](https://arxiv.org/abs/2507.17220) | - |
| 2025-07-17 | [osmAG-LLM: Zero-Shot Open-Vocabulary Object Navigation via Semantic Maps and Large Language Models Reasoning](https://arxiv.org/abs/2507.12753) | - |
| 2025-07-09 | [LOVON: Legged Open-Vocabulary Object Navigator](https://arxiv.org/abs/2507.06747) | - |
| 2025-07-07 | [MOSU: Autonomous Long-range Robot Navigation with Multi-modal Scene Understanding](https://arxiv.org/abs/2507.04686) | - |
| 2025-06-12 | [Grounded Vision-Language Navigation for UAVs with Open-Vocabulary Goal Understanding](https://arxiv.org/abs/2506.10756) | - |
| 2025-06-09 | [Hierarchical Scoring with 3D Gaussian Splatting for Instance Image-Goal Navigation](https://arxiv.org/abs/2506.07338) | - |
| 2025-06-07 | [Multimodal Spatial Language Maps for Robot Navigation and Manipulation](https://arxiv.org/abs/2506.06862) | - |
| 2025-06-04 | [LaF-GRPO: In-Situ Navigation Instruction Generation for the Visually Impaired via GRPO with LLM-as-Follower Reward](https://arxiv.org/abs/2506.04070) | - |
| 2025-06-01 | [NavBench: Probing Multimodal Large Language Models for Embodied Navigation](https://arxiv.org/abs/2506.01031) | - |
| 2025-05-27 | [FM-Planner: Foundation Model Guided Path Planning for Autonomous Drone Navigation](https://arxiv.org/abs/2505.20783) | - |
| 2025-05-24 | [SD-OVON: A Semantics-aware Dataset and Benchmark Generation Pipeline for Open-Vocabulary Object Navigation in Dynamic Scenes](https://arxiv.org/abs/2505.18881) | - |
| 2025-05-10 | [STRIVE: Structured Representation Integrating VLM Reasoning for Efficient Object Navigation](https://arxiv.org/abs/2505.06729) | - |
| 2025-04-23 | [Think Hierarchically, Act Dynamically: Hierarchical Multi-modal Fusion and Reasoning for Vision-and-Language Navigation](https://arxiv.org/abs/2504.16516) | - |
| 2025-03-18 | [HA-VLN 2.0: An Open Benchmark and Leaderboard for Human-Aware Navigation in Discrete and Continuous Environments with Dynamic Multi-Human Interactions](https://arxiv.org/abs/2503.14229) | - |
| 2025-03-12 | [Vi-LAD: Vision-Language Attention Distillation for Socially-Aware Robot Navigation in Dynamic Environments](https://arxiv.org/abs/2503.09820) | - |
| 2025-03-12 | [LLM-Guided Indoor Navigation with Multimodal Map Understanding](https://arxiv.org/abs/2503.11702) | - |
| 2025-03-10 | [LTLCodeGen: Code Generation of Syntactically Correct Temporal Logic for Robot Task Planning](https://arxiv.org/abs/2503.07902) | - |
| 2025-03-04 | [LLM-Glasses: GenAI-driven Glasses with Haptic Feedback for Navigation of Visually Impaired People](https://arxiv.org/abs/2503.16475) | - |
| 2025-02-19 | [NavigateDiff: Visual Predictors are Zero-Shot Navigation Assistants](https://arxiv.org/abs/2502.13894) | - |
| 2025-01-08 | [OpenIN: Open-Vocabulary Instance-Oriented Navigation in Dynamic Domestic Environments](https://arxiv.org/abs/2501.04279) | - |
| 2025-01-07 | [Language and Planning in Robotic Navigation: A Multilingual Evaluation of State-of-the-Art Models](https://arxiv.org/abs/2501.05478) | - |
| 2024-12-13 | [Constraint-Aware Zero-Shot Vision-Language Navigation in Continuous Environments](https://arxiv.org/abs/2412.10137) | - |
| 2024-12-11 | [RoomTour3D: Geometry-Aware Video-Instruction Tuning for Embodied Navigation](https://arxiv.org/abs/2412.08591) | - |
| 2024-12-09 | [Uni-NaVid: A Video-based Vision-Language-Action Model for Unifying Embodied Navigation Tasks](https://arxiv.org/abs/2412.06224) | - |
| 2024-12-05 | [NaVILA: Legged Robot Vision-Language-Action Model for Navigation](https://arxiv.org/abs/2412.04453) | - |
| 2024-11-18 | [VLN-Game: Vision-Language Equilibrium Search for Zero-Shot Semantic Navigation](https://arxiv.org/abs/2411.11609) | - |
| 2024-10-29 | [Reliable Semantic Understanding for Real World Zero-shot Object Goal Navigation](https://arxiv.org/abs/2410.21926) | - |
| 2024-10-11 | [VLM See, Robot Do: Human Demo Video to Robot Action Plan via Vision Language Model](https://arxiv.org/abs/2410.08792) | - |
| 2024-09-30 | [Robot Navigation Using Physically Grounded Vision-Language Models in Outdoor Environments](https://arxiv.org/abs/2409.20445) | - |
| 2024-09-27 | [Open-Nav: Exploring Zero-Shot Vision-and-Language Navigation in Continuous Environment with Open-Source LLMs](https://arxiv.org/abs/2409.18794) | - |
| 2024-09-27 | [OpenObject-NAV: Open-Vocabulary Object-Oriented Navigation Based on Dynamic Carrier-Relationship Scene Graph](https://arxiv.org/abs/2409.18743) | - |
| 2024-09-26 | [GSON: A Group-based Social Navigation Framework with Large Multimodal Model](https://arxiv.org/abs/2409.18084) | - |
| 2024-09-24 | [BehAV: Behavioral Rule Guided Autonomy Using VLMs for Robot Navigation in Outdoor Scenes](https://arxiv.org/abs/2409.16484) | - |
| 2024-09-22 | [HM3D-OVON: A Dataset and Benchmark for Open-Vocabulary Object Goal Navigation](https://arxiv.org/abs/2409.14296) | [GitHub](https://github.com/facebookresearch/habitat-matterport3d-dataset) |
| 2024-09-20 | [Hey Robot! Personalizing Robot Navigation through Model Predictive Control with a Large Language Model](https://arxiv.org/abs/2409.13393) | - |
| 2024-09-17 | [Multi-Floor Zero-Shot Object Navigation Policy](https://arxiv.org/abs/2409.10906) | - |
| 2024-09-08 | [Socially-Aware Robot Navigation Enhanced by Bidirectional Natural Language Conversations Using Large Language Models](https://arxiv.org/abs/2409.04965) | - |
| 2024-08-09 | [Loc4Plan: Locating Before Planning for Outdoor Vision and Language Navigation](https://arxiv.org/abs/2408.05090) | - |
| 2024-07-31 | [Navigating Beyond Instructions: Vision-and-Language Navigation in Obstructed Environments](https://arxiv.org/abs/2407.21452) | - |
| 2024-07-02 | [Open Scene Graphs for Open World Object-Goal Navigation](https://arxiv.org/abs/2407.02473) | - |
| 2024-06-27 | [Human-Aware Vision-and-Language Navigation: Bridging Simulation to Reality with Dynamic Human Interactions](https://arxiv.org/abs/2406.19236) | - |
| 2024-06-20 | [CityNav: A Large-Scale Dataset for Real-World Aerial Navigation](https://arxiv.org/abs/2406.14240) | - |
| 2024-06-17 | [Minimal Self in Humanoid Robot &quot;Alter3&quot; Driven by Large Language Model](https://arxiv.org/abs/2406.11420) | - |
| 2024-06-14 | [Sim-to-Real Transfer via 3D Feature Fields for Vision-and-Language Navigation](https://arxiv.org/abs/2406.09798) | - |
| 2024-06-11 | [A3VLM: Actionable Articulation-Aware Vision Language Model](https://arxiv.org/abs/2406.07549) | - |
| 2024-06-07 | [InstructNav: Zero-shot System for Generic Instruction Navigation in Unexplored Environment](https://arxiv.org/abs/2406.04882) | - |
| 2024-05-27 | [Vision-and-Language Navigation Generative Pretrained Transformer](https://arxiv.org/abs/2405.16994) | - |
| 2024-05-16 | [SEEK: Semantic Reasoning for Object Goal Navigation in Real World Inspection Tasks](https://arxiv.org/abs/2405.09822) | - |
| 2024-05-08 | [LOC-ZSON: Language-driven Object-Centric Zero-Shot Object Retrieval and Navigation](https://arxiv.org/abs/2405.05363) | - |
| 2024-03-30 | [VLM-Social-Nav: Socially Aware Robot Navigation through Scoring using Vision-Language Models](https://arxiv.org/abs/2404.00210) | - |
| 2024-03-27 | [3P-LLM: Probabilistic Path Planning using Large Language Model for Autonomous Robot Navigation](https://arxiv.org/abs/2403.18778) | - |
| 2024-03-27 | [Online Embedding Multi-Scale CLIP Features into 3D Maps](https://arxiv.org/abs/2403.18178) | - |
| 2024-03-26 | [Hierarchical Open-Vocabulary 3D Scene Graphs for Language-Grounded Robot Navigation](https://arxiv.org/abs/2403.17846) | - |
| 2024-03-22 | [CoNVOI: Context-aware Navigation using Vision Language Models in Outdoor and Indoor Environments](https://arxiv.org/abs/2403.15637) | - |
| 2024-03-21 | [Leveraging Large Language Model-based Room-Object Relationships Knowledge for Enhancing Multimodal-Input Object Goal Navigation](https://arxiv.org/abs/2403.14163) | - |
| 2024-03-15 | [Advancing Object Goal Navigation Through LLM-enhanced Object Affinities Transfer](https://arxiv.org/abs/2403.09971) | - |
| 2024-03-09 | [Towards Deviation-Robust Agent Navigation via Perturbation-Aware Contrastive Learning](https://arxiv.org/abs/2403.05770) | - |
| 2024-02-24 | [NaVid: Video-based VLM Plans the Next Step for Vision-and-Language Navigation](https://arxiv.org/abs/2402.15852) | - |
| 2023-12-25 | [WebVLN: Vision-and-Language Navigation on Websites](https://arxiv.org/abs/2312.15820) | - |
| 2023-12-06 | [VLFM: Vision-Language Frontier Maps for Zero-Shot Semantic Navigation](https://arxiv.org/abs/2312.03275) | - |
| 2023-10-11 | [Co-NavGPT: Multi-Robot Cooperative Visual Semantic Navigation Using Vision Language Models](https://arxiv.org/abs/2310.07937) | [GitHub](https://github.com/GengzeZhou/NavGPT) |
| 2023-09-19 | [Bridging Zero-shot Object Navigation and Foundation Models through Pixel-Guided Navigation Skill](https://arxiv.org/abs/2309.10309) | - |
| 2023-09-15 | [Find What You Want: Learning Demand-conditioned Object Attribute Space for Demand-driven Navigation](https://arxiv.org/abs/2309.08138) | - |
| 2023-07-12 | [VELMA: Verbalization Embodiment of LLM Agents for Vision and Language Navigation in Street View](https://arxiv.org/abs/2307.06082) | - |
| 2023-06-20 | [Habitat Synthetic Scenes Dataset (HSSD-200): An Analysis of 3D Scene Scale and Realism Tradeoffs for ObjectGoal Navigation](https://arxiv.org/abs/2306.11290) | [GitHub](https://github.com/facebookresearch/habitat-lab) |
| 2023-05-23 | [Masked Path Modeling for Vision-and-Language Navigation](https://arxiv.org/abs/2305.14268) | - |
| 2023-04-11 | [L3MVN: Leveraging Large Language Models for Visual Target Navigation](https://arxiv.org/abs/2304.05501) | [GitHub](https://github.com/ybgdgh/L3MVN) |
| 2022-12-09 | [Self-Supervised Object Goal Navigation with In-Situ Finetuning](https://arxiv.org/abs/2212.05923) | - |
| 2022-06-22 | [Graph-Based Multi-Robot Path Finding and Planning](https://arxiv.org/abs/2206.11319) | - |
| 2022-01-12 | [Dynamical Audio-Visual Navigation: Catching Unheard Moving Sound Sources in Unmapped 3D Environments](https://arxiv.org/abs/2201.04279) | - |
| 2021-10-14 | [Self-Supervised Domain Adaptation for Visual Navigation with Global Map Consistency](https://arxiv.org/abs/2110.07184) | - |
| 2021-09-16 | [Habitat-Matterport 3D Dataset (HM3D): 1000 Large-scale 3D Environments for Embodied AI](https://arxiv.org/abs/2109.08238) | [GitHub](https://github.com/facebookresearch/habitat-matterport3d-dataset) |
| 2020-12-10 | [Visual Perception Generalization for Vision-and-Language Navigation via Meta-Learning](https://arxiv.org/abs/2012.05446) | - |
| 2020-11-07 | [Sim-to-Real Transfer for Vision-and-Language Navigation](https://arxiv.org/abs/2011.03807) | - |
| 2020-10-19 | [Language and Visual Entity Relationship Graph for Agent Navigation](https://arxiv.org/abs/2010.09304) | - |
| 2019-12-24 | [SoundSpaces: Audio-Visual Navigation in 3D Environments](https://arxiv.org/abs/1912.11474) | [GitHub](https://github.com/facebookresearch/sound-spaces) |

---

## 📊 Statistics

| Category | Count |
|----------|-------|
| Foundation & Benchmark | 47 |
| Understanding the Decision | 46 |
| Understanding the Error | 22 |
| Understanding the Future | 27 |
| Understanding the History | 56 |
| Understanding the Reality | 117 |
| **Total** | **315** |
