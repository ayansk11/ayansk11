<div align="center">

# Ayan Shaikh

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=16&duration=3000&pause=1500&color=58A6FF&center=true&vCenter=true&repeat=true&width=600&height=30&lines=building+intelligent+systems+that+learn%2C+reason%2C+and+adapt)](https://github.com/ayansk11)

MS Computer Science · Indiana University, Bloomington

[linkedin](https://www.linkedin.com/in/ayansk11) · [huggingface](https://huggingface.co/Ayansk11) · [email](mailto:hello.ayansk152@gmail.com) · [aws certified](https://cp.certmetrics.com/amazon/en/public/verify/credential/4f1b937babf844b9b2d4a061d8283b3b)

</div>

---

### current work

**Research Assistant — Cybersecurity AI** · Indiana University, Kelley School of Business

> Building a hierarchical **LLM + RL red team adversary** for autonomous penetration testing on the CybORG CAGE Challenge 4 enterprise network — 9 subnets, 1 red agent vs 5 blue defenders + 48 green agents.

- Designed a **3-layer reward shaping system** (negated opponent rewards + milestone bonuses + prerequisite penalties) to train RL from zero environment signal
- Evaluated **13 LLMs** (0.6B–70B) across 4 inference backends on NVIDIA H100 GPUs — **no LLM achieves meaningful attack success zero-shot**, model size does not correlate with performance
- PPO with action masking · vLLM · curriculum learning · SLURM/HPC on Big Red 200
- Presenting at [SPIE Defense + Security 2026](https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28) — April 2026, National Harbor, MD

---

### projects

| | |
|---|---|
| **[Agentic Cybersec Threat Analyst](https://github.com/ayansk11/Agentic-Cybersec-Threat-Analyst)** | 3-agent LangGraph pipeline — transforms raw CVEs into defense playbooks. Ingests NVD, CISA KEV & OTX feeds, maps threats via hybrid RAG over 19K+ MITRE ATT&CK techniques, auto-generates Sigma detection rules. `langgraph · rag · mitre att&ck · fastapi · qdrant` |
| **[FinSight](https://github.com/ayansk11/FinSight)** | Four specialized LangGraph agents (Document, Quantitative, Risk, Synthesis) dissect SEC filings with hierarchical PageIndex navigation. Local Ollama + Groq cloud fallback. FRED & Finnhub market data. 129 unit + 10 E2E tests. `langgraph · ollama · groq · finnhub` |
| **[FinSent-CoT](https://github.com/ayansk11/FinSent-CoT)** | 16,944-sample balanced dataset — financial texts paired with expert Chain-of-Thought reasoning distilled from Qwen3-235B on H100 GPUs. SFT + GRPO formats for on-device LLMs (0.5B–8B). 15.5% rejection rate via multi-stage QA. `chain-of-thought · grpo · sft · qwen3` |
| **[FinistralAI](https://github.com/ayansk11/FinistralAI_code)** | Mistral-7B fine-tuned for financial sentiment with LoRA adapters (rank 16, alpha 32). BF16 precision, gradient checkpointing & DeepSpeed multi-GPU training. Published on HuggingFace Hub. `lora · mistral-7b · deepspeed · bf16` |
| **[DDoS Mitigation](https://github.com/ayansk11/ddos-mitigation)** | Three-tier defense-in-depth — XDP/eBPF kernel-level rate limiting (10M pps), P4 BMv2 in-network per-flow detection (1024 flows), BGP FlowSpec/RTBH upstream blackholing. Tested on Jetstream2 with Mininet + FRR. `xdp/ebpf · p4 · bgp flowspec · mininet` |
| **[Brain Tumor Classification](https://github.com/ayansk11/Brain-Tumor-Classification-Using-Convolutional-Neural-Network-CNN-)** ★ 8 | CNN classifying brain tumor MRI scans into 4 categories (Glioma, Meningioma, Pituitary, No Tumor) across 7K+ images. End-to-end pipeline from Kaggle download to prediction. `cnn · pytorch · medical imaging` |
| **[Drug Typology Classification](https://github.com/ayansk11/Drug-Typology-Based-on-Clinical-Profiles)** ★ 8 | Comparative ML study — Logistic Regression, Random Forest, SVM & Voting Ensemble with precision-recall trade-off analysis for minimizing clinical false positives. `scikit-learn · random forest · svm` |
| **[FinEdu.AI](https://github.com/ayansk11/FinEdu.AI)** ★ 13 | Conversational financial education assistant powered by LLaMA-2-7B with RAG over curated financial terminology. Gradio web UI with beginner-friendly explanations and real-world examples. `llama-2 · rag · gradio` |

---

### experience

```
Research Assistant (Cybersecurity AI)    Indiana University
  Hierarchical LLM+RL red team adversary for CybORG CAGE Challenge 4
  RL controller hit 8x heuristic baseline · 3-layer reward shaping
  13 LLMs benchmarked across 4 backends on H100s · ~15K lines of Python
  → SPIE Defense + Security 2026 paper

Research Software Developer              Indiana University
  LLM annotation pipeline · Tree-of-Thoughts + Self-Consistency
  167K+ patent abstracts & 22K+ AV incidents · 7-way classification
  OpenAI & Gemini APIs

Software Developer - AI                  OCG Technologies, Singapore
  Llama 2 chatbot · LoRA/PEFT fine-tuning on SageMaker
  83% accuracy boost · RAG with OpenSearch · 75% support overhead reduction

Software Developer - Data                Visual Labs, Mumbai
  3 TB drone imagery ETL · PySpark + OpenCV preprocessing
  AWS Lambda · DynamoDB · Power BI · 45% stakeholder outcome improvement
```

---

### stack

```
languages       python · c · p4 · sql · javascript
ml/dl           pytorch · ppo · grpo · cnns · transformers · curriculum learning
llms            vllm · lora/qlora/peft · rag · langgraph · ollama · llama.cpp
infra           aws (sagemaker, lambda, s3, dynamodb, opensearch) · slurm/hpc (h100) · docker
data            pyspark · pandas · numpy · opencv · power bi
tools           git · weights & biases · pytest · unsloth · huggingface hub
```

---

<div align="center">

*if it can learn, i can build it.*

</div>
