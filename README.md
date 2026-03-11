# Awesome Scaling Coding Agent Envs 🚀

<p align="center">
  <img src="https://awesome.re/badge.svg" alt="Awesome">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/Focus-RL%20%26%20Scaling-orange" alt="Focus">
</p>

> **The next frontier of Coding Agents isn't just better models, but the massive scaling of the environments they live in.**

---

## 🌟 Introduction

As coding agents evolve from simple completion tools to autonomous software engineers, the bottleneck has shifted. To achieve general intelligence for software engineering, we need **dynamic, scalable, and high-fidelity environments** that enable continuous learning.

This repository is a curated collection of resources dedicated to:
1. **Automated Environment Setup**: Converting raw GitHub Issues/PRs into reproducible, sandboxed execution environments.
2. **Scalable Instance Synthesis**: Generating infinite, diverse training instances beyond existing human-annotated data.
3. **Novel Training Paradigms**: Scaling autonomous training loops through self-play and recursive feedback.


### Core Pillars

| Pillar | Description | Keywords |
|---|---|---|
| **Auto-Grounding** | Automatically resolving dependencies and environment state from project metadata. | `Repo-to-Env`, `Dependency Resolution` |
| **Instance Synthesis** | Scaling the problem space beyond human-written issues. | `Issue Synthesis`, `Unit Test Generation` |
| **Training Paradigms** | Beyond standard RL: Scaling via self-play, search-based optimization, and recursive self-improvement. | `Self-Play `, `MCTS`, `PRM`, `Autonomous Scaling` |

---

### 🛠️ Automated Environment Setup
##### Benchmark

