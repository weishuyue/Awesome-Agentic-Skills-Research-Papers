# 🌟 Awesome Agentic Skills Research Papers

> A curated academic reading list on agentic skills.

Last checked: 2026-06-26.

---

<a name="scope"></a>

## 🗺️ Scope

This repository is research-first. It is intentionally different from implementation catalogs such as `awesome-agent-skills` repositories that list ready-to-install `SKILL.md` packages.

Included:

- Papers where agent skills, skill libraries, skill routing, skill distillation, skill evolution, or skill evaluation are a primary object of study.
- Closely related precursor papers on tool learning, experiential learning, and executable skill libraries.
- Surveys, benchmarks, datasets, and security/governance papers that help define the field.

Not included by default:

- General LLM agent papers unless they introduce or evaluate reusable skills.
- Marketplaces or skill-package collections unless they are used as research artifacts.
- Prompt libraries with no evaluation or research contribution.

<a name="contents"></a>

## 📚 Contents

- [🗺️ Scope](#scope)
- [📚 Contents](#contents)
- [📄 Paper list](#paper-list)
  - [Surveys and position papers](#surveys-and-position-papers)
  - [Foundations and precursors](#foundations-and-precursors)
  - [Skill acquisition and self-improvement](#skill-acquisition-and-self-improvement)
  - [Skill retrieval, routing, and context construction](#skill-retrieval-routing-and-context-construction)
  - [Benchmarks and evaluation](#benchmarks-and-evaluation)
  - [Application-specific skill systems](#application-specific-skill-systems)
  - [Security and governance](#security-and-governance)
- [🔗 Related awesome lists](#related-awesome-lists)
- [🤝 Contributing](#contributing)
- [🆕 Recent skill creation / generation papers to integrate](#recent-skill-creation--generation-papers-to-integrate)

<a name="paper-list"></a>

## 📄 Paper list

### Surveys and Position Papers

| Year | Paper                                                        | Links                                                        | Why it matters                                               |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2026 | Harnessing Agent Skills: Architectural Patterns and a Reference Architecture for Skill-Mediated LLM Agents | [arXiv](https://arxiv.org/abs/2606.20631) | Catalogue of 10 architectural patterns and a 4-layer reference architecture (Supply Chain, Mediation, Execution Control, Evidence & Feedback) for skill harnessing. |
| 2026 | SoK: Agentic Skills -- Beyond Tool Use in LLM Agents         | [arXiv](https://arxiv.org/abs/2602.20867)                    | Frames skills as reusable procedural capabilities beyond atomic tool calls, with lifecycle, representation, scope, and security taxonomies. |
| 2026 | Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward | [arXiv](https://arxiv.org/abs/2602.12430)                    | Focuses on the SKILL.md/progressive-disclosure abstraction, MCP relationship, acquisition, deployment, and trust tiers. |
| 2026 | A Comprehensive Survey on Agent Skills: Taxonomy, Techniques, and Applications | [arXiv](https://arxiv.org/abs/2605.07358)                    | Organizes the literature around representation, acquisition, retrieval, and evolution. |
| 2025 | LLM-Based Agents for Tool Learning: A Survey                 | [Springer](https://link.springer.com/article/10.1007/s41019-025-00296-9) | Useful bridge from tool learning to skill-equipped agents.   |
| 2024 | A Review of Prominent Paradigms for LLM-Based Agents: Tool Use, Planning, and Feedback Learning | [arXiv](https://arxiv.org/abs/2406.05804)                    | Provides the broader agent paradigm background for skill-based systems. |
| 2023 | A Survey on Large Language Model based Autonomous Agents     | [arXiv](https://arxiv.org/abs/2308.11432)                    | General LLM-agent survey; useful for positioning skills against memory, planning, and action modules. |
| 2023 | The Rise and Potential of Large Language Model Based Agents: A Survey | [arXiv](https://arxiv.org/abs/2309.07864)                    | Broad overview of single-agent, multi-agent, and human-agent scenarios. |


### Foundations and Precursors

| Year | Paper                                                        | Links                                                    | Why it matters                                               |
| ---- | ------------------------------------------------------------ | -------------------------------------------------------- | ------------------------------------------------------------ |
| 2023 | Toolformer: Language Models Can Teach Themselves to Use Tools | [arXiv](https://arxiv.org/abs/2302.04761)                | Early self-supervised tool-use training; a precursor to learning callable procedural capability. |
| 2023 | API-Bank: A Comprehensive Benchmark for Tool-Augmented LLMs  | [arXiv](https://arxiv.org/abs/2304.08244)                | Benchmark and dataset for tool-augmented LLM behavior.       |
| 2023 | On the Tool Manipulation Capability of Open-source Large Language Models | [arXiv](https://arxiv.org/abs/2305.16504)                | Studies practical tool manipulation and creates a ToolBench benchmark. |
| 2023 | ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs | [arXiv](https://arxiv.org/abs/2307.16789)                | Large-scale API/tool learning framework and dataset.         |
| 2023 | Voyager: An Open-Ended Embodied Agent with Large Language Models | [arXiv](https://arxiv.org/abs/2305.16291)                | Introduces an ever-growing executable code skill library for Minecraft agents. |
| 2023 | ExpeL: LLM Agents Are Experiential Learners                  | [arXiv](https://arxiv.org/abs/2308.10144)                | Learns from task experience without model-weight updates; important precursor to skill distillation. |
| 2024 | SkillAct: Using Skill Abstractions Improves LLM Agents       | [OpenReview](https://openreview.net/forum?id=6LG3cIRrF4) | Shows that prompting with reusable skill abstractions improves interactive task performance. |
| 2024 | LLMs in the Imaginarium: Tool Learning through Simulated Trial and Error | [arXiv](https://arxiv.org/abs/2403.04746)                | Uses simulated trial-and-error and memory to learn tool use behavior. |

### Skill Acquisition and Self-Improvement

| Year | Paper                                                        | Links                                     | Why it matters                                               |
| ---- | ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ |
| 2024 | Agentic Skill Discovery                                      | [arXiv](https://arxiv.org/abs/2405.15019) | LLM-driven discovery of robotic skills from zero initial skill library. |
| 2025 | Reinforcement Learning for Self-Improving Agent with Skill Library | [arXiv](https://arxiv.org/abs/2512.17102) | Introduces SAGE, using Skill Augmented GRPO and sequential rollouts to accumulate reusable skills. |
| 2025 | CASCADE: Cumulative Agentic Skill Creation through Autonomous Development and Evolution | [arXiv](https://arxiv.org/abs/2512.23880) | Studies cumulative skill creation and evolution for AI-assisted scientific workflows. |
| 2026 | SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning | [arXiv](https://arxiv.org/abs/2602.08234) | Builds a hierarchical SkillBank from experience and co-evolves skill library and policy. |
| 2026 | Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis | [arXiv](https://arxiv.org/abs/2602.03279) | Uses modular reasoning skills to synthesize verifiable training problems. |
| 2026 | AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution | [arXiv](https://arxiv.org/abs/2603.01145) | Derives, maintains, and reuses skills from dialogue and interaction traces. |
| 2026 | Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills | [arXiv](https://arxiv.org/abs/2603.25158) | Distills trajectory-local lessons into transferable agent skills. |
| 2026 | Skill-SD: Skill-Conditioned Self-Distillation for Multi-turn LLM Agents | [arXiv](https://arxiv.org/abs/2604.10674) | Converts agent trajectories into dynamic training-only skill supervision. |
| 2026 | SkillX: Automatically Constructing Skill Knowledge Bases for Agents | [arXiv](https://arxiv.org/abs/2604.04804) | Builds plug-and-play hierarchical skill knowledge bases from trajectories. |
| 2026 | MIND-Skill: Quality-Guaranteed Skill Generation via Multi-Agent Induction and Deduction | [arXiv](https://arxiv.org/abs/2605.08670) | Automatically induces generalizable skills from successful trajectories with quality guarantees. |
| 2026 | Skill1: Unified Evolution of Skill-Augmented Agents via Reinforcement Learning | [arXiv](https://arxiv.org/abs/2605.06130) | Jointly optimizes skill selection, utilization, and distillation from a shared task-outcome signal. |
| 2026 | SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graphs | [arXiv](https://arxiv.org/abs/2605.12039) | Represents skills as graph nodes with prerequisite, enhancement, and co-occurrence edges. |
| 2026 | SkillMaster: Toward Autonomous Skill Mastery in LLM Agents   | [arXiv](https://arxiv.org/abs/2605.08693) | Trains agents to create, refine, and select their own accumulated skills. |
| 2026 | SkillEvolver: Skill Learning as a Meta-Skill                 | [arXiv](https://arxiv.org/abs/2605.10500) | Treats skill learning itself as a reusable meta-skill that authors, deploys, and refines skills. |
| 2026 | SkillGen: Verified Inference-Time Agent Skill Synthesis      | [arXiv](https://arxiv.org/abs/2605.10999) | Synthesizes auditable skills from success and failure trajectories, then verifies net intervention effect. |
| 2026 | SkillGrad: Optimizing Agent Skills Like Gradient Descent     | [arXiv](https://arxiv.org/abs/2605.27760) | Optimizes skill packages with trajectory-level loss evidence and text-based gradients. |
| 2026 | COLLEAGUE.SKILL: Automated AI Skill Generation via Expert Knowledge Distillation | [arXiv](https://arxiv.org/abs/2605.31264) | Distills person- or role-grounded traces into inspectable, correctable skill packages. |
| 2026 | OpenSkill: Open-World Self-Evolution for LLM Agents | [arXiv](https://arxiv.org/abs/2606.06741) | Builds skills and verification signals from scratch in open worlds with no target-task supervision; demonstrates strong transferability across models. |
| 2026 | Ctx2Skill: From Context to Skills: Can Language Models Learn from Context Skillfully? | [arXiv](https://arxiv.org/abs/2604.27660) | Self-evolving multi-agent self-play framework that discovers, refines, and selects context-specific skills without human supervision. |
| 2026 | SoftSkill: Behavioral Compression for Contextual Adaptation | [arXiv](https://arxiv.org/abs/2606.20333) |Compresses long textual skills into a compact continuous prefix, enabling efficient behavioral adaptation and significant context reduction while keeping the base model frozen. |


### Skill Retrieval, Routing, and Context Construction

| Year | Paper                                                        | Links                                     | Why it matters                                               |
| ---- | ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ |
| 2026 | SkillRouter: Retrieve-and-Rerank Skill Selection for LLM Agents at Scale | [arXiv](https://arxiv.org/abs/2603.22455) | Studies large-scale skill routing and shows full skill bodies are crucial routing signal. |
| 2026 | Graph-of-Skills: Dependency-Aware Structural Retrieval for Massive Agent Skills | [arXiv](https://arxiv.org/abs/2604.05333) | Retrieves dependency-aware skill bundles instead of isolated semantically similar skills. |
| 2026 | SkillsInjector: Dynamic Skill Context Construction for LLM Agents | [arXiv](https://arxiv.org/abs/2605.29794) | Learns adaptive skill budgets and set-aware rendering for injected context. |
| 2026 | The Scaling Laws of Skills in LLM Agent Systems              | [arXiv](https://arxiv.org/abs/2605.16508) | Empirically studies how routing and execution degrade or recover as skill libraries scale. |

### Benchmarks and Evaluation

| Year | Paper                                                        | Links                                     | Why it matters                                               |
| ---- | ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ |
| 2026 | How Well Do Agentic Skills Work in the Wild: Benchmarking LLM Skill Usage in Realistic Settings | [arXiv](https://arxiv.org/abs/2604.04323) | Benchmarks skill utility under realistic retrieval and refinement conditions. |
| 2026 | SkillRet: A Large-Scale Benchmark for Skill Retrieval in LLM Agents | [arXiv](https://arxiv.org/abs/2605.05726) | Provides a retrieval benchmark with public agent skills, taxonomy, training samples, and evaluation queries. |
| 2026 | SkillMOO: Multi-Objective Optimization of Agent Skills for Software Engineering | [arXiv](https://arxiv.org/abs/2604.09297) | Optimizes SE skill bundles for both pass rate and inference cost. |
| 2026 | ClawTrace: Cost-Aware Tracing for LLM Agent Skill Distillation | [arXiv](https://arxiv.org/abs/2604.23853) | Adds cost-aware trace cards and skill patches for distillation pipelines. |

### Application-Specific Skill Systems

| Year | Paper                                                        | Links                                     | Why it matters                                               |
| ---- | ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ |
| 2026 | CUA-Skill: Develop Skills for Computer Using Agent           | [arXiv](https://arxiv.org/abs/2601.21123) | Builds a structured skill base for computer-using agents on Windows applications. |
| 2026 | SkillForge: Forging Domain-Specific, Self-Evolving Agent Skills in Cloud Technical Support | [arXiv](https://arxiv.org/abs/2604.08618) | Creates and refines domain-specific enterprise support skills from knowledge bases and operational failures. |
| 2026 | PANDO: Efficient Multimodal AI Agents via Online Skill Distillation | [arXiv](https://arxiv.org/abs/2605.24785) | Online skill distillation for multimodal web agents with efficiency metrics. |

### Security and Governance

No standalone security-only paper is listed yet. For security and governance angles in the current list, see:

- [SoK: Agentic Skills -- Beyond Tool Use in LLM Agents](https://arxiv.org/abs/2602.20867) — supply-chain risk, prompt injection through skills, malicious skill payloads, trust tiers.
- [Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward](https://arxiv.org/abs/2602.12430) — Skill Trust and Lifecycle Governance Framework.
- [How Well Do Agentic Skills Work in the Wild](https://arxiv.org/abs/2604.04323) — fragility of skill gains under realistic retrieval and refinement conditions.
- [SkillHarness: Harnessing Safe Skills for Computer-Use Agents](https://arxiv.org/abs/2606.20636) — models skill learning as a safety-constrained interaction process; introduces skill boundary and selective skill reuse, reducing unsafe skill rate by 57.1%.

<a name="related-awesome-lists"></a>

## 🔗 Related Awesome Lists

These are useful, but have a different center of gravity from this repository.

- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - implementation-oriented skill catalog.
- [kodustech/awesome-agent-skills](https://github.com/kodustech/awesome-agent-skills) - engineering skill catalog.
- [JayLZhou/Awesome-Agent-Skills](https://github.com/JayLZhou/Awesome-Agent-Skills) - companion resources for a survey on agent skills.
- [baibizhe/Awesome-Skills-Paper](https://github.com/baibizhe/Awesome-Skills-Paper) - existing paper list; this repo aims for a research-map style taxonomy and stricter scope notes.
- [Paitesanshi/LLM-Agent-Survey](https://github.com/Paitesanshi/LLM-Agent-Survey) - broader LLM-agent survey resources.
- [WooooDyy/LLM-Agent-Paper-List](https://github.com/WooooDyy/LLM-Agent-Paper-List) - broad LLM-agent paper list.

<a name="contributing"></a>

## 🤝 Contributing

If you want to add a paper, benchmark, project, or resource, please include:

1. Title
2. Venue and year
3. Link to paper, code, or website
4. Suggested category in this taxonomy

Suggested entry format:

```markdown
| 2026 | Paper Title | [arXiv](https://arxiv.org/abs/xxxx.xxxxx) / [Code](https://github.com/...) | One-sentence reason this belongs in agentic skill research. |
```

Inclusion checklist:

- The paper treats skills, reusable procedures, tool-using routines, executable behaviors, skill libraries, or skill routing as a main contribution.
- The link points to a primary source when possible: arXiv, ACL Anthology, OpenReview, publisher page, project page, or official repository.
- The note explains the agentic-skill relevance, not just the general LLM-agent relevance.

<a name="recent-skill-creation--generation-papers-to-integrate"></a>

## 🆕 Recent Skill Creation / Generation Papers to Integrate

| Year | Paper                                                        | Links                                     | Why it matters                                               |
| ---- | ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ |
| 2026 | SkillGenBench: Benchmarking Skill Generation Pipelines for LLM Agents | [arXiv](https://arxiv.org/abs/2605.18693) | Treats skill generation itself as the benchmark target, covering task-conditioned and task-agnostic generation from repository- and document-grounded sources. |
| 2026 | MUSE-Autoskill: Self-Evolving Agents via Skill Creation, Memory, Management, and Evaluation | [arXiv](https://arxiv.org/abs/2605.27366) | Frames skills as long-lived assets in a creation, memory, management, evaluation, and refinement lifecycle. |
| 2026 | SkillLearnBench: Benchmarking Continual Learning Methods for Agent Skill Generation on Real-World Tasks | [arXiv](https://arxiv.org/abs/2604.20087) | Evaluates continual skill generation methods across skill quality, execution trajectory, and task outcome, including skill-creator-style baselines. |
| 2026 | SkillRevise: Improving LLM-Authored Agent Skills via Trace-Conditioned Skill Revision | [arXiv](https://arxiv.org/abs/2606.01139) | Refines imperfect LLM-authored skills using execution traces, repair principles, re-execution, and empirical utility selection. |
| 2026 | SkillForge: Forging Domain-Specific, Self-Evolving Agent Skills in Cloud Technical Support | [arXiv](https://arxiv.org/abs/2604.08618) | Uses a domain-contextualized Skill Creator plus failure analysis and optimization loops for enterprise support skills; already listed above under application-specific systems, but directly relevant to skill creation. |
