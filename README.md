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

```mermaid
flowchart TB
    START(["Business challenge / opportunity"]):::entry

    subgraph DISCOVERY["01  /  DISCOVER & ALIGN"]
        direction LR
        NEED["Understand the problem<br/>Stakeholders · users · workflows"]:::strategy
        TARGET["Define measurable success<br/>KPIs · ROI · quality · SLOs"]:::strategy
        TRUST["Set delivery constraints<br/>Privacy · security · budget"]:::strategy
        NEED --> TARGET --> TRUST
    end

    subgraph FEASIBILITY["02  /  DATA & FEASIBILITY"]
        direction LR
        AUDIT["Assess data readiness<br/>Sources · rights · quality"]:::data
        BASE["Prove feasibility<br/>Baselines · experiments · PoC"]:::data
        GO{"Viable business<br/>and technical case?"}:::gate
        AUDIT --> BASE --> GO
    end

    subgraph BUILD["03  /  ARCHITECT & BUILD"]
        direction TB
        CHOICE{"Choose the simplest<br/>viable AI approach"}:::gate
        RAG["LLM / RAG<br/>Ingest · embed · retrieve · ground"]:::model
        VISION["Computer vision / ML<br/>Label · train · tune"]:::model
        AGENTS["Agentic / hybrid AI<br/>Tools · orchestration · guardrails"]:::model
        SYSTEM["Integrate end to end<br/>Pipelines · APIs · UX · human review"]:::model
        CHOICE -->|LLM / RAG| RAG
        CHOICE -->|CV / ML| VISION
        CHOICE -->|Agents| AGENTS
        RAG --> SYSTEM
        VISION --> SYSTEM
        AGENTS --> SYSTEM
    end

    subgraph EVALUATION["04  /  EVALUATE & GOVERN"]
        direction LR
        OFFLINE["Evaluate task quality<br/>Golden sets · accuracy · groundedness"]:::validation
        NONFUNC["Validate trust & SLOs<br/>Safety · robustness · latency · cost"]:::validation
        GATE{"Release gates<br/>passed?"}:::gate
        OFFLINE --> GATE
        NONFUNC --> GATE
    end

    subgraph PRODUCTION["05  /  DEPLOY & SCALE"]
        direction LR
        OPS["MLOps / LLMOps<br/>Tracking · versioning · CI/CD"]:::operations
        SERVE["Production serving<br/>Cloud / edge · APIs · containers"]:::operations
        ROLL["Progressive rollout<br/>Canary · rollback · scaling"]:::operations
        OPS --> SERVE --> ROLL
    end

    subgraph OBSERVABILITY["06  /  MONITOR & OPTIMIZE"]
        direction LR
        WATCH["Monitor live systems<br/>Quality · drift · latency · cost"]:::operations
        LEARN["Learn from production<br/>Feedback · eval sets · A/B tests"]:::operations
        VALUE(["Measured business value<br/>Adoption · KPI uplift · ROI"]):::outcome
        WATCH --> LEARN --> VALUE
    end

    START --> DISCOVERY
    DISCOVERY --> FEASIBILITY
    FEASIBILITY -->|Go| BUILD
    FEASIBILITY -. Reframe .-> DISCOVERY
    BUILD --> EVALUATION
    EVALUATION -->|Pass| PRODUCTION
    EVALUATION -. Iterate .-> BUILD
    PRODUCTION --> OBSERVABILITY
    OBSERVABILITY -. Continuous improvement .-> BUILD

    classDef entry fill:#254B7B,stroke:#183457,color:#FFFFFF,stroke-width:2px;
    classDef strategy fill:#EAF1FC,stroke:#6385BC,color:#203B60,stroke-width:1.5px;
    classDef data fill:#E7F4FA,stroke:#5291AA,color:#184D63,stroke-width:1.5px;
    classDef model fill:#E5F6F1,stroke:#3A9A83,color:#135B4C,stroke-width:1.5px;
    classDef validation fill:#F1EDFE,stroke:#8A75BF,color:#473478,stroke-width:1.5px;
    classDef gate fill:#FFF1D9,stroke:#C9993D,color:#79500F,stroke-width:2px;
    classDef operations fill:#EDF1FE,stroke:#7585C7,color:#344377,stroke-width:1.5px;
    classDef outcome fill:#DFF4E8,stroke:#39966A,color:#1B6143,stroke-width:2px;
```

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
