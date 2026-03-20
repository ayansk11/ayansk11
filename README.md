<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey,%20I'm%20Ayan%20👋&fontSize=42&fontColor=fff&animation=fadeIn&fontAlignY=35" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=8D6EF7&center=true&vCenter=true&repeat=true&random=false&width=800&height=45&lines=Building+intelligent+systems+that+learn%2C+reason%2C+and+adapt!;LLM+%2B+RL+%7C+Agentic+AI+%7C+Cybersecurity;MS+Computer+Science+%40+Indiana+University)](https://github.com/ayansk11)

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayansk11)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Ayansk11)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello.ayansk152@gmail.com)
[![AWS](https://img.shields.io/badge/AWS_Certified-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)](https://cp.certmetrics.com/amazon/en/public/verify/credential/4f1b937babf844b9b2d4a061d8283b3b)

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=1" width="100%" />

## 🔬 What I'm working on

<table>
<tr>
<td>

**Research Assistant — Cybersecurity AI** @ Indiana University, Kelley School of Business

</td>
</tr>
<tr>
<td>

- 🧠 Building a **hierarchical LLM + RL red team adversary** for autonomous penetration testing in the CybORG CAGE Challenge 4 enterprise network (9 subnets, 1 red vs 5 blue defenders + 48 green agents)
- 🎯 Designed a **3-layer reward shaping system** (negated opponent rewards + milestone bonuses + prerequisite penalties) to enable RL training from zero environment signal
- 📊 Evaluated **13 LLMs** (0.6B–70B) across 4 inference backends on NVIDIA H100 GPUs — found that **no LLM achieves meaningful attack success zero-shot**, and model size does not correlate with performance
- ⚙️ PPO with action masking | vLLM | Curriculum learning | SLURM/HPC on Big Red 200
- 📄 Presenting at [**SPIE Defense + Security 2026**](https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28) — April 2026, National Harbor, MD

</td>
</tr>
</table>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=1" width="100%" />

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/Agentic-Cybersec-Threat-Analyst">🛡️ Agentic Cybersec Threat Analyst</a></h3>

3-agent LangGraph pipeline that transforms raw CVEs into defense playbooks — ingests NVD, CISA KEV & OTX feeds, maps threats via hybrid RAG over 19K+ MITRE ATT&CK techniques, and auto-generates Sigma detection rules. FastAPI + React + Qdrant.

`LangGraph` `RAG` `MITRE ATT&CK` `FastAPI` `Qdrant`

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/FinSight">📈 FinSight</a></h3>

Four specialized LangGraph agents (Document, Quantitative, Risk, Synthesis) dissect SEC filings (10-K, 10-Q, 8-K) with hierarchical PageIndex navigation. Local Ollama + Groq cloud fallback. FRED & Finnhub market data. 129 unit + 10 E2E tests.

`LangGraph` `Ollama` `SEC Filings` `Groq` `Finnhub`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/FinSent-CoT">💡 FinSent-CoT</a></h3>

16,944-sample balanced dataset pairing financial texts with expert Chain-of-Thought reasoning distilled from Qwen3-235B on H100 GPUs. SFT + GRPO formats for on-device LLMs (0.5B–8B). Multi-stage QA with 15.5% rejection rate.

`Chain-of-Thought` `GRPO` `SFT` `Qwen3` `H100`

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/FinistralAI_code">🧪 FinistralAI</a></h3>

Mistral-7B fine-tuned for financial sentiment with LoRA adapters (rank 16, alpha 32). BF16 precision, gradient checkpointing & DeepSpeed multi-GPU training. Published on HuggingFace Hub.

`LoRA` `Mistral-7B` `DeepSpeed` `BF16` `HuggingFace`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/ddos-mitigation">🌐 DDoS Mitigation</a></h3>

Three-tier defense-in-depth: XDP/eBPF kernel-level rate limiting (10M pps), P4 BMv2 in-network per-flow detection (1024 flows), and BGP FlowSpec/RTBH upstream blackholing. Tested on Jetstream2 with Mininet + FRR.

`XDP/eBPF` `P4` `BGP FlowSpec` `Mininet` `Jetstream2`

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/Brain-Tumor-Classification-Using-Convolutional-Neural-Network-CNN-">🧬 Brain Tumor Classification</a> ⭐ 8</h3>

CNN classifying brain tumor MRI scans into 4 categories (Glioma, Meningioma, Pituitary, No Tumor) across 7K+ images. End-to-end pipeline from Kaggle download to prediction.

`CNN` `PyTorch` `Medical Imaging` `Kaggle`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/Drug-Typology-Based-on-Clinical-Profiles">💊 Drug Typology Classification</a> ⭐ 8</h3>

Comparative ML study — Logistic Regression, Random Forest, SVM & Voting Ensemble with precision-recall trade-off analysis for minimizing clinical false positives.

`Scikit-learn` `Random Forest` `SVM` `Ensemble`

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/ayansk11/FinEdu.AI">🎓 FinEdu.AI</a> ⭐ 13</h3>

Conversational financial education assistant powered by LLaMA-2-7B with RAG over curated financial terminology. Gradio web UI with beginner-friendly explanations and real-world examples.

`LLaMA-2` `RAG` `Gradio` `Financial NLP`

</td>
</tr>
</table>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=1" width="100%" />

## 💼 Experience

<table>
<tr>
<th>Role</th>
<th>Where</th>
<th>What</th>
</tr>
<tr>
<td><strong>Research Assistant</strong><br><em>Cybersecurity AI</em></td>
<td>Indiana University</td>
<td>Hierarchical LLM+RL red team adversary for CybORG CAGE Challenge 4 — RL controller hit 8x heuristic baseline via custom 3-layer reward shaping; benchmarked 13 LLMs (0.6B–70B) across 4 backends on H100s; ~15K lines of Python; <a href="https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28">SPIE 2026 paper</a></td>
</tr>
<tr>
<td><strong>Research Software Developer</strong></td>
<td>Indiana University</td>
<td>LLM annotation pipeline with Tree-of-Thoughts + Self-Consistency — labeled 167K+ patent abstracts & 22K+ AV disengagement incidents with 7-way classification using OpenAI & Gemini APIs</td>
</tr>
<tr>
<td><strong>Software Developer - AI</strong></td>
<td>OCG Technologies, Singapore</td>
<td>Fine-tuned Llama 2 chatbot with LoRA/PEFT on SageMaker — 83% accuracy boost; RAG with OpenSearch for 75% support overhead reduction</td>
</tr>
<tr>
<td><strong>Software Developer - Data</strong></td>
<td>Visual Labs, Mumbai</td>
<td>3 TB drone imagery ETL pipeline — PySpark + OpenCV preprocessing, AWS Lambda orchestration, DynamoDB storage, Power BI dashboards; 45% stakeholder outcome improvement</td>
</tr>
</table>

<br>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=1" width="100%" />

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat-square&logo=html5&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-5C2D91?style=flat-square&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![W&B](https://img.shields.io/badge/Weights_%26_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

</div>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" />

<div align="center">

*If it can learn, I can build it.*

</div>
