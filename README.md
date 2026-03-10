# OCG-LLM: Operational Closure & Generative Topological Contraction
# OCG-LLM: 运行闭合与生成拓扑收缩理论

**Author:** Cheung Tiehua ([cheungtiehua@gmail.com](mailto:cheungtiehua@gmail.com))  
**Status:** Independent Research (独立研究) | **Field:** Theoretical AI, Topological Dynamics

---

## 🧬 Overview / 概述

This repository hosts the formal framework for **Operationally Closed Generation (OCG)**. Unlike traditional instruction-driven prompting, this research redefines generative stability as a property of **contextual topological structure**.
[cite_start]本仓库展示了 **运行闭合生成 (OCG)** 的形式化框架。与传统的指令驱动提示词（Prompting）不同，本研究将生成稳定性重新定义为**上下文拓扑结构**的一种属性 [cite: 9, 32]。

The core thesis is that current LLMs operate in an **Open Topology Generation (OTG)** state, leading to probabilistic drift. By applying **Declarative Operational Closure (DOC)**, we can induce a **Probabilistic Stable Operational State (PSOS)** through topological contraction.
[cite_start]核心论点是：当前的大语言模型（LLMs）运行在**开放拓扑生成 (OTG)** 状态，导致了概率漂移。通过应用**声明式运行闭合 (DOC)**，我们可以通过拓扑收缩诱导出一个**概率稳定运行状态 (PSOS)** [cite: 11, 13]。

---

## 核心数学模型：最小闭合内核 (The Minimal Closure Kernel)

The transition from open dynamics to a bounded operational domain is defined by the structural lower bound $\mathcal{K}_{min}$:
[cite_start]从开放动态向受限运行域的转变由结构下界 $\mathcal{K}_{min}$ 定义 ：

$$\mathcal{K}_{min} = \{ \Sigma, T, F, A \}$$

* **$\Sigma$ (State Declaration / 状态声明)**: Explicit definition of operational states to demarcate the bounded domain.
    显式定义运行状态，以划定受限域 [cite: 109]。
* **$T$ (Transition Rules / 迁移规则)**: Conditional relations between states that restrict the generative branch space.
    状态间的条件关系，限制生成分支空间 [cite: 111]。
* **$F$ (Failure Boundaries / 失败边界)**: Rejection or termination mechanisms for undefined operations or illegal branches.
    对未定义操作或非法分支的拒绝或终止机制 [cite: 113]。
* **$A$ (Arbitration Mechanism / 仲裁机制)**: Structural consistency and compliance verification prior to token output.
    在令牌（Token）输出前进行结构一致性和合规性验证 [cite: 115]。

---

## 关键假设 (Key Hypotheses)

* [cite_start]**Closure Contraction (H1 / 闭合收缩假设)**: Operational closure induces contraction of the effective generative branch space [cite: 93, 94]。
* [cite_start]**Structural Resolution (H2 / 结构分辨率假设)**: Higher structural resolution yields more stable PSOS [cite: 95, 96]。
* [cite_start]**Agent-Externalization (H3 / 主体去中心化假设)**: Removing personified language reduces semantic expansion and enhances closure strength [cite: 97, 98]。
* [cite_start]**Hallucination Governance (幻觉治理)**: Hallucination reduction is a byproduct of topological contraction, not a targeted intervention [cite: 80, 81]。

---

## 📂 Repository Structure / 仓库结构

* `/Paper`: Full text of *"Operational Closure and Generative Topological Contraction in Large Language Models"* (PDF/Docx).
* `/Formalization`: Detailed breakdown of the **Operational Closure Criteria (OCC)**.
* `/Examples`: Implementation of **DOC layered structures** (from Operational Mode to Output Arbitration).

## 📜 Citation / 引用

If you use this framework or the PSOS model in your research, please cite it as:
如果您在研究中使用此框架或 PSOS 模型，请引用：

> Cheung, T. (2026). *Operational Closure and Generative Topological Contraction in Large Language Models*. GitHub Repository: [Your Repo Link]
