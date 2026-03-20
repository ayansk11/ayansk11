<div align="center">

# Hey, I'm Ayan 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=8D6EF7&center=true&vCenter=true&repeat=false&random=false&width=750&height=35&lines=Building+intelligent+systems+that+learn%2C+reason%2C+and+adapt!)](https://github.com/ayansk11)

**MS Computer Science @ Indiana University, Bloomington**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayansk11)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/Ayansk11)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hello.ayansk152@gmail.com)
[![AWS](https://img.shields.io/badge/AWS_Certified_AI_Practitioner-232F3E?style=flat&logo=amazonwebservices&logoColor=white)](https://cp.certmetrics.com/amazon/en/public/verify/credential/4f1b937babf844b9b2d4a061d8283b3b)

</div>

---

### What I'm working on

**Research Assistant - Cybersecurity AI** @ Indiana University, Kelley School of Business
- Building a **hierarchical LLM + RL red team adversary** for autonomous penetration testing in the CybORG CAGE Challenge 4 enterprise network (9 subnets, 1 red vs 5 blue defenders + 48 green agents)
- Designed a **3-layer reward shaping system** (negated opponent rewards + milestone bonuses + prerequisite penalties) to enable RL training from zero environment signal
- Evaluated **13 LLMs** (0.6B–70B) across 4 inference backends on NVIDIA H100 GPUs — found that **no LLM achieves meaningful attack success zero-shot**, and model size does not correlate with performance
- PPO with action masking | vLLM | Curriculum learning | SLURM/HPC on Big Red 200
- Presenting at [**SPIE Defense + Security 2026**](https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28) — April 2026, National Harbor, MD

---

### Featured Projects

<table>
<tr>
<td width="50%">

**[Agentic Cybersec Threat Analyst](https://github.com/ayansk11/Agentic-Cybersec-Threat-Analyst)**
<br>3-agent LangGraph pipeline that transforms raw CVEs into defense playbooks - ingests NVD, CISA KEV & OTX feeds, maps threats via hybrid RAG over 19K+ MITRE ATT&CK techniques, and auto-generates Sigma detection rules. FastAPI + React + Qdrant.

**[FinSent-CoT](https://github.com/ayansk11/FinSent-CoT)**
<br>16,944-sample balanced dataset pairing financial texts with expert Chain-of-Thought reasoning distilled from Qwen3-235B on H100 GPUs. SFT + GRPO formats for on-device LLMs (0.5B–8B). Multi-stage QA with 15.5% rejection rate.

**[DDoS Mitigation](https://github.com/ayansk11/ddos-mitigation)**
<br>Three-tier defense-in-depth: XDP/eBPF kernel-level rate limiting (10M pps), P4 BMv2 in-network per-flow detection (1024 flows), and BGP FlowSpec/RTBH upstream blackholing. Tested on Jetstream2 with Mininet + FRR.

**[Drug Typology Classification](https://github.com/ayansk11/Drug-Typology-Based-on-Clinical-Profiles)** ⭐ 8
<br>Comparative ML study - Logistic Regression, Random Forest, SVM & Voting Ensemble with precision-recall trade-off analysis for minimizing clinical false positives.

</td>
<td width="50%">

**[FinSight](https://github.com/ayansk11/FinSight)**
<br>Four specialized LangGraph agents (Document, Quantitative, Risk, Synthesis) dissect SEC filings (10-K, 10-Q, 8-K) with hierarchical PageIndex navigation. Local Ollama + Groq cloud fallback. FRED & Finnhub market data. 129 unit + 10 E2E tests.

**[FinistralAI](https://github.com/ayansk11/FinistralAI_code)**
<br>Mistral-7B fine-tuned for financial sentiment with LoRA adapters (rank 16, alpha 32). BF16 precision, gradient checkpointing & DeepSpeed multi-GPU training. Published on HuggingFace Hub.

**[Brain Tumor Classification (CNN)](https://github.com/ayansk11/Brain-Tumor-Classification-Using-Convolutional-Neural-Network-CNN-)** ⭐ 8
<br>CNN classifying brain tumor MRI scans into 4 categories (Glioma, Meningioma, Pituitary, No Tumor) across 7K+ images. End-to-end pipeline from Kaggle download to prediction.

**[FinEdu.AI](https://github.com/ayansk11/FinEdu.AI)** ⭐ 13
<br>Conversational financial education assistant powered by LLaMA-2-7B with RAG over curated financial terminology. Gradio web UI with beginner-friendly explanations and real-world examples.

</td>
</tr>
</table>

---

### Experience

| Role | Where | What |
|------|-------|------|
| **Research Assistant** (Cybersecurity AI) | Indiana University | Hierarchical LLM+RL red team adversary for CybORG CAGE Challenge 4 — RL controller hit 8x heuristic baseline via custom 3-layer reward shaping; benchmarked 13 LLMs (0.6B - 70B) across 4 backends on H100s; [SPIE 2026 paper](https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28) |
| **Research Software Developer** | Indiana University | LLM annotation pipeline with Tree-of-Thoughts + Self-Consistency — labeled 167K+ patent abstracts & 22K+ AV disengagement incidents with 7-way classification using OpenAI & Gemini APIs |
| **Software Developer - AI** | OCG Technologies, Singapore | Fine-tuned Llama 2 chatbot with LoRA/PEFT on SageMaker — 83% accuracy boost; RAG with OpenSearch for 75% support overhead reduction |
| **Software Developer - Data** | Visual Labs, Mumbai | 3 TB drone imagery ETL pipeline — PySpark + OpenCV preprocessing, AWS Lambda orchestration, DynamoDB storage, Power BI dashboards; 45% stakeholder outcome improvement |

---

### Tech Stack

```text
Languages       Python, C, P4, SQL, JavaScript, HTML/CSS
ML/DL           PyTorch, PPO, GRPO, CNNs, Transformers, Curriculum Learning
LLMs            vLLM, LoRA/QLoRA/PEFT, RAG, LangGraph, Ollama, llama.cpp, OpenAI API, Gemini API
Infra           AWS (SageMaker, Lambda, S3, DynamoDB, OpenSearch), SLURM/HPC (H100), Docker
Data            PySpark, Pandas, NumPy, OpenCV, Power BI, BeautifulSoup
Tools           Git, Weights & Biases, pytest, Unsloth, HuggingFace Hub
```

---

<div align="center">

*If it can learn, I can build it.*

</div>
