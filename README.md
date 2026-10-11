![Banner](assets/Banner.png)
              
<h1 align="center">Daniil Horobets</h1>
<h3 align="center">AI/ML Expert</h3>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=3200&pause=900&center=true&vCenter=true&width=900&color=36558B&lines=Building+production+LLM+systems;RAG+%7C+Computer+Vision+%7C+MLOps;From+problem+understanding+to+deployment;AI+architecture+that+drives+business+value"
    alt="Typing SVG"
  />
</p>

<p align="center">
  I build production AI systems from problem understanding and model design
  to deployment, monitoring, and business use.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/Daniil-Horobets"><img src="https://img.shields.io/badge/LinkedIn-Daniil_Horobets-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:daniil.horobets.dev@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Daniil-Horobets"><img src="https://img.shields.io/badge/GitHub-Daniil--Horobets-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based_in-Germany-000000?style=flat-square" alt="Germany"/>
  <img src="https://img.shields.io/badge/Focus-LLMs_|_Computer_Vision_|_MLOps-blueviolet?style=flat-square" alt="Focus"/>
</p>

---

## Quick overview

<div align="center">

<table width="100%">
<tr>
<td width="50%" valign="top" nowrap>

### What I build
- LLM applications and AI assistants  
- RAG pipelines and multilingual NLP systems  
- Computer vision and real-time perception systems  
- Forecasting, anomaly detection, and edge AI deployment  <br/><br/>

</td>
<td width="50%" valign="top" nowrap>

### What I usually own
- AI solution architecture  
- Model lifecycle and MLOps  
- Cloud deployment and platform integration  
- Technical leadership and stakeholder communication  <br/><br/>

</td>
</tr>
</table>

</div>

---

## How I work

<table>
<tr>
<td width="50%" valign="top">
  <b>Production AI</b><br/>
  I turn ML ideas into systems that teams can ship and scale.<br/><br/>
</td>
<td width="50%" valign="top">
  <b>Architecture Thinking</b><br/>
  I connect models, APIs, and infrastructure into one solution.<br/><br/>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <b>MLOps & Cloud</b><br/>
  I design deployment, tracking, orchestration, CI/CD, and monitoring as part of the product.
</td>
<td width="50%" valign="top">
  <b>Leadership</b><br/>
  I lead technical decisions, explain trade-offs clearly, and help teams move faster with less risk.
</td>
</tr>
</table>

## AI Delivery Lifecycle

From business discovery to production AI that drives measurable results.