- (Fu et al., arxiv 2025) Multi-Docker-Eval: A ‘Shovel of the Gold Rush’ Benchmark on Automatic Environment Building for Software Engineering [[Paper](https://www.arxiv.org/abs/2512.06915)] [[Data](https://huggingface.co/datasets/litble/Multi-Docker-Eval)]
- (Eliseeva et al., ICLR 2025 workshop) ENVBENCH: A BENCHMARK FOR AUTOMATED ENVIRONMENT SETUP [[Paper](https://arxiv.org/pdf/2503.14443)] [[Data](https://github.com/JetBrains-Research/EnvBench)]
- (Kuang et al., arxiv 2025) Process-Level Trajectory Evaluation for Environment Configuration in Software Engineering Agents [[Paper](https://arxiv.org/abs/2510.25694)] [[Data](https://github.com/TencentYoutuResearch/EnConda-Bench)]
- (Milliken et al., Sanner 2025) Beyond pip install: Evaluating LLM Agents for the Automated Installation of Python Projects [[Paper](https://arxiv.org/pdf/2412.06294)] [[Data](https://github.com/coinse/installamatic)]

##### EnvAgent

- (Zhang et al., arxiv 2026) DOCKSMITH: Scaling Reliable Coding Environments via an Agentic Docker Builder [[Paper](https://arxiv.org/abs/2602.00592)]
- (Li et al., arxiv 2026) HerAgent: Rethinking the Automated Environment Deployment via Hierarchical Test Pyramid [[Paper](https://arxiv.org/abs/2602.07871)] [[Code](https://github.com/EuniAI/HerAgent)]
- (Kovrigin et al., NIPS2025 workshop) Advancing Environment Setup LLMs through Online Reinforcement Learning [[Paper](https://openreview.net/pdf?id=9TsxdPdhSz)] [[Code](https://github.com/envsetup-rl-dl4c/envsetup-rl)]
- (Guo et al., FSE 2026) SWE-Factory: Your Automated Factory for Issue
Resolution Training Data and Evaluation Benchmarks [[Paper](https://arxiv.org/pdf/2506.10954v1)] [[Code](https://github.com/DeepSoftwareAnalytics/swe-factory)]
- (Hu et al., NIPS2025) An LLM-based Agent for Reliable Docker Environment Configuration [[Paper](https://arxiv.org/pdf/2502.13681v1)] [[Code](https://github.com/bytedance/Repo2Run)]
- (Badertdinov et al., arxiv 2025) SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents [[Paper](https://arxiv.org/pdf/2505.20411)] [[Data](https://huggingface.co/datasets/nebius/SWE-rebench)]
- (Zhang et al., NIPS 2025) SWE-bench Goes Live! [[Paper](https://arxiv.org/pdf/2505.23419)] [[Code](https://github.com/microsoft/RepoLaunch)]
- (Xie et al., arxiv 2025) RepoST: Scalable Repository-Level Coding Environment Construction with Sandbox Testing [[Paper](https://arxiv.org/abs/2503.07358)] [[Data](https://github.com/yiqingxyq/RepoST)]
- (Bouzenia and Pradel, ISSTA 2025) You Name It, I Run It: An LLM Agent to Execute Tests of Arbitrary Projects [[Paper](https://arxiv.org/abs/2412.10133)] [[Code](https://github.com/sola-st/ExecutionAgent)]
- (Jain et al., ICML 2024) R2E: Turning any GitHub Repository into a Programming Agent Environment [[Paper](https://openreview.net/pdf/13f2979bd779bbc9936d509aaacab58f9f3fbe1d.pdf)] [[Code](https://github.com/r2e-project/r2e)]

### 🪄 Scalable Instance Synthesis
##### BugFix / Feature / Perf
- (Zhu et al., arxiv 2025) Training Versatile Coding Agents in Synthetic Environments [[Paper](https://arxiv.org/pdf/2512.12216)] [[Code](https://github.com/neulab/SWE-Playground)]
- (Sonwane et al., arxiv 2025) BugPilot: Complex Bug Generation for Efficient Learning of SWE Skills [[Paper](https://arxiv.org/pdf/2510.19898)] [[Code](https://microsoft.github.io/debug-gym/)]
- (Pham et al., arxiv 2025) SWE-Synth: Synthesizing Verifiable Bug-Fix Data to Enable Large Language Models in Resolving Real-World Bugs [[Paper](https://arxiv.org/pdf/2504.14757)] [[Code](https://github.com/FSoft-AI4Code/SWE-Synth)]
- (Wang et al., arxiv 2025) SWE-Mirror: Scaling Issue-Resolving Datasets by Mirroring Issues Across Repositories [[Paper](https://arxiv.org/pdf/2509.08724)]
- (Yang et al., arxiv 2025) SWE-smith: Scaling Data for Software Engineering Agents [[Paper](https://arxiv.org/pdf/2504.21798)] [[Code](https://github.com/SWE-bench/SWE-smith)]
- (Jain et al., COLM 2025) R2E-Gym: Procedural Environment Generation and Hybrid Verifiers for Scaling Open-Weights SWE Agents [[Paper](https://arxiv.org/pdf/2504.07164)] [[Code](https://github.com/R2E-Gym/R2E-Gym)]
- (Zhang et al., ICML 2025) SWE-Flow: Synthesizing Software Engineering Data in a Test-Driven Manner [[Paper](https://arxiv.org/pdf/2506.09003)] [[Code](https://github.com/Hambaobao/SWE-Flow)]

##### Test Generation
- (Nashid et al., arxiv 2025) Issue2Test: Generating Reproducing Test Cases from Issue Reports [[Paper](https://arxiv.org/pdf/2503.16320)] [[Code](https://github.com/test-generation/issue2test)]
- (Ahmed et al., ICML 2025) Otter: Generating Tests from Issues to Validate SWE Patches [[Paper](https://arxiv.org/pdf/2502.05368)] [[Code](https://github.com/IBM/TDD-Bench-Verified)]
- (Ahmed et al., arxiv 2024) TDD-Bench Verified: Can LLMs Generate Tests for Issues Before They Get Resolved? [[Paper](https://arxiv.org/pdf/2412.02883)] [[Code](https://github.com/IBM/TDD-Bench-Verified)]
- (Mundler et al., NIPS 2024) SWT-Bench: Testing and Validating Real-World Bug-Fixes with Code Agents [[Paper](https://arxiv.org/pdf/2406.12952)] [[Code](https://github.com/logic-star-ai/swt-bench)]
- (Xu et al., ACL 2025) UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench [[Paper](https://arxiv.org/pdf/2506.09289)] [[Code](https://github.com/cuhk-shenzhen-se/utboost)]


### 📈 Novel Training Paradigms
##### Self-Play / Recursive-improvement
- (Wei et al., arxiv 2025) Toward Training Superintelligent Software Agents through Self-Play SWE-RL [[Paper](https://arxiv.org/pdf/2512.18552)]
- (Kumar et al., arxiv 2026) Digital Red Queen: Adversarial Program Evolution in Core War with LLMs [[Paper](https://arxiv.org/pdf/2601.03335)] [[Code](https://github.com/SakanaAI/drq/)]
- (Rank et al., arxiv 2025) PostTrainBench: Measuring AI Ability to Perform LLM Post-Training [[Code](https://github.com/aisa-group/PostTrainBench)]

##### (P)RM / Verifier / MCTS
- (Raghavendra et al., arxiv 2026) Agentic Rubrics as Contextual Verifiers for SWE Agents [[Paper](https://arxiv.org/pdf/2601.04171)]
- (Shum et al., arxiv 2025) SWE-RM: EXECUTION-FREE FEEDBACK FOR SOFTWARE ENGINEERING AGENTS [[Paper](https://www.arxiv.org/pdf/2512.21919)]
- (Xia et al., arxiv 2025) LIVE-SWE-AGENT: Can Software Engineering Agents Self-Evolve on the Fly? [[Paper](https://arxiv.org/pdf/2511.13646)] [[Code](https://github.com/OpenAutoCoder/live-swe-agent)]
- (Xi et al., arxiv 2025) AgentPRM: Process Reward Models for LLM Agents via Step-Wise Promise and Progress [[Paper](https://arxiv.org/pdf/2511.08325)]
- (Gandhi et al., NIPS 2025 workshop) When Agents go Astray: Course-Correcting SWE Agents with PRMs [[Paper](https://arxiv.org/pdf/2509.02360)]
- (Antoni  et al., ICLR 2025) SWE-SEARCH: ENHANCING SOFTWARE AGENTS WITH MONTE CARLO TREE SEARCH AND ITERATIVE REFINEMENT [[Paper](https://arxiv.org/pdf/2410.20285)] [[Code](https://github.com/aorwall/moatless-tree-search)]

---

### 🙌 Contribution
We welcome contributions! If you have a tool, paper, or dataset that helps in scaling the "gym" for coding agents, please feel free to open a PR.
