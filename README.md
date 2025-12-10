# LLM-based Agents in Healthcare and Medicine: A Curated List

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[badge-qa]: https://img.shields.io/badge/Function-Q%26A-00b3b3?style=flat-square
[badge-cds]: https://img.shields.io/badge/Function-Clinical%20Decision%20Support-2962ff?style=flat-square
[badge-doc]: https://img.shields.io/badge/Function-Documentation%20Workflow-f39c12?style=flat-square
[badge-counsel]: https://img.shields.io/badge/Function-Patient%20Counseling-9b59b6?style=flat-square
[badge-research]: https://img.shields.io/badge/Function-Research%20%26%20Discovery-34495e?style=flat-square
[badge-edu]: https://img.shields.io/badge/Function-Education%20%26%20Simulation-8e44ad?style=flat-square

[badge-ki]: https://img.shields.io/badge/Tool--Usage-Knowledge--Integrated-7f8c8d?style=flat-square
[badge-ta]: https://img.shields.io/badge/Tool--Usage-Tool--Augmented-f1c40f?style=flat-square
[badge-mm]: https://img.shields.io/badge/Tool--Usage-Multi--Modal-e91e63?style=flat-square
[badge-ma]: https://img.shields.io/badge/Tool--Usage-Multi--Agent-2c3e50?style=flat-square
[badge-base]: https://img.shields.io/badge/Tool--Usage-Standalone%20LLM-lightgrey?style=flat-square

[badge-auto]: https://img.shields.io/badge/Autonomy-Fully%20Autonomous-2ecc71?style=flat-square
[badge-hitl]: https://img.shields.io/badge/Autonomy-Human--in--the--loop-ff6f00?style=flat-square
[badge-passive]: https://img.shields.io/badge/Autonomy-Passive-95a5a6?style=flat-square

> **Abstract:** Large language models (LLMs) are rapidly migrating from text-only chatbots to **agentic systems** that plan, act, and collaborate within clinical workflows. This repository supplements our survey on LLM-based medical agents, providing a living collection of research papers, implementations, and resources. Each entry is annotated with **functional tags**, **tool-usage type**, and **autonomy level**.

---

## 📖 Menu
- [Surveys](#surveys)
- [Agent Papers](#agent-papers)
  - [2025](#2025)
  - [2024](#2024)
  - [2023 & Earlier](#2023--earlier)
- [General Agent Frameworks](#general-agent-frameworks)

---

## 📚 Surveys
Reviews focusing specifically on agents, trustworthiness, and foundation models in medicine.

- **A Survey of LLM-based Agents in Medicine: How far are we from Baymax?** (2025)  
  [📄 Paper](https://arxiv.org/abs/2502.11211)
- **Multimodal Large Language Models for Medicine: A Comprehensive Survey** (2025)  
  [📄 Paper](https://arxiv.org/abs/2504.21051)
- **A Comprehensive Survey on the Trustworthiness of Large Language Models in Healthcare** (2025)  
  [📄 Paper](https://arxiv.org/abs/2502.15871)
- **LLM-based agentic systems in medicine and healthcare** (Nature Machine Intelligence, 2024)  
  [📄 Paper](https://doi.org/10.1038/s42256-024-00944-1)
- **A Survey on Medical Large Language Models: Technology, Application, Trustworthiness, and Future Directions** (2024)  
  [📄 Paper](https://arxiv.org/abs/2406.03712)
- **A Survey on the Memory Mechanism of Large Language Model based Agents** (2024)  
  [📄 Paper](https://arxiv.org/abs/2404.13501)

---

## 🧠 Agent Papers

### 2025

- **MedAgent-Pro: Towards Multi-modal Evidence-based Medical Diagnosis via Reasoning Agentic Workflow** ![Clinical Decision Support][badge-cds] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2503.18968) [💻 Code](https://github.com/jinlab-imvr/MedAgent-Pro)

- **Agentic Reasoning: Reasoning LLMs with Tools for the Deep Research** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2502.04644)

- **Ask Patients with Patience: Enabling LLMs for Human-Centric Medical Dialogue with Grounded Reasoning** ![Patient Counseling][badge-counsel] ![Knowledge Integrated][badge-ki] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2502.07143)

- **DrugAgent: Automating AI-aided Drug Discovery Programming through LLM Multi-Agent Collaboration** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2411.15692)

- **The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search** ![Research & Discovery][badge-research] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2504.08066)

- **Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2405.02957)

- **RareAgents: Advancing Rare Disease Care through LLM-Empowered Multi-disciplinary Team** ![Clinical Decision Support][badge-cds] ![Multi-Agent][badge-ma] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2412.12475)

- **ColaCare: Enhancing Electronic Health Record Modeling through Large Language Model-Driven Multi-Agent Collaboration** ![Documentation Workflow][badge-doc] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](http://dx.doi.org/10.1145/3696410.3714877)

- **MedAide: Information Fusion and Anatomy of Medical Intents via LLM-based Agent Collaboration** ![Medical Reasoning][badge-cds] ![Multi-Agent][badge-ma] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2410.12532)

- **DH-RAG: A Dynamic Historical Context-Powered Retrieval-Augmented Generation Method for Multi-Turn Dialogue** ![Patient Counseling][badge-counsel] ![Tool Augmented][badge-ta] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2502.13847)

- **Large Language Models as Evaluators in Education: Verification of Feedback Consistency and Accuracy** ![Documentation Workflow][badge-doc] ![Standalone LLM][badge-base] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://www.mdpi.com/2076-3417/15/2/671)

- **Llama 3.1 405B Is Comparable to GPT-4 for Extraction of Data from Thrombectomy Reports** ![Documentation Workflow][badge-doc] ![Knowledge Integrated][badge-ki] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://doi.org/10.1007/s00062-025-01500-z)

### 2024

- **Enhancing LLMs for Impression Generation in Radiology Reports through a Multi-Agent System** ![Documentation Workflow][badge-doc] ![Tool Augmented][badge-ta] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2412.06828)

- **Almanac Copilot: Towards Autonomous Electronic Health Record Navigation** ![Documentation Workflow][badge-doc] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2405.07896)

- **MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://aclanthology.org/2024.findings-acl.33/)

- **MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/90d1fc07f46e31387978b88e7e057a31-Paper-Conference.pdf)

- **Mmedagent: Learning to use medical tools with multi-modal agent** ![Clinical Decision Support][badge-cds] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2407.02483)

