<!--
  Notion-inspired GitHub profile README for @vamsitallapudi.
  Design language: DESIGN-notion.md — warm calm, one Notion-blue accent (#0075de),
  sticker palette used only decoratively, heavy tight display type in the hero SVG.
  Content source: resume.txt (all quantitative claims copied verbatim).
-->

<p align="center">
  <img src="assets/hero.svg" alt="Applied AI Engineer — Building production GenAI for clinical trials." width="100%" />
</p>

<!-- Contact row — the ONLY place Notion blue (#0075de) paints a CTA -->
<p align="center">
  <a href="https://www.linkedin.com/in/vamsitallapudi/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0075de?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/Vamsitallapudi9">
    <img alt="GitHub" src="https://img.shields.io/badge/GitHub-0075de?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:vamsii.tallapudi@gmail.com"><!-- TODO: fill email -->
    <img alt="Email" src="https://img.shields.io/badge/Email-0075de?style=for-the-badge&logo=maildotru&logoColor=white" />
  </a>
</p>

<br />

## Hi, I'm Vamsi 👋

Applied AI Engineer with **4+ years** across healthcare and pharma, specializing in production GenAI systems — RAG pipelines, LLM evaluation, and clinical document intelligence. I've built and shipped AI platforms that replaced a **~$1.5M/yr commercial vendor**, cut clinical authoring time from **hours to minutes**, and drove an estimated **$700K+ in annual savings**.

Deep experience turning unstructured protocols, safety data, and regulatory documents into structured, audit-ready outputs using Python, SQL, and frontier LLMs (Claude, GPT, Gemini). Author of an LLM benchmark under review at **EMNLP**, with a growing focus on evaluation systems and mechanistic interpretability.

<hr />

## ✦ Featured Work

<table>
  <tr>
    <td width="50%" valign="top">
      <img alt="Compass" src="https://img.shields.io/badge/●-Sanofi-2a9d99?style=flat-square&labelColor=ffffff" />
      <h3>Compass — Risk-Based Site Monitoring</h3>
      <p>
        Risk-based site-monitoring platform for clinical trials that ingests CTMS + operational data, computes explainable <b>Workload</b> and <b>Risk</b> scores for every site, and auto-generates monitor visit-prep summaries.
      </p>
      <p>
        <sub><b>Impact —</b> Replaced a ~<b>$1.5M/yr</b> commercial RBM vendor license and cut low-value on-site monitoring visits by an estimated <b>~30%</b> (~$400K/yr in avoided travel and CRA time). Every score traceable to raw signals for audit and inspection readiness.</sub>
      </p>
    </td>
    <td width="50%" valign="top">
      <img alt="ClinTrailBench" src="https://img.shields.io/badge/●-Sanofi%20·%20EMNLP-d6b6f6?style=flat-square&labelColor=ffffff" />
      <h3>ClinTrailBench — LLM Eval Benchmark</h3>
      <p>
        Benchmark for evaluating LLM reasoning and regulatory compliance using <b>FDA warning letters</b> and <b>ICH / 21 CFR</b> guidance across Claude, Gemini, GPT, DeepSeek, and other frontier models.
      </p>
      <p>
        <sub><b>Impact —</b> Under review at <b>EMNLP</b> — <i>"ClinTrailBench: Strong on the Exam, Weak on the (GxP) Job."</i> Novel evaluation suite exposing the gap between LLMs' exam-style knowledge and real clinical-trial operational competence.</sub>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img alt="Protocol Amendment Analyzer" src="https://img.shields.io/badge/●-BMS-dd5b00?style=flat-square&labelColor=ffffff" />
      <h3>Protocol Amendment Analyzer</h3>
      <p>
        AI-powered analyzer using Python, custom DOCX/XML parsing, and <b>GPT-4.1</b> to compare protocol revisions and automatically generate change summaries.
      </p>
      <p>
        <sub><b>Impact —</b> Achieved <b>90%+</b> accuracy against SME validation while eliminating ~<b>60 hours</b> of manual review per week across <b>25–40 protocols</b> monthly.</sub>
      </p>
    </td>
    <td width="50%" valign="top">
      <img alt="Safety Narratives" src="https://img.shields.io/badge/●-BMS-ff64c8?style=flat-square&labelColor=ffffff" />
      <h3>Clinical Safety Narratives — GenAI Pipeline</h3>
      <p>
        End-to-end GenAI pipeline using <b>Claude</b> models, <b>RAG</b>, prompt engineering, and structured outputs to automatically generate clinical Safety Narratives.
      </p>
      <p>
        <sub><b>Impact —</b> Reduced authoring time from <b>2 hours to 2 minutes</b>, contributing to an estimated <b>$300K–$400K</b> in annual operational savings.</sub>
      </p>
    </td>
  </tr>
</table>

<hr />

## ✦ Experience

<table>
  <tr>
    <td valign="top" width="230"><b>Sanofi</b><br /><sub>Software Engineering Expert<br />Digital R&D</sub><br /><sub><i>Feb 2026 — Present · Hyderabad</i></sub></td>
    <td valign="top">
      Building <b>Compass</b> (RBM platform) and designing <b>ClinTrailBench</b> (EMNLP submission). Prototyped a PDFPlumber → Markdown → Claude pipeline converting protocol PDFs into visit × assessment JSON matrices, reaching ~<b>85%</b> field-level extraction accuracy over ~30 protocols with a Gemini LLM-as-judge eval. Led an interpretability PoC applying <b>Sparse Autoencoders (SAEs)</b> to GPT-2 and Microsoft <b>BioGPT</b>.
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Bristol-Myers Squibb</b><br /><sub>Software Engineer 2<br />DDIT — Applied AI</sub><br /><sub><i>May 2024 — Jan 2026 · Hyderabad</i></sub></td>
    <td valign="top">
      Shipped the <b>Protocol Amendment Analyzer</b> and the <b>Safety Narratives</b> pipeline. Built Python/SQL ETL bridging <b>Redshift</b> and <b>Impala</b> into GenAI workflows, consolidating <b>15+ clinical datasets</b> (~$350K organization-wide impact). Developed NER pipelines with Gemini/OpenAI to extract <b>ICD-10/11, HIPAA</b>, procedural, and drug codes across <b>100+ protocols</b>. Managed ingestion and validation for <b>600+ study protocols</b> and validated 4 Tableau dashboards. Analyzed market insights across <b>52 countries</b> using Python + NLTK.
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Cognizant</b><br /><sub>Senior Systems Engineer</sub><br /><sub><i>Jul 2022 — Apr 2024 · Bangalore</i></sub></td>
    <td valign="top">
      Cloud-based data solutions in Python, SQL, Excel, and MongoDB — data processing, cleaning, validation, and automation. Applied ML for data classification and optimized reporting workflows across Agile and Waterfall delivery.
    </td>
  </tr>
</table>

<hr />

## ✦ Tech Stack

<sub><b>GENERATIVE&nbsp;AI&nbsp;&&nbsp;LLMs</b></sub><br />
<img alt="Python" src="https://img.shields.io/badge/Python-1f1f1f?style=flat-square&logo=python&logoColor=ffffff" />
<img alt="LangChain" src="https://img.shields.io/badge/LangChain-1f1f1f?style=flat-square" />
<img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-1f1f1f?style=flat-square" />
<img alt="PydanticAI" src="https://img.shields.io/badge/PydanticAI-1f1f1f?style=flat-square" />
<img alt="RAG" src="https://img.shields.io/badge/RAG-1f1f1f?style=flat-square" />
<img alt="MCP" src="https://img.shields.io/badge/MCP-1f1f1f?style=flat-square" />
<img alt="Prompt Engineering" src="https://img.shields.io/badge/Prompt%20Engineering-1f1f1f?style=flat-square" />
<img alt="Structured Outputs" src="https://img.shields.io/badge/Structured%20Outputs-1f1f1f?style=flat-square" />
<img alt="Agentic Workflows" src="https://img.shields.io/badge/Agentic%20Workflows-1f1f1f?style=flat-square" />

<br /><br />
<sub><b>LLM&nbsp;INFERENCE&nbsp;&&nbsp;OPTIMIZATION</b></sub><br />
<img alt="vLLM" src="https://img.shields.io/badge/vLLM-1f1f1f?style=flat-square" />
<img alt="Continuous Batching" src="https://img.shields.io/badge/Continuous%20Batching-1f1f1f?style=flat-square" />
<img alt="KV Cache" src="https://img.shields.io/badge/KV%20Cache-1f1f1f?style=flat-square" />
<img alt="Speculative Decoding" src="https://img.shields.io/badge/Speculative%20Decoding-1f1f1f?style=flat-square" />
<img alt="Quantization" src="https://img.shields.io/badge/Quantization%20(GPTQ%2FAWQ%2FFP8%2FINT4)-1f1f1f?style=flat-square" />

<br /><br />
<sub><b>LLMOPS&nbsp;&&nbsp;EVALUATION</b></sub><br />
<img alt="LangSmith" src="https://img.shields.io/badge/LangSmith-1f1f1f?style=flat-square" />
<img alt="LLM-as-Judge" src="https://img.shields.io/badge/LLM--as--Judge-1f1f1f?style=flat-square" />
<img alt="Human Evaluation" src="https://img.shields.io/badge/Human%20Evaluation-1f1f1f?style=flat-square" />
<img alt="Benchmark Design" src="https://img.shields.io/badge/Benchmark%20Design-1f1f1f?style=flat-square" />
<img alt="Hallucination Detection" src="https://img.shields.io/badge/Hallucination%20Detection-1f1f1f?style=flat-square" />

<br /><br />
<sub><b>RETRIEVAL&nbsp;&&nbsp;NLP</b></sub><br />
<img alt="FAISS" src="https://img.shields.io/badge/FAISS-1f1f1f?style=flat-square" />
<img alt="Pinecone" src="https://img.shields.io/badge/Pinecone-1f1f1f?style=flat-square" />
<img alt="Hybrid Search" src="https://img.shields.io/badge/Hybrid%20Search-1f1f1f?style=flat-square" />
<img alt="Sentence Transformers" src="https://img.shields.io/badge/Sentence%20Transformers-1f1f1f?style=flat-square" />
<img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-1f1f1f?style=flat-square&logo=huggingface&logoColor=ffffff" />
<img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-1f1f1f?style=flat-square&logo=pytorch&logoColor=ffffff" />
<img alt="NER" src="https://img.shields.io/badge/NER-1f1f1f?style=flat-square" />
<img alt="Biomedical NLP" src="https://img.shields.io/badge/Biomedical%20NLP-1f1f1f?style=flat-square" />
<img alt="SAEs" src="https://img.shields.io/badge/Sparse%20Autoencoders-1f1f1f?style=flat-square" />

<br /><br />
<sub><b>DATA&nbsp;ENGINEERING</b></sub><br />
<img alt="SQL" src="https://img.shields.io/badge/SQL-1f1f1f?style=flat-square" />
<img alt="Redshift" src="https://img.shields.io/badge/Amazon%20Redshift-1f1f1f?style=flat-square&logo=amazonredshift&logoColor=ffffff" />
<img alt="Impala" src="https://img.shields.io/badge/Apache%20Impala-1f1f1f?style=flat-square&logo=apache&logoColor=ffffff" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-1f1f1f?style=flat-square&logo=postgresql&logoColor=ffffff" />
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-1f1f1f?style=flat-square&logo=mongodb&logoColor=ffffff" />
<img alt="Parquet" src="https://img.shields.io/badge/Apache%20Parquet-1f1f1f?style=flat-square" />
<img alt="Pandas" src="https://img.shields.io/badge/Pandas-1f1f1f?style=flat-square&logo=pandas&logoColor=ffffff" />

<br /><br />
<sub><b>CLOUD,&nbsp;DEVOPS&nbsp;&&nbsp;VISUALIZATION</b></sub><br />
<img alt="Azure" src="https://img.shields.io/badge/Microsoft%20Azure-1f1f1f?style=flat-square&logo=microsoftazure&logoColor=ffffff" />
<img alt="Azure Functions" src="https://img.shields.io/badge/Azure%20Functions-1f1f1f?style=flat-square" />
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-1f1f1f?style=flat-square&logo=githubactions&logoColor=ffffff" />
<img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-1f1f1f?style=flat-square&logo=streamlit&logoColor=ffffff" />
<img alt="Tableau" src="https://img.shields.io/badge/Tableau-1f1f1f?style=flat-square&logo=tableau&logoColor=ffffff" />
<img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-1f1f1f?style=flat-square&logo=powerbi&logoColor=ffffff" />

<br /><br />
<sub><b>CLINICAL&nbsp;AI&nbsp;&&nbsp;LIFE&nbsp;SCIENCES</b></sub><br />
<img alt="Clinical Trial Analytics" src="https://img.shields.io/badge/Clinical%20Trial%20Analytics-1f1f1f?style=flat-square" />
<img alt="Protocol Intelligence" src="https://img.shields.io/badge/Protocol%20Intelligence-1f1f1f?style=flat-square" />
<img alt="Safety Narratives" src="https://img.shields.io/badge/Safety%20Narratives-1f1f1f?style=flat-square" />
<img alt="Regulatory AI" src="https://img.shields.io/badge/FDA%20·%20ICH%20·%2021%20CFR%20·%20GxP-1f1f1f?style=flat-square" />
<img alt="Medical Coding" src="https://img.shields.io/badge/ICD--10%2F11%20·%20HIPAA-1f1f1f?style=flat-square" />

<hr />

## ✦ Education & Certifications

- **M.Tech, Artificial Intelligence and Data Science** — KIET, Kakinada · <sub>2022 — 2024</sub>
- **B.Tech, Electrical and Electronics Engineering** — Aditya University, Surampalem · <sub>2018 — 2021</sub>
- **Technical Diploma, Electrical and Electronics Engineering** — APT, Anaparthi · <sub>2015 — 2018</sub>
- **IBM Data Science Professional Certification** — Innomatics Research Labs
- **IBM Data Engineering Professional Certification** — Coursera

<hr />

<p align="center">
  <sub>Hyderabad, Telangana · Applied AI · Clinical GenAI · LLM Evaluation</sub><br />
  <sub><i>Quiet chrome. One blue. Everything else earns its color.</i></sub>
</p>
