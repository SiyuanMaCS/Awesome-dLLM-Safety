# Awesome Diffusion Language Model Safety 🛡️

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of research on safety, alignment, and security of Diffusion Language Models (dLLMs).

## 📋 Table of Contents

- [Introduction](#-introduction)
- [dLLM Safety](#️-dllm-safety)
  - [dLLM Safety Vulnerabilities](#-dllm-safety-vulnerabilities)
  - [dLLM Safety Alignment](#-dllm-safety-alignment)
- [Diffusion Language Modeling Foundations](#️-diffusion-language-modeling-foundations)
- [General LLM Safety & Alignment](#-general-llm-safety--alignment)
- [Contributing](#-contributing)
- [License](#-license)

## 🎯 Introduction

Diffusion Language Models (dLLMs) generate text via iterative denoising, offering parallel generation and bidirectional conditioning. However, their unique architecture introduces novel security risks (e.g., masking attacks, priming vulnerabilities) that traditional autoregressive safety mechanisms often fail to address. This repository tracks native dLLM safety research and relevant foundational work.

---

## 🛡️ dLLM Safety

### 🔴 dLLM Safety Vulnerabilities

- **[The Devil behind the mask: An emergent safety vulnerability of Diffusion LLMs](https://arxiv.org/abs/2507.11097)** (Jul 2025)
  - Explores "Masking Attacks" enabled by bidirectional attention and parallel decoding.
  - *Sun Yat-Sen University, Shanghai AI Laboratory*

- **[Toward Safer Diffusion Language Models: Discovery and Mitigation of Priming Vulnerability](https://arxiv.org/abs/2510.00565)** (Oct 2025)
  - Identifies "Priming Vulnerabilities" in early denoising steps of the diffusion process.
  - *Institute of Science Tokyo, RIKEN AIP*

- **[DiffuGuard: How Intrinsic Safety is Lost and Found in Diffusion Large Language Models](https://arxiv.org/abs/2509.24296)** (Sep 2025)
  - Analyzes safety boundary stability during iterative generation.

### 🟢 dLLM Safety Alignment

- **[A2D: Any-Order, Any-Step Safety Alignment for Diffusion Language Models](https://arxiv.org/abs/2509.23286)** (Sep 2025)
  - Proposes alignment for any-order generation and template-based prefilling.

- **[Where to Start Alignment? Diffusion Large Language Model May Demand a Distinct Position](https://arxiv.org/abs/2508.12398)** (Aug 2025)
  - Investigates optimal intervention stages in diffusion trajectories.
  - *Nanyang Technological University*

---

## 🏗️ Diffusion Language Modeling Foundations

### Foundational Models

- **[Large Language Diffusion with Autoregressive Prior (LLaDA)](https://arxiv.org/abs/2502.11564)** (Feb 2025)
  - A unified continuous diffusion model for language modeling.
  - *KAIST, DeepAuto.ai*

- **[Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models](https://arxiv.org/abs/2503.09573)** (Mar 2025)
  - Hybrid generation framework between AR and Diffusion paradigms.
  - *Stanford, Cohere, Cornell Tech*

- **[Scaling Diffusion Language Models via Adaptation from Autoregressive Models (DREAM)](https://arxiv.org/abs/2410.17891)** (Oct 2024)
  - Scaling dLLMs via adaptation from pre-trained AR models.
  - *UIUC, HKU, Tencent AI Lab, Apple*

- **[Simple and Effective Masked Diffusion Language Models (SEDD)](https://arxiv.org/abs/2406.07524)** (Jun 2024)
  - Foundational discrete diffusion model using score entropy.
  - *Cornell Tech*

### Surveys

- **[A Survey on Diffusion Language Models](https://arxiv.org/abs/2508.10875)** (Aug 2025)
  - Comprehensive overview of DLMs including architectures, training methods, and safety considerations.

- **[Discrete Diffusion in Large Language and Multimodal Models: A Survey](https://arxiv.org/abs/2506.13759)** (Jun 2025)
  - Systematic survey of discrete diffusion approaches in language and multimodal contexts.


> 🔗 Visit: **[Awesome-Diffusion-Language-Models](https://github.com/ZhenghaoLin/Awesome-Diffusion-Language-Models)**

---

## 🌐 General LLM Safety & Alignment

### Alignment Foundations

- **[Training a Helpful and Harmless Assistant with RLHF](https://arxiv.org/abs/2204.05862)** (Apr 2022)
  - Foundational work on RLHF for safety alignment.
  - *Anthropic*

- **[Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073)** (Dec 2022)
  - Principles-based alignment using RLAIF.
  - *Anthropic*

### Jailbreak & Adversarial Attacks

- **[Universal and Transferable Adversarial Attacks on Aligned LLMs (GCG)](https://arxiv.org/abs/2307.15043)** (Jul 2023)
  - Seminal work on discrete optimization for adversarial prompt generation.
  - *CMU, Center for AI Safety, Bosch Center for AI*


> 🔗 Visit: **[Awesome-LLM-Safety](https://github.com/corca-ai/awesome-llm-safety)**

---

## 🤝 Contributing
If you have any questions, please contact our authors!
masiyuan@westlake.edu.cn

## 🔗 Related Awesome Lists

- [Awesome-Diffusion-Language-Models](https://github.com/ZhenghaoLin/Awesome-Diffusion-Language-Models)
- [Awesome-LLM-Safety](https://github.com/corca-ai/awesome-llm-safety)
- [Awesome-AI-Security](https://github.com/DeepSpaceHarbor/Awesome-AI-Security)

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

---

**Disclaimer**: For research purposes only.  
**Last Updated**: February 2026 | **Maintainer**: [Siyuan Ma](mailto:siyuan.ma.jasper@gmail.com)
