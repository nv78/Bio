<h1 align="center">Natan Vidra</h1>

<p align="center">
  <b>Co-founder & CEO of <a href="https://anote.ai">Anote</a></b>: human-centered AI for enterprises, federal clients and model providers.<br/>
  Multi-agent systems · Synthetic data · LLM evaluation · RAG · Human-in-the-loop learning
</p>

<p align="center">
  <a href="https://anote.ai"><img src="https://img.shields.io/badge/anote.ai-website-4B32C3?style=flat-square" alt="anote.ai"/></a>
  <a href="https://github.com/anote-ai"><img src="https://img.shields.io/badge/GitHub-anote--ai-181717?style=flat-square&logo=github" alt="anote-ai on GitHub"/></a>
  <a href="https://arxiv.org/search/?query=Vidra%2C+Natan&searchtype=author"><img src="https://img.shields.io/badge/Papers-arXiv-B31B1B?style=flat-square&logo=arxiv" alt="Papers"/></a>
  <a href="mailto:vidranatan@gmail.com"><img src="https://img.shields.io/badge/Email-vidranatan%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 👋 About

I build AI systems that work in the real world: reliable, measurable, and backed by high-quality data. At **Anote** (NYC) we cover the full AI/ML lifecycle, from dataset curation, annotation and synthetic data through fine-tuning, evaluation, RAG, multi-agent frameworks and private on-prem deployments.

- 🏢 **Anote**, co-founder & CEO. Products, research and government AI programs.
- 💼 Previously **Deloitte Applied AI**, data scientist / software engineer (NLP, computer vision, analytics).
- 🎓 **Cornell University**: B.S. Electrical & Computer Engineering, M.Eng. Computer Science.

