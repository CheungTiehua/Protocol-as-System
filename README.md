# Protocol-as-System (PaS) 

### 声明式协议计算范式：实现完全可审计的 AI 生成
### A Declarative Protocol Computing Paradigm for Auditable AI Generation

**Author:** Cheung Tiehua (cheungtiehua@gmail.com)  
**Field:** Theoretical AI, System Architecture, Topological Dynamics  
**Core Model:** PC-ITS (Protocol-Constrained Interactive Transition System)

---

## 💡 Overview / 概述

This repository hosts the formal framework for **Protocol-as-System (PaS)**, a paradigm shift in AI governance. We redefine the Large Language Model (LLM) not as an autonomous executor, but as a **"State Transition Proposal Generator."** 本仓库展示了“**协议即系统 (PaS)**”的形式化架构。我们实现了 AI 治理范式的根本迁移：将大语言模型（LLM）重新定义为“**状态转移提议生成器**”，而非具备自主写入权的执行主体。

### Two Pillars of the Paradigm / 范式两大支柱：

* **Top-down: Protocol-as-System (PaS)** System sovereignty is anchored in explicit, non-bypassable, and auditable **Declarative Protocols**. Behavior is defined by state-space legitimacy, not execution paths.  
  **自上而下：协议即系统 (PaS)** —— 系统主权由显式、不可绕过且可审计的“**声明式协议**”锚定。系统行为取决于状态空间的合法性声明，而非程序的执行路径。

* **Bottom-up: Operational Closure (OCG/DOC)** Achieving structural stability through **Topological Contraction**. By applying **Declarative Operational Closure (DOC)**, we induce a **Probabilistic Stable Operational State (PSOS)**.  
  **自下而上：运行闭合 (OCG)** —— 通过“**拓扑收缩**”确立结构稳定性。通过施加声明式运行闭合（DOC），诱导系统进入概率稳定运行态（PSOS）。

---

## 🏗️ Core Theory / 核心理论

### 1. PC-ITS Model (协议约束交互式状态转移系统)
We formalize the system interaction as a 5-tuple:  
我们将系统交互形式化为五元组：

$$V = \langle S, A, P, \delta, \Omega \rangle$$

* **S (State Space)**: Explicitly defined, auditable structured objects. (显式定义的结构化状态对象)
* **A (Action Proposals)**: Generative outputs treated as unexecuted transition requests. (作为未执行转移请求的生成输出)
* **P (Protocol Predicates)**: Purely declarative adjudication: $(S, A) \to \{ALLOW, DENY\}$. (纯声明式状态判定)
* **$\delta$ (Transition Function)**: Controlled state updates contingent on protocol clearance. (基于协议准入的受控状态转移)
* **$\Omega$ (Sovereign Source)**: External mechanism for non-autonomous finality. (体现非自治性的外部主权源)

### 2. Topological Contraction & Governance (拓扑收缩与治理)
The system constrains the "probabilistic drift" of LLMs by defining a **Minimal Closure Kernel ($K_{min}$)**. In this framework, **hallucination governance is an intrinsic byproduct of topological contraction**, not a targeted intervention.  

系统通过定义“**最小闭合内核 ($K_{min}$)**”强制约束 LLM 的“概率漂移”。在此框架下，**幻觉治理被定义为拓扑收缩的内生副产物**，而非外部的目标性干预。

---

## 📂 Repository Structure / 仓库结构

* **[/Papers](./Papers)**: 
    * **[Protocol-as-System (PDF)](./Papers/Protocol_as_System.pdf)** - 系统架构范式与 PC-ITS 形式化证明。
    * **[Operational-Closure (PDF)](./Papers/Operational_Closure.pdf)** - 运行闭合理论与生成拓扑收缩数学基础。
* **`/Protocols`**: Exemplars of Declarative Protocol Objects (DOC). (声明式协议对象示例)

---

## 📜 Citation / 引用

If you apply the PaS paradigm or the PC-ITS model in your research, please cite:  
若您的研究涉及 PaS 范式或 PC-ITS 模型，请引用：

> **Cheung, T. (2026).** *Protocol-as-System: A Declarative Protocol Computing Paradigm for Auditable AI Generation.* GitHub Repository: `https://github.com/CheungTiehua/Protocol-as-System`
