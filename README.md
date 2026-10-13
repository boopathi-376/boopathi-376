<a href="https://boopathi-376.web.app"><img src="./assets/banner.jpg" alt="System Craft — how it actually works." width="100%" /></a>

# Boopathi S

**Software Developer Intern, Levarus** · B.Tech, Artificial Intelligence & Data Science, Dr. Mahalingam College of Engineering and Technology (2023–2027)

[Portfolio](https://boopathi-376.web.app) · [Résumé](https://boopathi-376.web.app/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/boopathisennappan/) · [Hugging Face](https://huggingface.co/Boopathi376) · [Email](mailto:boopathi5140@gmail.com)

---

I work on core banking systems built on Oracle FLEXCUBE at Levarus, and I study how AI systems should be designed: how they retrieve evidence, how they reason over it, and how they show when an answer isn't reliable. My approach is architecture first. Before building anything, I compare the candidate designs, make the trade-offs explicit, and write down the reasons for the final choice.

### Research interests

- **Retrieval for grounded generation:** hybrid dense, sparse and graph retrieval, reranking, and grounding answers in evidence
- **Reliability of LLM systems:** hallucination detection, confidence estimation, and structured, schema-validated outputs
- **Agentic systems:** multi-step workflows with LangGraph, and where agents fit inside enterprise systems such as core banking
- **Automated machine learning:** reinforcement learning for model selection and hyperparameter search

### Currently

- **Levarus** (Jul 2026 – present): core banking on Oracle FLEXCUBE, and exploring AI agents for banking workflows
- **Studying:** banking system architecture, and evaluation methods for retrieval-augmented and agentic systems

---

## Selected work

**[1] Hybrid retrieval with confidence-scored answers for Indian legal question answering**
*Legal AI Chatbot*, 2026 · [code](https://github.com/boopathi-376/Legal-AI-Chatbot)
Combines dense retrieval (Qdrant, multilingual-e5-base-v2), BM25 and a NetworkX knowledge graph, followed by two-stage CrossEncoder reranking. A five-node LangGraph pipeline expands legal abbreviations (IPC, FIR, CrPC), checks answers for hallucination, and assigns each response a High, Medium or Low confidence level. It runs fully locally with Llama 3.2 via Ollama.

**[2] Reinforcement learning for automated model selection and hyperparameter tuning**
*Meta-LambdaLads*, 2026 · [code](https://github.com/boopathi-376/Meta-LambdaLads) · [demo](https://huggingface.co/spaces/Boopathi376/Meta-LambdaLads)
Frames AutoML as a sequential decision problem: a reinforcement-learning agent chooses models and hyperparameters inside a custom environment, served through FastAPI.

**[3] Turning natural-language queries into structured search filters**
*Semantic Filter-Driven Chatbot*, 2025 · [code](https://github.com/boopathi-376/Semantic-Filter-Driven-Chatbot)
Uses E5-Base-V2 embeddings with Qdrant, and validates intent with Qwen2.5-7B (via Ollama), to translate free-text questions into schema-validated JSON filters, with no external API dependency. The same approach underpins **OpenBot**, which I built during my AI internship at InFynd (Nov 2025 – Jan 2026).

---

## Open-source contributions

| Project | Contribution | Status |
|---|---|---|
| [google/adk-python](https://github.com/google/adk-python) | Eval cases kept their position when updated in `LocalEvalSetsManager`; added a regression test ([#7221](https://github.com/google/adk-python/pull/7221)) | Merged · [`a6c6623`](https://github.com/google/adk-python/commit/a6c6623455e6064f1934bdff260abdc3f6eb5025) |
| [mycelium-labs/mycelium](https://github.com/mycelium-labs/mycelium) | Pinned third-party GitHub Actions to immutable commit SHAs; migrated four actions off Node 20 ([#155](https://github.com/mycelium-labs/mycelium/pull/155)) | Merged |

---

## Experience

| | | |
|---|---|---|
| **Software Developer Intern** | Levarus · core banking (Oracle FLEXCUBE), AI agents | Jul 2026 – present |
| **Artificial Intelligence Intern** | InFynd, Coimbatore · built OpenBot, a semantic retrieval system | Nov 2025 – Jan 2026 |

## Honours

- **Winner, Smart India Hackathon 2025**, Smart Education category (Team HackHounds), ₹1.5 lakh prize
- **Office Bearer**, Invictus, AI & DS Association (2024–2025)

## Tools

Python · FastAPI · LangGraph · LangChain · Ollama · Qdrant · ChromaDB · BM25 · Docker · Hugging Face Spaces · Oracle FLEXCUBE · Flutter · Firebase · Java · SQL

---

<sub>I'm happy to discuss system design, retrieval, or AI reliability. You can reach me at <a href="mailto:boopathi5140@gmail.com">boopathi5140@gmail.com</a>.</sub>
