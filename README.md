# MAS Security Papers
A collection of papers on Multi-Agent System (MAS) security, covering defense mechanisms, framework designs, and attack strategies.

## Bookmarks
* [**System Level Defense for MAS**](#system-level-defense-for-mas)
  * [Topology-Aware Defense](#topology-aware-defense)
  * [Psychological and Behavioral Analysis Defense](#psychological-and-behavioral-analysis-defense)
  * [Access Control Defense](#access-control-defense)
* [**MAS Threats (Attack Classification)**](#mas-threats-attack-classification)
  * [Attack Through User Interaction](#attack-through-user-interaction)
  * [Attack Through Agent](#attack-through-agent)
  * [Attack Through External Sources](#attack-through-external-sources)

## System Level Defense for MAS
System-Level Defense operates as the governance mechanism within MAS, abstracting the system into a collaborative network to maintain the resilience and controllability of the multi-agent society from the perspective of communication patterns, role dynamics, global consensus and resource access.

### Topology-Aware Defense
This section focuses on defense mechanisms that secure structural integrity against propagation risks, preventing vulnerability propagation where malicious agents exploit communication networks to disseminate misleading information.

| Time | Title | Venue | Paper | Code |
|------|-------|-------|-------|------|
| 2024.10 | NetSafe: Exploring the Topological Safety of Multi-Agent System | ACL 2025 Findings | [link](https://arxiv.org/abs/2410.15686) | [code](https://anonymous.4open.science/r/NetSafe-B726) |
| 2025.2 | G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems | arXiv | [link](https://arxiv.org/pdf/2502.11127) | [code](https://github.com/wslong20/G-safeguard) |
| 2025.8 | BlindGuard: Safeguarding LLM-based Multi-Agent Systems under Unknown Attacks | arXiv | [link](https://arxiv.org/pdf/2508.08127) | [code](https://github.com/MR9812/BlindGuard) |
| 2025.12 | Tipping the Dominos: Topology-Aware Multi-Hop Attacks on LLM-based Multi-Agent Systems | arXiv | [link](https://arxiv.org/pdf/2512.04129) | - |

### Psychological and Behavioral Analysis Defense
This section focuses on defense mechanisms that conduct continuous audit of subtle intention shifts & deceptive traits through psychological profiling and long-term behavioral monitoring of agents.

| Time | Title | Venue | Paper | Code |
|------|-------|-------|-------|------|
| 2024.8 | PsySafe: A Comprehensive Framework for Psychological-based Attack, Defense, and Evaluation of Multi-agent System Safety | ACL 2024 | [link](https://arxiv.org/abs/2401.11880) | [code](https://github.com/AI4Good24/PsySafe) |
| 2025.7 | AgentXposed: Modeling and Detecting Intention-Hiding Malicious Agents in LLM-based Multi-Agent Systems | arXiv | [link](https://arxiv.org/pdf/2507.04724) | [code](https://anonymous.4open.science/r/AgentXposed-F814) |

### Access Control Defense
This section focuses on defense mechanisms that enforce strict permission boundaries (Zero Trust) for agent's data access and tool usage to prevent unauthorized resource access.

| Time | Title | Venue | Paper | Code |
|------|-------|-------|-------|------|
| 2025.5 | MASTER: Multi-Agent Security Through Exploration of Roles and Topological Structures | arXiv | [link](https://arxiv.org/pdf/2505.18572) | - |
| 2025.2 | RTBAS: Defending LLM Agents Against Prompt Injection and Privacy Leakage | arXiv | [link](https://arxiv.org/pdf/2502.08966) | - |
| 2025.9 | GAMA: A General Anonymizing Multi-Agent System for Privacy Preservation | arXiv | [link](https://arxiv.org/pdf/2509.10018) | [code](https://anonymous.4open.science/r/GAMA/README.md) |

## MAS Threats
MAS threats are categorized by **transmission route** , focusing exclusively on multi-agent-specific attacks (excluding single-agent-only attacks). These attacks exploit inter-agent communication, collaboration mechanisms, and system-level vulnerabilities to compromise collective behavior.

### Attack Through User Interaction
Attacks initiated via user input, exploiting multi-agent communication to propagate adversarial prompts across the system.

| Time | Title | Venue | Paper | Code |
|------|-------|-------|-------|------|
| 2024 | LLM-based Multi-Agents System Attack via Continuous Optimization with Discrete Efficient Search | COLM 2025 | [link](https://openreview.net/pdf?id=ED5diyzc1C) | - |
| 2025 | CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models | arXiv | [link](https://arxiv.org/pdf/2502.14529) | [code](https://github.com/zhrli324/Corba) |
| 2025 | Agents under Siege: Breaking Pragmatic Multi-Agent LLM Systems with Optimized Prompt Attacks | ACL 2025 | [link](https://arxiv.org/pdf/2504.00218) | - |

### Attack Through Agent
Attacks propagating internally via compromised agents, including malicious agent injection and communication hijacking.

| Time | Title | Venue | Paper | Code |
|------|-------|-------|-------|------|
| 2024 | Flooding Spread of Manipulated Knowledge in LLM-Based Multi-Agent Communities | arXiv | [link](https://arxiv.org/pdf/2407.07791) | [code](https://github.com/Jometeorie/KnowledgeSpread) |
| 2025 | Red-Teaming LLM Multi-Agent Systems via Communication Attacks | ACL 2025 Findings | [link](https://arxiv.org/pdf/2502.14847) | - |
| 2025 | Attack the Messages, Not the Agents: A Multi-Round Adaptive Stealthy Tampering Framework for LLM-MAS | arXiv | [link](https://arxiv.org/pdf/2508.03125) | - |

### Attack Through External Sources
Attacks exploiting external tools, memory modules, or peripherals to contaminate multi-agent collaboration.

| Time | Title | Venue | Paper | Code |
|------|-------|-------|-------|------|
| 2024 | AgentPoison: Red-Teaming LLM Agents via Poisoning Memory or Knowledge Bases | NeurIPS 2024 | [link](https://arxiv.org/pdf/2407.12784) | [code](https://github.com/BillChan226/AgentPoison) |
| 2025 | Collaborative Shadows: Distributed Backdoor Attacks in LLM-based Multi-Agent Systems | arXiv | [link](https://arxiv.org/pdf/2510.11246) | - |
| 2025 | Multi-Agent Systems Execute Arbitrary Malicious Code | arXiv | [link](https://arxiv.org/pdf/2503.12188) | - |
