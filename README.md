## Hi there 👋

I build end-to-end AI systems — agentic pipelines, browser agents, and ML infrastructure.

#### Agentic Systems
**[Financial Agentic RAG](https://github.com/Jbb-525/Agentic-RAG-chatbot-for-Financial-Report-QA)** — LangGraph agent routing financial report queries across Qdrant vector search and SQLite, with CRAG-style relevance loops and SSE streaming to a React frontend.

**[VoiceNav](https://github.com/Jbb-525/voicenav)** — LLM browser automation agent with Text vs Vision planner ablation (+17pp task success), two-layer failure attribution, and CDP-based live browser streaming.

#### Research
**[Web World Model](https://github.com/Jbb-525/webworldmodel)** — RL training system for web navigation agents. SFT + GRPO on Qwen2.5-3B on 2×A100 with vLLM rollout serving, 150K synthetic samples — +44% over CoT, 4.4× faster than Tree Search. 

**[Spatial VLM Investigator](https://github.com/Yvonne511/spatial-vlm-investigator)** — Spatial reasoning in VLMs via CoT and RL fine-tuning. GRPO beats SFT on OOD generalization (3.17% vs 12.03% ID-OOD gap).

**[Academic Knowledge Graph](https://github.com/Jbb-525/Construction-of-Academic-Knowledge-Graph-for-Semantic-Retrieval)** — End-to-end KG pipeline: crawling → ontology construction → BERT+BiLSTM+CRF NER → Neo4j → semantic retrieval.

#### Knowledge & Infrastructure
**[ML Inference on Kubernetes](https://github.com/Jbb-525/k8s-project)** — PyTorch training Job + inference Deployment on GKE, shared PersistentVolume, liveness/readiness probes, LoadBalancer REST API.