Most of my code lives in the **[anote-ai](https://github.com/anote-ai)** organization. Below is a map of that work. Each project links to its copy on my profile, and each copy links back to the anote-ai original. ★ marks projects I led or am a primary contributor to; the others are team and fellow-led projects I directed or advised.

---

## 🗺️ Map of my work

```
Anote
├── 1. Core platform & products     agents · private LLMs · synthetic data · evaluation
├── 2. Research                     Anote AI Research Fellowship: benchmarks & papers
│   ├── Agents & orchestration
│   ├── Retrieval & RAG
│   ├── Data, annotation & synthetic data
│   └── Foundational benchmarks
├── 3. Government, defense & science   NASA · DARPA · NIH · DoD
├── 4. Robotics & prototypes
├── 5. Education & mentorship       Break Through Tech AI Studio · Research Fellowship
└── Private work                    government · platform · enterprise (high level)
```

---

## 1. 🧩 Core Platform & Products

| | Project | What it is | Live |
|---|---|---|---|
| ★ | **[Panacea](https://github.com/anote-ai/Panacea)** | Anote's flagship multi-agent framework for building, deploying and optimizing collaborative AI agents | [chat.anote.ai](https://chat.anote.ai) |
| ★ | **[Synthetic-Data](https://github.com/nv78/Synthetic-Data)** | Synthetic dataset generation across text, image and audio | [anote.ai/syntheticdata](https://anote.ai/syntheticdata) |
| ★ | **[Leaderboard](https://github.com/nv78/Leaderboard)** | Model leaderboard: compare LLMs across evolving datasets and expert evaluations | [anote.ai/leaderboard](https://anote.ai/leaderboard) |
| ★ | **[Community](https://github.com/nv78/Community)** | Community platform for AI research, events and knowledge sharing | [community.anote.ai](https://community.anote.ai) |
| | **[PrivateGPT](https://github.com/anote-ai/PrivateGPT)** | Secure private chatbot for enterprise and on-premise deployment | [download](https://anote.ai/downloadprivategpt) |
| | **[Agentic-Chatbot](https://github.com/nv78/Agentic-Chatbot)** | Framework for building collaborative AI agents | |
| ★ | **[Base](https://github.com/nv78/Base)** · **[Template-Github-Repository](https://github.com/nv78/Template-Github-Repository)** | Anote home page and website template | [anote.ai](https://anote.ai) |

---

## 2. 🔬 Research

Anote's open research program, run through the **[Anote AI Research Fellowship](https://github.com/nv78/Anote-AI-Research-Fellowship)** ★. Papers and code are collected in **[Research](https://github.com/nv78/Research)** ★.

### 📄 Publications
- **Improving Classification Performance with Human Feedback: Label a Few, We Label the Rest** · [arXiv:2401.09555](https://arxiv.org/abs/2401.09555)
- **Enhancing Large Language Model Performance to Answer Questions and Extract Information More Accurately** · [arXiv:2402.01722](https://arxiv.org/abs/2402.01722)
- **Improving Retrieval for RAG-Based Question Answering Models on Financial Documents** · [arXiv:2404.07221](https://arxiv.org/abs/2404.07221)
- 🎤 Talk: [AI and data labeling: combining ML with human input at scale](https://www.youtube.com/watch?v=7I_pBLjMNzs)

### 🤖 Agents & orchestration
| | Project | Focus |
|---|---|---|
| ★ | [Research-EnterpriseBench](https://github.com/nv78/Research-EnterpriseBench) | LLM agents on policy compliance, reliability, auditability and multi-turn consistency |
| ★ | [Research-CodeBench](https://github.com/nv78/Research-CodeBench) | Evaluating AI coding agents: corrected reliability@k, security-adjusted scoring, SWE-bench |
| | [Research-OrchestrateBench](https://github.com/nv78/Research-OrchestrateBench) | Multi-agent orchestration reliability: routing, failure recovery, cascades |
| | [Research-MetaRouting](https://github.com/nv78/Research-MetaRouting) | When should an agent decompose, retrieve, execute, delegate, verify or answer? |
| | [Research-AgenticRAG](https://github.com/nv78/Research-AgenticRAG) | Diagnosing and attributing failure propagation in agentic RAG pipelines |
| | [Research-DevIntent](https://github.com/nv78/Research-DevIntent) | IntentSpec: LLM code that passes tests but violates developer intent |

### 🔎 Retrieval & RAG
| | Project | Focus |
|---|---|---|
| ★ | [Research-FinancialDocumentRetrieval](https://github.com/nv78/Research-FinancialDocumentRetrieval) | Cost-aware RAG ablations on financial filings |
| ★ | [Research-Improving-RAG](https://github.com/nv78/Improving-Retrieval) | Code for the *Improving Retrieval for RAG on Financial Documents* paper |
| | [Research-RetrievalBench](https://github.com/nv78/Research-RetrievalBench) | Chunking × embedding-model interactions across 12 retrieval domains |
| | [Research-semanticchunking](https://github.com/nv78/Research-semanticchunking) | Semantic chunking and hybrid retrieval on FinanceBench |
| | [Research-TuluLegalRAG](https://github.com/nv78/Research-TuluLegalRAG) | Legal RAG with Tulu models |

### 🏷️ Data, annotation & synthetic data
| | Project | Focus |
|---|---|---|
| ★ | [Research-MetadataAnnotation](https://github.com/nv78/Research-MetadataAnnotation) | Does document structure predict the value of metadata-augmented annotation? |
| | [Research-AnnotateBench](https://github.com/nv78/Research-AnnotateBench) | How much labeled data do different annotation strategies need? |
| | [Research-EnterpriseSynth](https://github.com/nv78/Research-EnterpriseSynth) · [Research-Enterprise-Synth-API](https://github.com/nv78/Research-Enterprise-Synth-API) | Agentic SFT and eval data from API schemas without live execution |

### 📊 Foundational benchmarks
| | Project | Focus |
|---|---|---|
| ★ | [Benchmarking-Question-Answering](https://github.com/nv78/Benchmarking-Question-Answering) | QA models across OpenAI, Anthropic, Llama 3 and Mistral |
| ★ | [Benchmarking-Few-Shot-Classification](https://github.com/nv78/Benchmarking-Few-Shot-Classification) | Few-shot text classification |
| ★ | [Benchmarking-Computer-Vision-Models](https://github.com/nv78/Benchmarking-Computer-Vision-Models) | CV and object-detection models |

---

## 3. 🛰️ Government, Defense & Science

| | Project | Program |
|---|---|---|
| ★ | **[Research-NIHOligotox](https://github.com/nv78/Research-NIHOligotox)** | 🏆 **Phase 1 winner**, NIH NCATS OligoTox Open Data Challenge (oligonucleotide toxicity) |
| ★ | [NASA-BeyondTheAlgorithm](https://github.com/nv78/NASA-BeyondTheAlgorithm) | NASA challenge: active-learning flood forecasting |
| ★ | [Adaptive-Intelligence-Layer-for-SmallSat-Earth-Observation](https://github.com/nv78/Adaptive-Intelligence-Layer-for-SmallSat-Earth-Observation) | Onboard adaptive processing for small-satellite Earth observation |
| ★ | [Research-DarpaLyft](https://github.com/nv78/Research-DarpaLyft) | DARPA LIFT: AI-driven drone payload optimization |
| ★ | [Research-PostureAndSustainmentOptimization](https://github.com/nv78/Research-PostureAndSustainmentOptimization) | Robust decision support for military posture and sustainment allocation |
| | [Research-COAGeneration](https://github.com/nv78/Research-COAGeneration) | COA-Bench: course-of-action generation with adversarial self-play |

Plus additional non-public programs with U.S. government partners (see [Private work](#-private-work) below).

---

## 4. 🦾 Robotics & Prototypes

| | Project | What it is |
|---|---|---|
| ★ | [Turtlebot-Robot](https://github.com/nv78/Turtlebot-Robot) | Autonomous TurtleBot: navigation, mapping, YOLO detection, manipulation |
| ★ | [audio-classification](https://github.com/nv78/audio-classification) | Audio classification with active learning and segment-level annotation |
| | [Autonomous-AI-Newsletter](https://github.com/anote-ai/Autonomous-AI-Newsletter) | Fully automated daily AI newsletter |
| | [ai-assisted-translation-prototype](https://github.com/nv78/ai-assisted-translation-prototype) | AI-assisted translation prototype |

---

## 5. 🎓 Education & Mentorship

I design and mentor industry projects for **[Break Through Tech AI Studio](https://www.breakthroughtech.org/)** teams and run the **[Anote AI Research Fellowship](https://github.com/nv78/Anote-AI-Research-Fellowship)**.

| | Cohort | Project |
|---|---|---|
| ★ | [BTT-Anote-1A-2024](https://github.com/nv78/BTT-Anote-1A-2024) | Financial question answering with numerical and categorical answers |
| ★ | [BTT-Anote-1B-2024](https://github.com/anote-ai/BTT-Anote-1B-2024) | Multimodal retrieval-augmented generation |
| ★ | [BTT-Anote-1C-2024](https://github.com/anote-ai/BTT-Anote-1C-2024) | Autonomous AI coding agent |
| | [btt-anote1a](https://github.com/nv78/btt-anote1a) | Multilingual LLM evaluation & RAG chatbot |
| | [btt-anote1b](https://github.com/nv78/btt-anote1b) | Leaderboard platform for benchmarking AI models |
| | [btt-anote2a](https://github.com/anote-ai/btt-anote2a) | Synthetic data generation for ML models |
| ★ | [btt-anote2b](https://github.com/nv78/btt-anote2b) | Multimodal RAG chatbot & computer-vision fine-tuning SDK |

---

## 🔒 Private work

Much of what I build at Anote is private, because it's customer, partner or government work. At a high level:

| Area | What we build |
|---|---|
| **Government & defense AI** | SBIR and prize-challenge work with U.S. defense and space agencies: document understanding for acquisition workflows, AI integration and evaluation, decision support, and simulation and training environments |
| **MLOps platform** | [Anote's end-to-end platform](https://dashboard.anote.ai) for data annotation, dataset creation, fine-tuning, evaluation and chatbot deployment, plus an agents SDK, a developer cookbook and on-premise annotation tooling |
| **Enterprise & research partnerships** | Custom NLP, RAG and data-labeling solutions for companies and academic institutions in healthcare, life sciences, finance, compliance and e-commerce |
| **AI developer tools** | AI-assisted coding tools and evaluation harnesses for coding agents |
| **Go-to-market automation** | Agentic workflows for outreach, proposal drafting and operations dashboards |

Happy to go deeper on any of these in conversation.

---

## 🧪 Personal projects

- [medical-reasoning](https://github.com/nv78/medical-reasoning) · [dental-project](https://github.com/nv78/dental-project) · [Trevor-ChatWithDocs](https://github.com/nv78/Trevor-ChatWithDocs)
- From Cornell: [CornellRobots](https://github.com/nv78/CornellRobots) · [BreakThroughAI](https://github.com/nv78/BreakThroughAI)
- More about me: [Full bio](BIO.md) · [Anote reference page](https://github.com/nv78/anote-ai)

---

<p align="center"><i>Always happy to talk AI, data, and evaluation. Reach me at <a href="mailto:vidranatan@gmail.com">vidranatan@gmail.com</a>.</i></p>