- **MAGDA: Multi-agent guideline-driven diagnostic assistance** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2409.06351)

- **DrugAgent: Explainable Drug Repurposing Agent with Large Language Model-based Reasoning** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2408.13378)

- **ChemCrow: Augmenting Large Language Models with Chemistry Tools** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://doi.org/10.1038/s42256-024-00832-8)

- **The Virtual Lab: AI Agents Design New SARS-CoV-2 Nanobodies with Experimental Validation** ![Research & Discovery][badge-research] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://www.biorxiv.org/content/early/2024/11/12/2024.11.11.623004)

- **WebPilot: A Versatile and Autonomous Multi-Agent System for Web Task Execution** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2408.15978)

- **AgentClinic: A Multimodal Agent Benchmark to Evaluate AI in Simulated Clinical Environments** ![Clinical Decision Support][badge-cds] ![Multi-modal][badge-mm] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2405.07960)

- **Ai Hospital: Benchmarking Large Language Models in a Multi-Agent Medical Interaction Simulator** ![Clinical Decision Support][badge-cds] ![Multi-Agent][badge-ma] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2402.09742)

- **ClinicalAgent: Clinical Trial Multi-Agent System with Large Language Model-based Reasoning** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2404.14777)

- **AgentMD: Empowering Language Agents for Risk Prediction with Large-Scale Clinical Tool Learning** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2402.13225)

- **Zodiac: A Cardiologist-Level LLM Framework for Multi-Agent Diagnostics** ![Clinical Decision Support][badge-cds] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2410.02026)

- **Polaris: A Safety-focused LLM Constellation Architecture for Healthcare** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2403.13313)

- **MedChain: Bridging the Gap Between LLM Agents and Clinical Practice through Interactive Sequential Benchmarking** ![Clinical Decision Support][badge-cds] ![Knowledge Integrated][badge-ki] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2412.01605)

- **Towards Next-Generation Medical Agent: How o1 is Reshaping Decision-Making in Medical Scenarios** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2411.14461)

- **EHRAgent: Code Empowers Large Language Models for Few-shot Complex Tabular Reasoning** ![Documentation Workflow][badge-doc] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2401.07128)

- **KRAGEN: A Knowledge Graph-enhanced RAG Framework for Biomedical Problem Solving** ![Clinical Decision Support][badge-cds] ![Knowledge Integrated][badge-ki] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://academic.oup.com/bioinformatics/article/40/6/btae353/7641259)

- **HeCiX: Integrating Knowledge Graphs and Large Language Models for Biomedical Research** ![Research & Discovery][badge-research] ![Knowledge Integrated][badge-ki] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2407.14030)

- **GeneGPT: Augmenting Large Language Models with Domain Tools** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://academic.oup.com/bioinformatics/article/40/2/btae075/7513689)

- **CellAgent: An LLM-driven Multi-Agent Framework for Automated Single-cell Data Analysis** ![Research & Discovery][badge-research] ![Multi-Agent][badge-ma] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2407.09811)

- **LLMs Can Simulate Standardized Patients via Agent Coevolution** ![Patient Counseling][badge-counsel] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2412.11716)

- **AIPatient: Simulating Patients with EHRs and LLM Powered Agentic Workflow** ![Education & Simulation][badge-edu] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2409.18924)

