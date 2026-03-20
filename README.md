<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:58a6ff&height=220&section=header&text=Ayan%20Shaikh&fontSize=42&fontColor=ffffff&fontAlignY=30&desc=Building%20intelligent%20systems%20that%20learn,%20reason,%20and%20adapt&descSize=16&descColor=8b949e&descAlignY=52&animation=fadeIn" width="100%" />

<br>

**MS Computer Science**  @  Indiana University, Bloomington

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayansk11)&nbsp;
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Ayansk11)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello.ayansk152@gmail.com)&nbsp;
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)](https://cp.certmetrics.com/amazon/en/public/verify/credential/4f1b937babf844b9b2d4a061d8283b3b)

</div>

<br>

## What I'm Working On

> **Research Assistant — Cybersecurity AI** @ Indiana University, Kelley School of Business

- Building a hierarchical **LLM + RL red team adversary** for autonomous penetration testing in the CybORG CAGE Challenge 4 enterprise network (9 subnets, 1 red vs 5 blue defenders + 48 green agents)
- Designed a **3-layer reward shaping system** (negated opponent rewards + milestone bonuses + prerequisite penalties) to enable RL training from zero environment signal
- Evaluated **13 LLMs** (0.6B–70B) across 4 inference backends on NVIDIA H100 GPUs — found that **no LLM achieves meaningful attack success zero-shot**, and model size does not correlate with performance
- PPO with action masking | vLLM | Curriculum learning | SLURM/HPC on Big Red 200
- Presenting at [**SPIE Defense + Security 2026**](https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28) — April 2026, National Harbor, MD

<br>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/Agentic-Cybersec-Threat-Analyst">Agentic Cybersec Threat Analyst</a></strong></div>
<br>

<sub>3-agent LangGraph pipeline that transforms raw CVEs into defense playbooks — ingests NVD, CISA KEV & OTX feeds, maps threats via hybrid RAG over 19K+ MITRE ATT&CK techniques, and auto-generates Sigma detection rules. FastAPI + React + Qdrant.</sub>

<br>

`LangGraph` `RAG` `MITRE ATT&CK` `FastAPI` `Qdrant`

</td>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/FinSight">FinSight</a></strong></div>
<br>

<sub>Four specialized LangGraph agents (Document, Quantitative, Risk, Synthesis) dissect SEC filings (10-K, 10-Q, 8-K) with hierarchical PageIndex navigation. Local Ollama + Groq cloud fallback. FRED & Finnhub market data. 129 unit + 10 E2E tests.</sub>

<br>

`LangGraph` `Ollama` `SEC Filings` `Groq` `Finnhub`

</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/FinSent-CoT">FinSent-CoT</a></strong></div>
<br>

<sub>16,944-sample balanced dataset pairing financial texts with expert Chain-of-Thought reasoning distilled from Qwen3-235B on H100 GPUs. SFT + GRPO formats for on-device LLMs (0.5B–8B). Multi-stage QA with 15.5% rejection rate.</sub>

<br>

`Qwen3-235B` `SFT` `GRPO` `H100` `Chain-of-Thought`

</td>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/FinistralAI_code">FinistralAI</a></strong></div>
<br>

<sub>Mistral-7B fine-tuned for financial sentiment with LoRA adapters (rank 16, alpha 32). BF16 precision, gradient checkpointing & DeepSpeed multi-GPU training. Published on HuggingFace Hub.</sub>

<br>

`Mistral-7B` `LoRA` `DeepSpeed` `BF16` `HuggingFace`

</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/ddos-mitigation">DDoS Mitigation</a></strong></div>
<br>

<sub>Three-tier defense-in-depth: XDP/eBPF kernel-level rate limiting (10M pps), P4 BMv2 in-network per-flow detection (1024 flows), and BGP FlowSpec/RTBH upstream blackholing. Tested on Jetstream2 with Mininet + FRR.</sub>

<br>

`XDP/eBPF` `P4` `BGP FlowSpec` `Mininet` `Jetstream2`

</td>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/Brain-Tumor-Classification-Using-Convolutional-Neural-Network-CNN-">Brain Tumor Classification</a></strong> ★ 8</div>
<br>

<sub>CNN classifying brain tumor MRI scans into 4 categories (Glioma, Meningioma, Pituitary, No Tumor) across 7K+ images. End-to-end pipeline from Kaggle download to prediction.</sub>

<br>

`CNN` `TensorFlow` `Medical Imaging` `Kaggle`

</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/Drug-Typology-Based-on-Clinical-Profiles">Drug Typology Classification</a></strong> ★ 8</div>
<br>

<sub>Comparative ML study — Logistic Regression, Random Forest, SVM & Voting Ensemble with precision-recall trade-off analysis for minimizing clinical false positives.</sub>

<br>

`Scikit-learn` `Random Forest` `SVM` `Clinical ML`

</td>
<td width="50%" valign="top">
<br>

<div align="center"><strong><a href="https://github.com/ayansk11/FinEdu.AI">FinEdu.AI</a></strong> ★ 13</div>
<br>

<sub>Conversational financial education assistant powered by LLaMA-2-7B with RAG over curated financial terminology. Gradio web UI with beginner-friendly explanations and real-world examples.</sub>

<br>

`LLaMA-2` `RAG` `Gradio` `Financial NLP`

</td>
</tr>
</table>

<br>

## Experience

<table>
<tr>
<td width="30%"><strong>Research Assistant</strong><br><sub>Cybersecurity AI · Indiana University</sub></td>
<td>Hierarchical LLM+RL red team adversary for CybORG CAGE Challenge 4 — RL controller hit <strong>8x heuristic baseline</strong> via custom 3-layer reward shaping; benchmarked 13 LLMs (0.6B–70B) across 4 backends on H100s; ~15K lines of Python · <a href="https://spie.org/defense-security/presentation/Red-teaming-framework-for-evaluating-robustness-of-AI-enabled-security/14046-28">SPIE 2026 paper</a></td>
</tr>
<tr>
<td><strong>Research Software Developer</strong><br><sub>Indiana University</sub></td>
<td>LLM annotation pipeline with Tree-of-Thoughts + Self-Consistency — labeled <strong>167K+ patent abstracts</strong> & <strong>22K+ AV disengagement incidents</strong> with 7-way classification using OpenAI & Gemini APIs</td>
</tr>
<tr>
<td><strong>Software Developer — AI</strong><br><sub>OCG Technologies, Singapore</sub></td>
<td>Fine-tuned Llama 2 chatbot with LoRA/PEFT on SageMaker — <strong>83% accuracy boost</strong>; RAG with OpenSearch for <strong>75% support overhead reduction</strong></td>
</tr>
<tr>
<td><strong>Software Developer — Data</strong><br><sub>Visual Labs, Mumbai</sub></td>
<td>3 TB drone imagery ETL pipeline — PySpark + OpenCV preprocessing, AWS Lambda orchestration, DynamoDB storage, Power BI dashboards; <strong>45% stakeholder outcome improvement</strong></td>
</tr>
</table>

<br>

## Tech Stack

<table>
<tr>
<td><strong>Languages</strong></td>
<td><code>Python</code> <code>C</code> <code>P4</code> <code>SQL</code> <code>JavaScript</code> <code>HTML/CSS</code></td>
</tr>
<tr>
<td><strong>ML / DL</strong></td>
<td><code>PyTorch</code> <code>PPO</code> <code>GRPO</code> <code>CNNs</code> <code>Transformers</code> <code>Curriculum Learning</code></td>
</tr>
<tr>
<td><strong>LLMs</strong></td>
<td><code>vLLM</code> <code>LoRA/QLoRA/PEFT</code> <code>RAG</code> <code>LangGraph</code> <code>Ollama</code> <code>llama.cpp</code> <code>OpenAI API</code> <code>Gemini API</code></td>
</tr>
<tr>
<td><strong>Infra</strong></td>
<td><code>AWS</code> <code>SageMaker</code> <code>Lambda</code> <code>S3</code> <code>DynamoDB</code> <code>OpenSearch</code> <code>SLURM/HPC (H100)</code> <code>Docker</code></td>
</tr>
<tr>
<td><strong>Data</strong></td>
<td><code>PySpark</code> <code>Pandas</code> <code>NumPy</code> <code>OpenCV</code> <code>Power BI</code> <code>BeautifulSoup</code></td>
</tr>
<tr>
<td><strong>Tools</strong></td>
<td><code>Git</code> <code>Weights & Biases</code> <code>pytest</code> <code>Unsloth</code> <code>HuggingFace Hub</code></td>
</tr>
</table>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:58a6ff&height=100&section=footer" width="100%" />

*If it can learn, I can build it.*

</div>
