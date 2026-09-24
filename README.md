<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:58a6ff&height=220&section=header&text=Ayan%20Shaikh&fontSize=42&fontColor=ffffff&fontAlignY=30&desc=Building%20intelligent%20systems%20that%20learn,%20reason,%20and%20adapt&descSize=16&descColor=8b949e&descAlignY=52&animation=fadeIn" width="100%" />

<br>

**Machine Learning Engineer** @ Indiana University, Kelley School of Business &nbsp;·&nbsp; **MS Computer Science '26**, Indiana University Bloomington

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayansk11)&nbsp;
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Ayansk11)&nbsp;
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=RFA2ubwAAAAJ)&nbsp;
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello.ayansk152@gmail.com)&nbsp;
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)](https://cp.certmetrics.com/amazon/en/public/verify/credential/4f1b937babf844b9b2d4a061d8283b3b)

</div>

<br>

<div align="center">

## What I'm Working On

</div>

> **Machine Learning Engineer — Security & Defense Research Group** @ Indiana University, Kelley School of Business

- **Hierarchical LLM + RL red teaming** (published, [SPIE 14046](https://doi.org/10.1117/12.3094223)): a frozen LLM planner plus a PPO controller with kill-chain reward shaping attacks the H-MARL Expert defender in CybORG CAGE Challenge 4 — **100% episode compromise (200/200)** vs **30%** for the best of 14 standalone LLMs and **0%** for RL alone; Reflexion memory keeps 99.5% success with **85% fewer attack actions** (3,559 → 541)
- **Cross-environment planner–executor study** (accepted, IEEE MILCOM 2026 Workshops): RL+RL vs LLM+LLM hierarchical red agents across CAGE 4 and Cyberwheel at 100 and 1010 hosts — 18 configurations, 3,600 episodes, and an environment-dependent inversion (RL wins compact, densely rewarded networks; a cyber-pretrained LLM wins the 1010-host network where RL stalls at privilege escalation)
- **Now:** porting the trained red agent from simulation to a DoD-grade network emulation, and rebuilding FinSenti (v2) across a 17-model ladder with SFT + DAPO/Dr.GRPO
- PPO with action masking | vLLM | Curriculum learning | SLURM/HPC on Big Red 200 and Quartz (H100 / A100)

<br>

<div align="center">

## Publications

</div>

- **Shaikh, A. J.**, Bastian, N. D., Shah, A. [A Red Teaming Framework for Evaluating Robustness of AI-enabled Security Orchestration, Automation, and Response Systems](https://doi.org/10.1117/12.3094223). *Proc. SPIE 14046*, 140460R, 2026. [arXiv:2605.17075](https://arxiv.org/abs/2605.17075)
- **Shaikh, A. J.**, Sinha, A., Bastian, N. D., Shah, A. No One Architecture Fits All: A Cross-Environment Evaluation of Hierarchical Red Team Agents. *IEEE MILCOM 2026 Workshops*, accepted (Oct 2026)
- **Shaikh, A. J.**, Parkar, F. J., Khan, A. Q. A. R., Mirza, Z. [Finistral AI: An Efficient Financial-Sentiment LoRA Adapter and a Train/Test Contamination Case Study](https://doi.org/10.64189/ict.26314). *J. Inf. Commun. Technol. Algorithms Syst. Appl.*, 2(3), 26314, 2026

<br>

<div align="center">

## Featured Projects

</div>

<table>
<tr>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/Agentic-Cybersec-Threat-Analyst">Agentic Cybersec Threat Analyst</a></strong>
<br><br>
<p>3-agent LangGraph pipeline that transforms raw CVEs into defense playbooks - ingests NVD, CISA KEV & OTX feeds, maps threats via hybrid RAG over 19K+ MITRE ATT&CK chunks, and auto-generates NIST playbooks and Sigma detection rules. FastAPI + React 19 + Qdrant, 83 tests.</p>
<p><code>LangGraph</code> <code>RAG</code> <code>MITRE ATT&CK</code> <code>FastAPI</code> <code>Qdrant</code></p>
</div>
</td>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/FinSight">FinSight</a></strong>
<br><br>
<p>Four specialized LangGraph agents (Document, Quantitative, Risk, Synthesis) dissect SEC filings (10-K, 10-Q, 8-K) with hierarchical PageIndex navigation. Local Ollama + Groq cloud fallback. FRED & Finnhub market data. 129 unit + 10 E2E tests.</p>
<p><code>LangGraph</code> <code>Ollama</code> <code>SEC Filings</code> <code>Groq</code> <code>Finnhub</code></p>
</div>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/FinSent-CoT">FinSenti / FinSent-CoT</a></strong>
<br><br>
<p>16,944-sample balanced dataset pairing financial texts with Chain-of-Thought rationales distilled from Qwen3-235B on H100s, plus 16 student models (10M–9B) fine-tuned with SFT + GRPO and released as 33 HuggingFace repos. 91.6% held-out accuracy at 8B, 85.4% at 0.8B.</p>
<p><code>Qwen3-235B</code> <code>SFT</code> <code>GRPO</code> <code>Unsloth</code> <code>H100</code></p>
</div>
</td>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/FinistralAI_code">FinistralAI</a></strong>
<br><br>
<p>Mistral-7B LoRA adapter for financial sentiment (41.9M trainable params, 0.58%) and a published train/test contamination case study: a 75.2% overlap audit, a rebuilt evaluation harness, and decontaminated results with McNemar tests and bootstrap CIs.</p>
<p><code>Mistral-7B</code> <code>LoRA</code> <code>Evaluation</code> <code>Statistics</code> <code>HuggingFace</code></p>
</div>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/bt-ml">bt-ml</a></strong> · Luddy Hackathon, 3rd place
<br><br>
<p>LightGBM residual model that learns Bloomington Transit's ETA bias from live GTFS-Realtime feeds: 50.2 s MAE vs BT's 82.3 s (39% better) on 78K matched predictions with trip-grouped CV. Dockerised FastAPI service on Railway; dataset and model on HuggingFace.</p>
<p><code>LightGBM</code> <code>GTFS-Realtime</code> <code>FastAPI</code> <code>Railway</code></p>
</div>
</td>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/MindFlyer">MindFlyer</a></strong> · <a href="https://mindflyer.vercel.app/">live</a>
<br><br>
<p>AI mental-wellness companion: FastAPI proxy over Claude for thought classification and CBT reframing, Vapi + Deepgram live voice, Hume AI emotion detection, Supermemory per-user memory, Firebase auth, and a parallel crisis-detection path routing to 988.</p>
<p><code>Claude API</code> <code>FastAPI</code> <code>React</code> <code>Deepgram</code> <code>Hume AI</code></p>
</div>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/ddos-mitigation">DDoS Mitigation</a></strong>
<br><br>
<p>Three-tier defense-in-depth: XDP/eBPF kernel-level rate limiting (10M pps), P4 BMv2 in-network per-flow detection (1024 flows), and BGP FlowSpec/RTBH upstream blackholing. Tested on Jetstream2 with Mininet + FRR.</p>
<p><code>XDP/eBPF</code> <code>P4</code> <code>BGP FlowSpec</code> <code>Mininet</code> <code>Jetstream2</code></p>
</div>
</td>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/FinEdu.AI">FinEdu.AI</a></strong> ★ 11
<br><br>
<p>Conversational financial education assistant powered by LLaMA-2-7B with RAG over curated financial terminology. Gradio web UI with beginner-friendly explanations and real-world examples.</p>
<p><code>LLaMA-2</code> <code>RAG</code> <code>Gradio</code> <code>Financial NLP</code></p>
</div>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/Brain-Tumor-Classification-Using-Convolutional-Neural-Network-CNN-">Brain Tumor Classification</a></strong> ★ 8
<br><br>
<p>CNN classifying brain tumor MRI scans into 4 categories (Glioma, Meningioma, Pituitary, No Tumor) across 7K+ images. End-to-end pipeline from Kaggle download to prediction.</p>
<p><code>CNN</code> <code>TensorFlow</code> <code>Medical Imaging</code> <code>Kaggle</code></p>
</div>
</td>
<td width="50%" valign="top">
<br>
<div align="center">
<strong><a href="https://github.com/ayansk11/Drug-Typology-Based-on-Clinical-Profiles">Drug Typology Classification</a></strong> ★ 8
<br><br>
<p>Comparative ML study - Logistic Regression, Random Forest, SVM & Voting Ensemble with precision-recall trade-off analysis for minimizing clinical false positives.</p>
<p><code>Scikit-learn</code> <code>Random Forest</code> <code>SVM</code> <code>Clinical ML</code></p>
</div>
</td>
</tr>
</table>

<br>

<div align="center">

## Experience

</div>

<table>
<tr>
<td width="35%" align="center"><strong>Machine Learning Engineer</strong><br><sub> @ Indiana University, Kelley School of Business</sub></td>
<td>Hierarchical LLM+RL red team agent for CybORG CAGE Challenge 4 - <strong>100% episode compromise vs 30% for the best of 14 LLMs</strong> (<a href="https://doi.org/10.1117/12.3094223">SPIE 2026</a>); cross-environment RL+RL vs LLM+LLM study over 3,600 episodes (IEEE MILCOM 2026 Workshop, accepted); LLM annotation pipeline with Tree-of-Thought + Self-Consistency labeling <strong>167K+ patent abstracts</strong> and <strong>22K+ AV disengagement incidents</strong></td>
</tr>
<tr>
<td align="center"><strong>Artificial Intelligence Intern</strong><br><sub> @ Interlinked Corp (Remote)</sub></td>
<td>Wildfire ignition-risk ML: diagnosed three data-leakage sources behind an AUC 0.994 model and rebuilt it into a calibrated LightGBM pipeline over a 1.9M-row H3 cell-week panel - <strong>honest held-out AUC 0.859, ECE 0.0037</strong>, served through a weekly FastAPI risk-zone API</td>
</tr>
<tr>
<td align="center"><strong>Artificial Intelligence Engineer</strong><br><sub> @ OCG Technologies, Singapore</sub></td>
<td>Fine-tuned Llama 2 13B chatbot with LoRA/PEFT on SageMaker - <strong>83% accuracy boost</strong>; RAG with OpenSearch for <strong>75% support overhead reduction</strong></td>
</tr>
<tr>
<td align="center"><strong>Data Engineer</strong><br><sub> @ Visual Labs, Mumbai</sub></td>
<td>3 TB drone imagery ETL pipeline — PySpark + OpenCV preprocessing, AWS Lambda orchestration, DynamoDB storage, Power BI dashboards; <strong>45% stakeholder outcome improvement</strong></td>
</tr>
</table>

<br>

<div align="center">

## Tech Stack

</div>

<table>
<tr>
<td align="center"><strong>Languages</strong></td>
<td><code>Python</code> <code>Java</code> <code>C</code> <code>SQL</code> <code>JavaScript/TypeScript</code> <code>P4</code> <code>HTML/CSS</code></td>
</tr>
<tr>
<td align="center"><strong>ML / DL</strong></td>
<td><code>PyTorch</code> <code>TensorFlow</code> <code>Scikit-learn</code> <code>LightGBM</code> <code>CNNs</code> <code>XGBoost</code></td>
</tr>
<tr>
<td align="center"><strong>RL</strong></td>
<td><code>PPO</code> <code>GRPO</code> <code>GSPO</code> <code>DAPO</code> <code>Curriculum Learning</code> <code>CybORG</code> <code>Cyberwheel</code></td>
</tr>
<tr>
<td align="center"><strong>LLMs</strong></td>
<td><code>vLLM</code> <code>SFT</code> <code>PEFT</code> <code>LoRA/QLoRA</code> <code>RAG</code> <code>LangGraph</code> <code>Transformers</code> <code>Ollama</code> <code>llama.cpp</code> <code>OpenAI API</code> <code>Gemini API</code> <code>Claude API</code></td>
</tr>
<tr>
<td align="center"><strong>Infra</strong></td>
<td><code>AWS</code> <code>SageMaker</code> <code>Lambda</code> <code>S3</code> <code>DynamoDB</code> <code>OpenSearch</code> <code>SLURM/HPC (H100, A100)</code> <code>Docker</code> <code>Railway</code> <code>Vercel</code></td>
</tr>
<tr>
<td align="center"><strong>Web / APIs</strong></td>
<td><code>FastAPI</code> <code>React</code> <code>Streamlit</code> <code>Gradio</code></td>
</tr>
<tr>
<td align="center"><strong>Data</strong></td>
<td><code>PySpark</code> <code>Pandas</code> <code>NumPy</code> <code>OpenCV</code> <code>BeautifulSoup</code> <code>pdfplumber</code></td>
</tr>
<tr>
<td align="center"><strong>Visualization</strong></td>
<td><code>Power BI</code> <code>Matplotlib</code> <code>Seaborn</code> <code>Altair</code></td>
</tr>
<tr>
<td align="center"><strong>Tools</strong></td>
<td><code>Git</code> <code>Weights & Biases</code> <code>pytest</code> <code>Unsloth</code> <code>TRL</code> <code>HuggingFace Hub</code></td>
</tr>
</table>

<br>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:58a6ff&height=100&section=footer" width="100%" />

<br>

### `If it can learn, I can build it.`

</div>