- **MEDCO: Medical Education Copilots Based on A Multi-Agent Framework** ![Education & Simulation][badge-edu] ![Multi-Agent][badge-ma] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2408.12496)

- **Benchmarking Retrieval-Augmented Generation for Medicine (MedRAG)** ![Clinical Decision Support][badge-cds] ![Knowledge Integrated][badge-ki] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://aclanthology.org/2024.findings-acl.372/)

- **Rationale-Guided Retrieval Augmented Generation for Medical Question Answering** ![Q&A][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2411.00300)

- **Biorag: A RAG-LLM Framework for Biological Question Reasoning** ![Q&A][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2408.01107)

- **Improving Medical Reasoning through Retrieval and Self-reflection** ![Q&A][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://academic.oup.com/bioinformatics/article/40/Supplement_1/i119/7700932)

- **Rx Strategist: Prescription Verification using LLM Agents System** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2409.03440)

- **Agentic LLM Workflows for Generating Patient-Friendly Medical Reports** ![Documentation Workflow][badge-doc] ![Standalone LLM][badge-base] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2408.01112)

- **ClinicalLab: Aligning Agents for Multi-Departmental Clinical Diagnostics** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2406.13890)

- **Adaptive Reasoning and Acting in Medical Language Agents** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2410.10020)

- **Beyond Direct Diagnosis: LLM-based Multi-Specialist Agent Consultation** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2401.16107)

- **Mitigating cognitive biases... through multi-agent conversations** ![Clinical Decision Support][badge-cds] ![Standalone LLM][badge-base] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://www.jmir.org/2024/1/e59439)

- **Benchmarking Large Language Models on Communicative Medical Coaching** ![Patient Counseling][badge-counsel] ![Standalone LLM][badge-base] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2402.05547)

- **The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery** ![Research & Discovery][badge-research] ![Multi-modal][badge-mm] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2408.06292)

### 2023 & Earlier

- **React: Synergizing Reasoning and Acting in Language Models** ![Knowledge Retrieval][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2210.03629)

- **Toolformer: Language Models Can Teach Themselves to Use Tools** ![Knowledge Retrieval][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2302.04761)

- **Webgpt: Browser-assisted question-answering with human feedback** (2021)  
  ![Knowledge Retrieval][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2112.09332)

- **Retrieval-augmented generation for knowledge-intensive nlp tasks (RAG)** (2020)  
  ![Knowledge Retrieval][badge-qa] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2005.11401)

- **Conversational Health Agents: A Personalized LLM-Powered Agent Framework** ![Patient Counseling][badge-counsel] ![Tool Augmented][badge-ta] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2310.02374)

- **Epidemic Modeling with Generative Agents** ![Research & Discovery][badge-research] ![Multi-Agent][badge-ma] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2307.04986)

- **Large language models with retrieval-augmented generation for zero-shot disease phenotyping** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2312.06457)

- **PathAsst: A Generative Foundation AI Assistant Towards Artificial General Intelligence of Pathology** ![Clinical Decision Support][badge-cds] ![Multi-modal][badge-mm] ![Human-in-the-loop][badge-hitl]  
  [📄 Paper](https://arxiv.org/abs/2305.15072)

- **Should we be going MAD? A Look at Multi-Agent Debate Strategies for LLMs** ![Clinical Decision Support][badge-cds] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2311.17371)

- **LLM-based Medical Assistant Personalization with Short- and Long-Term Memory Coordination** ![Patient Counseling][badge-counsel] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2309.11696)

---

## General Agent Frameworks
While not exclusively medical, these frameworks are frequently cited as the backbone for medical agent implementation.

- **AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2308.08155)

- **MetaGPT: Meta Programming for A Multi-Agent Collaborative Framework** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2308.00352)

- **Agent AI with LangGraph** ![Research & Discovery][badge-research] ![Tool Augmented][badge-ta] ![Fully Autonomous][badge-auto]  
  [📄 Paper](https://arxiv.org/abs/2412.03801)

  ## 📝 Citation

If you find this repository or our survey helpful in your research, please cite the following paper:

**Agentic Large-Language-Model Systems in Medicine: A Systematic Review and Taxonomy** *Abdul Mohaimen Al Radi, Xu Cao, Fanyang Yu, et al.* TechRxiv. September 08, 2025.

```bibtex
@article{al2025agentic,

  title={Agentic large-language-model systems in medicine: A systematic review and taxonomy},

  author={Al Radi, Abdul Mohaimen and Cao, Xu and Yu, Fanyang and Liu, Yuyuan and Liu, Fengbei and Wang, Chong and Chen, Yuanhong and Chen, Jintai and Wang, Hu and Meng, Yanda and others},

  journal={Authorea Preprints},

  year={2025},

  publisher={Authorea}

}
```