<div align="center">

# Hey, I'm Ayan 👋

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&duration=3000&pause=2000&color=58A6FF&center=true&vCenter=true&repeat=true&width=750&height=30&lines=Building+intelligent+systems+that+learn%2C+reason%2C+and+adapt!)](https://github.com/ayansk11)

**MS Computer Science** · Indiana University, Bloomington

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayansk11) &nbsp;
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/Ayansk11) &nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hello.ayansk152@gmail.com) &nbsp;
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-232F3E?style=flat&logo=amazonwebservices&logoColor=white)](https://cp.certmetrics.com/amazon/en/public/verify/credential/4f1b937babf844b9b2d4a061d8283b3b)

</div>

---

### What I'm Working On

**Research Assistant — Cybersecurity AI** · Indiana University, Kelley School of Business

- Building a hierarchical **LLM + RL red team adversary** for autonomous penetration testing in the CybORG CAGE Challenge 4 enterprise network (9 subnets, 1 red vs 5 blue defenders + 48 green agents)
- Designed a **3-layer reward shaping system** (negated opponent rewards + milestone bonuses + prerequisite penalties) to enable RL training from zero environment signal
- Evaluated **13 LLMs** (0.6B–70B) across 4 inference backends on NVIDIA H100 GPUs — found that **no LLM achieves meaningful attack success zero-shot**, and model size does not correlate with performance
- PPO with action masking | vLLM | Curriculum learning | SLURM/HPC on Big Red 200
- Presenting at [**SPIE Defense + Security 2026**](https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28) — April 2026, National Harbor, MD

---

### Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[Agentic Cybersec Threat Analyst](https://github.com/ayansk11/Agentic-Cybersec-Threat-Analyst)**

3-agent LangGraph pipeline that transforms raw CVEs into defense playbooks — ingests NVD, CISA KEV & OTX feeds, maps threats via hybrid RAG over 19K+ MITRE ATT&CK techniques, and auto-generates Sigma detection rules. FastAPI + React + Qdrant.

</td>
<td width="50%" valign="top">

**[FinSight](https://github.com/ayansk11/FinSight)**

Four specialized LangGraph agents (Document, Quantitative, Risk, Synthesis) dissect SEC filings (10-K, 10-Q, 8-K) with hierarchical PageIndex navigation. Local Ollama + Groq cloud fallback. FRED & Finnhub market data. 129 unit + 10 E2E tests.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[FinSent-CoT](https://github.com/ayansk11/FinSent-CoT)**

16,944-sample balanced dataset pairing financial texts with expert Chain-of-Thought reasoning distilled from Qwen3-235B on H100 GPUs. SFT + GRPO formats for on-device LLMs (0.5B–8B). Multi-stage QA with 15.5% rejection rate.

</td>
<td width="50%" valign="top">

**[FinistralAI](https://github.com/ayansk11/FinistralAI_code)**

Mistral-7B fine-tuned for financial sentiment with LoRA adapters (rank 16, alpha 32). BF16 precision, gradient checkpointing & DeepSpeed multi-GPU training. Published on HuggingFace Hub.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[DDoS Mitigation](https://github.com/ayansk11/ddos-mitigation)**

Three-tier defense-in-depth: XDP/eBPF kernel-level rate limiting (10M pps), P4 BMv2 in-network per-flow detection (1024 flows), and BGP FlowSpec/RTBH upstream blackholing. Tested on Jetstream2 with Mininet + FRR.

</td>
<td width="50%" valign="top">

**[Brain Tumor Classification (CNN)](https://github.com/ayansk11/Brain-Tumor-Classification-Using-Convolutional-Neural-Network-CNN-)** ⭐ 8

CNN classifying brain tumor MRI scans into 4 categories (Glioma, Meningioma, Pituitary, No Tumor) across 7K+ images. End-to-end pipeline from Kaggle download to prediction.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[Drug Typology Classification](https://github.com/ayansk11/Drug-Typology-Based-on-Clinical-Profiles)** ⭐ 8

Comparative ML study — Logistic Regression, Random Forest, SVM & Voting Ensemble with precision-recall trade-off analysis for minimizing clinical false positives.

</td>
<td width="50%" valign="top">

**[FinEdu.AI](https://github.com/ayansk11/FinEdu.AI)** ⭐ 13

Conversational financial education assistant powered by LLaMA-2-7B with RAG over curated financial terminology. Gradio web UI with beginner-friendly explanations and real-world examples.

</td>
</tr>
</table>

---

### Experience

<table>
<tr>
<td width="30%"><strong>Research Assistant</strong><br><sub>Cybersecurity AI</sub></td>
<td width="20%">Indiana University</td>
<td>Hierarchical LLM+RL red team adversary for CybORG CAGE Challenge 4 — RL controller hit <strong>8x heuristic baseline</strong> via custom 3-layer reward shaping; benchmarked 13 LLMs (0.6B–70B) across 4 backends on H100s; ~15K lines of Python · <a href="https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28">SPIE 2026 paper</a></td>
</tr>
<tr>
<td><strong>Research Software Developer</strong></td>
<td>Indiana University</td>
<td>LLM annotation pipeline with Tree-of-Thoughts + Self-Consistency — labeled <strong>167K+ patent abstracts</strong> & <strong>22K+ AV disengagement incidents</strong> with 7-way classification using OpenAI & Gemini APIs</td>
</tr>
<tr>
<td><strong>Software Developer — AI</strong></td>
<td>OCG Technologies, Singapore</td>
<td>Fine-tuned Llama 2 chatbot with LoRA/PEFT on SageMaker — <strong>83% accuracy boost</strong>; RAG with OpenSearch for <strong>75% support overhead reduction</strong></td>
</tr>
<tr>
<td><strong>Software Developer — Data</strong></td>
<td>Visual Labs, Mumbai</td>
<td>3 TB drone imagery ETL pipeline — PySpark + OpenCV preprocessing, AWS Lambda orchestration, DynamoDB storage, Power BI dashboards; <strong>45% stakeholder outcome improvement</strong></td>
</tr>
</table>

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