```mermaid
%%{init: {"theme":"base","themeVariables":{"background":"#0D1117","primaryColor":"#111827","primaryTextColor":"#F1F5F9","primaryBorderColor":"#334155","lineColor":"#8291A7","clusterBkg":"#151D2B","clusterBorder":"#344256","textColor":"#F1F5F9","edgeLabelBackground":"#0D1117","fontFamily":"Inter, Segoe UI, Arial, sans-serif","fontSize":"14px"},"flowchart":{"curve":"basis","nodeSpacing":26,"rankSpacing":30,"htmlLabels":true}}}%%
flowchart TB
    START(["<b>BUSINESS OPPORTUNITY</b><br/>From idea to measurable impact"]):::hero

    subgraph S1["01  /  DISCOVER         ."]
        direction LR
        A["<b>Problem framing</b><br/>Users · workflows · risks"]:::blue
        B["<b>Success contract</b><br/>KPIs · ROI · SLOs · budget"]:::blue
        A --> B
    end

    subgraph S2["02  /  DATA & FEASIBILITY         ."]
        direction LR
        C["<b>Data readiness</b><br/>Access · quality · governance"]:::cyan
        D["<b>Baseline & PoC</b><br/>Benchmarks · cost · feasibility"]:::cyan
        E{"Go /<br/>re-scope?"}:::decision
        C --> D --> E
    end

    subgraph S3["03  /  ARCHITECT         ."]
        direction TB
        F{"Select AI<br/>approach"}:::decision
        G["<b>LLM / RAG</b><br/>Retrieval · grounding"]:::teal
        H["<b>CV / Predictive ML</b><br/>Features · training"]:::teal
        I["<b>Agentic systems</b><br/>Tools · guardrails"]:::teal
        J["<b>Solution integration</b><br/>Pipelines · APIs · UX · human review"]:::teal
        F --> G & H & I
        G & H & I --> J
    end

    subgraph S4["04  /  EVALUATE         ."]
        direction LR
        K["<b>Task evaluation</b><br/>Golden sets · accuracy · groundedness"]:::violet
        L["<b>Production readiness</b><br/>Safety · latency · resilience · cost"]:::violet
        M{"Release<br/>gate"}:::decision
        K --> M
        L --> M
    end

    subgraph S5["05  /  DEPLOY         ."]
        direction LR
        N["<b>MLOps / LLMOps</b><br/>Versioning · CI/CD · lineage"]:::indigo
        O["<b>Production serving</b><br/>Cloud / edge · APIs · scaling"]:::indigo
        P["<b>Safe rollout</b><br/>Canary · rollback · security"]:::indigo
        N --> O --> P
    end

    subgraph S6["06  /  OBSERVE         ."]
        direction LR
        Q["<b>Monitor</b><br/>Quality · drift · latency · spend"]:::blue
        R["<b>Improve</b><br/>Feedback · A/B tests · retraining"]:::blue
        Q --> R
    end

    RESULT(["<b>MEASURABLE BUSINESS VALUE</b><br/>Adoption · KPI uplift · ROI"]):::success

    START --> S1 --> S2 -->|Go                 .| S3 --> S4 --> S5 --> S6 --> RESULT

    classDef hero fill:#183A66,stroke:#60A5FA,color:#FFFFFF,stroke-width:2px;
    classDef blue fill:#18283D,stroke:#60A5FA,color:#F1F5F9,stroke-width:1.5px;
    classDef cyan fill:#102D3A,stroke:#38BDF8,color:#F1F5F9,stroke-width:1.5px;
    classDef teal fill:#10332F,stroke:#34D399,color:#F1F5F9,stroke-width:1.5px;
    classDef violet fill:#2C2144,stroke:#A78BFA,color:#F1F5F9,stroke-width:1.5px;
    classDef indigo fill:#1E2749,stroke:#818CF8,color:#F1F5F9,stroke-width:1.5px;
    classDef decision fill:#3A2C17,stroke:#FBBF24,color:#FEF3C7,stroke-width:2px;
    classDef success fill:#103D31,stroke:#4ADE80,color:#DCFCE7,stroke-width:2px;

    style S1 fill:#141E2E,stroke:#334965,stroke-width:1px,color:#E2E8F0
    style S2 fill:#13232E,stroke:#285169,stroke-width:1px,color:#E2E8F0
    style S3 fill:#122823,stroke:#276258,stroke-width:1px,color:#E2E8F0
    style S4 fill:#241B35,stroke:#564279,stroke-width:1px,color:#E2E8F0
    style S5 fill:#1A2140,stroke:#485A93,stroke-width:1px,color:#E2E8F0
    style S6 fill:#141E2E,stroke:#334965,stroke-width:1px,color:#E2E8F0

    linkStyle default stroke:#8190A5,stroke-width:1.5px;
```

**Every release is a learning cycle:** production telemetry and user feedback inform the next round of scoping, model improvements, evaluation, and rollout.


---

## Tech Stack

<p align="center">
  <br/><br/>
    <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,postgres,docker,kubernetes,aws,gcp,azure,terraform&perline=11" /></a>
  <br/><br/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LLMs-OpenAI_·_Anthropic_·_Gemini-412991?style=flat-square" alt="LLMs"/>
  <img src="https://img.shields.io/badge/NLP-Transformers_·_RAG_·_LangChain-1f6feb?style=flat-square" alt="NLP"/>
  <img src="https://img.shields.io/badge/CV-OpenCV_·_YOLO_·_SAM2_·_DETR-0a7ea4?style=flat-square" alt="CV"/>
  <img src="https://img.shields.io/badge/MLOps-MLflow_·_Kubeflow_·_Airflow-ff6b35?style=flat-square" alt="MLOps"/>
  <img src="https://img.shields.io/badge/Data-SQL_·_PostgreSQL_·_Qdrant-198754?style=flat-square" alt="Data"/>
  <img src="https://img.shields.io/badge/Deployment-Docker_·_Kubernetes_·_CI/CD-6f42c1?style=flat-square" alt="Deployment"/>
</p>

---

## Education

</b><br/>
<p>
  <img src="assets/stanford.png" alt="Stanford University" height="55" align="left" hspace="12" />
  <b>Stanford University</b><br/>
  Artificial Intelligence Graduate Certificate
</p>

<br clear="left"/>

<p>
  <img src="assets/fau.png" alt="FAU Erlangen-Nürnberg" height="55" align="left" hspace="12" />
  <b>FAU Erlangen-Nürnberg</b><br/>
  M.Sc. in Information and Communication Technology
</p>

<br clear="left"/>

<p>
  <img src="assets/bsuir.png" alt="BSUIR" height="55" align="left" hspace="12" />
  <b>BSUIR</b><br/>
  B.Sc. in Infocommunication Technologies
</p>

<br clear="left"/>

---

## Recognition

- **1st Place** — The Tensor Tournament Hackathon  
- **1st Place** — FAU Deep Learning Challenge  
- Certifications in **Azure AI**, **Docker**, **Vector Databases**, and **Data Science**

---

## Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/Daniil-Horobets"><img src="https://img.shields.io/badge/LinkedIn-Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:daniil.horobets.dev@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>
