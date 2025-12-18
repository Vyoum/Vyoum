                                                   # Hey, I'm Vyoum

<div align="center">
  <h3>AI Engineer • Backend Architect • RAG + Agentic Systems</h3>
  <p>Turning LLM ideas into production systems with Spring Boot backends, MERN control surfaces, and reliable data pipelines.</p>
  <br>
  <img src="https://img.shields.io/badge/Focus-Production_RAG-orange?style=for-the-badge&logo=openai">
  <img src="https://img.shields.io/badge/Builds-Agentic_Workflows-8A2BE2?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Architect-Scalable_APIs-0b7285?style=for-the-badge&logo=springboot">
</div>

---

### 🚀 Snapshot
- Design and ship end-to-end RAG pipelines (chunking, retrievers, evaluators, guardrails).
- Build agentic AI that orchestrates tools, context, and APIs with predictable outcomes.
- Architect Java/Spring Boot services built for throughput, observability, and scale.
- Deliver MERN interfaces for ops dashboards, evaluators, and human-in-the-loop flows.
- Prototype fast with Python (NumPy/SciPy/matplotlib/seaborn) and harden hot paths in C++ when needed.

### 🛠️ Tech I Ship With
**Languages**  
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">

**Backend & APIs**  
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"> <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white">

**Frontend & Data Stores**  
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white">

**AI / Data**  
<img src="https://img.shields.io/badge/RAG_Pipelines-0f9d58?style=for-the-badge&logo=openai&logoColor=white"> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"> <img src="https://img.shields.io/badge/matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white"> <img src="https://img.shields.io/badge/seaborn-4c8cb5?style=for-the-badge">

### 🔬 RAG & Agentic Playbook
- Retrieval built for signal: smart chunking, embeddings tuned to domain language, and hybrid search when it wins.
- Tool-using agents over noisy data: deterministic planners, tool catalogs, and safe fallbacks.
- Evaluation loops that measure hallucination, grounding, and latency before anything ships.
- APIs that stay fast: caching, async pipelines, and tight JVM profiling when performance matters.

### 🧭 How I Work
- Shape fast with Python notebooks, then graduate pieces into Spring Boot or Node microservices.
- Keep ops-friendly: logs, metrics, traces, and docs that make handoffs painless.
- Bias toward automation for data curation, eval suites, and regression checks.

### 🎯 Current Focus
- Hardening Spring Boot services for AI workloads (rate-limited, observable, horizontally scalable).
- Building evaluation dashboards with React/Node for human-in-the-loop review.
- Experimenting with agent handoffs between Python orchestration and JVM services.

### 🧪 Mini Build (RAG sketch)
```python
from rag_pipeline import Pipeline  # pseudo interface

pipeline = (
    Pipeline()
    .chunk(strategy="semantic", overlap=64)
    .embed(model="domain-bert")
    .retrieve(top_k=10, hybrid=True)
    .ground(model="gpt-4o-mini", guardrails=True)
    .evaluate(metrics=["faithfulness", "latency"])
)

response = pipeline.answer("How do we roll out the new API?")
print(response.text)
```
