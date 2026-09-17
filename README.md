# Mohammad A. T. Hijjawi

**Senior AI Engineer** · agentic systems, LLM architecture, applied NLP

London · [LinkedIn](https://www.linkedin.com/in/mohammadhijjawi) · [ORCID](https://orcid.org/0009-0001-3199-7769) · mohammad.hijjawi1997@gmail.com

I design, build and deploy AI systems end to end: data pipelines, model work, multi-agent orchestration, retrieval, evaluation, and production serving on Google Cloud Run and AWS.

My core specialism is **agentic AI**: LangGraph state machines and checkpointers, MCP tool layers, retrieval-augmented generation, guardrails as architecture, human-in-the-loop interrupts, and the evaluation harnesses that make an agent defensible in production. I have shipped a six-agent enterprise assistant to Cloud Run and re-delivered it air-gapped on-premise.

---

## Now

- **AI Instructor and AI Engineering Mentor**, Multiverse, London. Hands-on architecture and code review with 130+ engineers building LLM, RAG and agent systems inside their own organisations, including the NHS and the University of Cambridge.
- **Instructor**, Great Learning, with Johns Hopkins University and UT Austin. Designed the reference implementations for a 14-week agentic AI programme: LangGraph agentic RAG, MCP-native ReAct agents, red-teaming, multi-agent systems, HITL workflows and evaluation.

Previously Data Scientist at EMCOR UK (now OCS). Lead AI and Data Engineer at Ideas Beyond Borders since 2019 (Bayt Al Hikma NLP ranking; content from that programme has been read 500 million+ times).

---

## Selected systems

**Insurance claims graph.** Orchestrator, specialised A2A worker agents, aggregator, critic and verdict nodes. Policy and document tooling from two FastMCP servers over streamable HTTP, with per-node checks and a full audit trail per claim.

**Sentinel Finance.** ReAct agent over five MCP tools (market data, news, sentiment, private-document RAG) with dual input/output guardrails, per-claim source attribution and an audit log.

**Returns and refunds agent.** Red-teamed an unguarded action-taking agent (prompt injection, PII exfiltration, tool poisoning, over-refund), then rebuilt safety as graph architecture: guardrail nodes, DeBERTa-v3, Detoxify, Presidio and server-side caps.

**Clinical data assistant.** Natural-language SQL with LangGraph interrupts: safe reads auto-execute, writes pause for human approval, unsafe queries are rejected, state is checkpointed across the interrupt.

**SCREENDEX.** Text-first OCR and keyframe index replacing raw video frames. Cut multimodal input cost by 75.6% on one frontier model and 82.8% on another at comparable accuracy, with a frozen evaluation harness (EMNLP 2026 Industry Track).

---

## Research

- **EMNLP 2026, Main Conference (CORE A*)**, accepted. *What Does a Language Model Know If It Has Never Seen the Future? Temporal Isolation as a Natural Experiment in Knowledge Attribution.* Co-author.
- **EMNLP 2026, Industry Track (CORE A*)**, accepted. *Cheaper Than Frames: An OCR+Keyframe Index as a Perception Layer for GUI-Video Question Answering.* Co-author.
- **IEEE/ACS AICCSA 2025.** [TextAge: Evaluating Large Language Models for Historical Text Dating](https://doi.org/10.1109/aiccsa66935.2025.11315270). Led the LLM strand: zero-shot and chain-of-thought evaluation, plus LoRA fine-tuning of LLaMA 2 7B and Mistral 7B.
- **MICAD 2025, Springer.** *A Multimodal Deep Learning Framework for Mycetoma Classification: Integrating Vision Transformers, Medical Language Models, and Transfer Learning.* ISBN 978-981-95-7425-4.
- **WikiJournal of Humanities 2025** (sole author, peer-reviewed): [Integrating Generative AI in Wikipedia Classrooms](https://doi.org/10.15347/wjh/2025/edu.13) · [Beyond Basics: Advanced PetScan Techniques for Improving Wikipedia Articles](https://doi.org/10.15347/wjh/2025/edu.23).

Teaching beyond the day job: 8-week agentic AI course at the University of Hertfordshire; guest lectures at the University of Birmingham; AI strategy adviser to Wikimedia UK; AI panel, Wikimania 2026, Paris.

---

## Stack

| Layer | What I use in production |
| --- | --- |
| Agents | LangGraph (state, checkpointers, interrupts), MCP / FastMCP, ReAct, A2A, n8n |
| Retrieval | Chunking strategy, OpenAI and Hugging Face embeddings, ChromaDB, FAISS, metadata filters |
| Evaluation and safety | LLM-as-judge, gold sets, RAGAS, DeepEval, Presidio, DeBERTa-v3, Detoxify, audit logs |
| Models | GPT, Claude, Mistral, LLaMA; LoRA; DSPy and GEPA for prompt optimisation |
| Serve | Python, FastAPI, Docker, GitHub Actions, Cloud Run, AWS, Azure, Vertex AI, air-gapped serving |

---

## Education

**MSc Data Science, High Distinction** (81.4%, top 3 of 150+), University of Birmingham, 2023-2024. Chevening Scholar (UK Government). Elected Best Student Representative, College of Engineering and Physical Sciences.

**BSc Engineering**, An-Najah National University, 2019.
