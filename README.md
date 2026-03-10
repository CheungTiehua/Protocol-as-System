# Protocol-as-System (PaS) 
### 声明式协议计算范式：实现可审计的 AI 生成
### A Declarative Protocol Computing Paradigm for Auditable AI Generation

**Author:** Cheung Tiehua (cheungtiehua@gmail.com)  
**Field:** Theoretical AI, System Architecture, Topological Dynamics  
**Core Model:** PC-ITS (Protocol-Constrained Interactive Transition System)

---

## 💡 Overview / 概述

This repository presents a novel paradigm for AI governance: **Protocol-as-System (PaS)**. We redefine AI not as an autonomous agent, but as a **"State Transition Proposal Generator."** 本仓库提出了一种全新的 AI 治理范式：**协议即系统 (PaS)**。我们重新定义了 AI 的角色——它不再是一个自主执行的主体，而是一个“**状态转移提议生成器**”。

### Two Pillars of the Framework / 框架的两大支柱：

1. **Top-down: Protocol-as-System (PaS)** System behavior is governed by explicit, non-bypassable, and auditable **Declarative Protocols**.  
   **自上而下：协议即系统 (PaS)** —— 系统行为由显式、不可绕过且可审计的“声明式协议”统一裁定。

2. **Bottom-up: Operational Closure (OCG/DOC)** Achieving generative stability through **Topological Contraction**. By applying Declarative Operational Closure (DOC), we induce a Probabilistic Stable Operational State (PSOS).  
   **自下而上：运行闭合 (OCG)** —— 通过“拓扑收缩”实现生成稳定性。通过应用声明式运行闭合 (DOC)，诱导模型进入概率稳定运行状态 (PSOS)。

---

## 🏗️ Core Theory / 核心理论

### 1. PC-ITS Model (协议约束状态机)
We formalize the interaction as: $\mathcal{V} = \langle S, A, P, \delta, \Omega \rangle$
- **S**: State Space (状态空间)
- **A**: Action Proposals (动作提议)
- **P**: Protocol Predicates (协议判定: ALLOW / DENY)
- **$\delta$**: Transition Function (受控转移函数)

### 2. Topological Contraction (拓扑收缩)
The system constrains the "probabilistic drift" of LLMs by defining a **Minimal Closure Kernel ($\mathcal{K}_{min}$)**.
系统通过定义“最小闭合内核”，限制了大语言模型的概率漂移，解决了幻觉与失控问题。

---

## 📂 Repository Structure / 仓库结构

* **`/Papers`**: 
    * `Protocol-as-System.pdf/docx`: Protocol_as_System：A Declarative Protocol Computing Paradigm for Auditable AI Generation. (协议即系统)
    * `Operational_Closure.pdf/docx`: Operational_Closure_and_Generative_Topological_Contraction. (声明式运行闭包)
* **`/Examples`**: Demonstrations of DOC and PaS implementations. (协议实现示例)

---

## 📜 Citation / 引用

If you use this framework in your research, please cite:
如果您在研究中使用此框架，请引用：

> Cheung, T. (2026). Protocol-as-System: A Declarative Protocol Computing Paradigm for Auditable AI Generation. GitHub: [Your-Repo-URL]
