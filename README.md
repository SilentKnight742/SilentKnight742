<div align="center">

# Apoorv Chitnis

### Applied AI Engineer · Python · Backend Systems · Cloud

I build practical AI systems that combine intelligent models with reliable software,
data pipelines, optimization, and real-world decision making.

[LinkedIn](https://www.linkedin.com/in/apoorvchitnis/) ·
[GitHub](https://github.com/SilentKnight742) ·
[Resume](./Apoorv_Chitnis_Resume.pdf) ·
[Email](mailto:chitnisapoorv@gmail.com)

</div>

---

## About

I’m a Python and AI engineer with professional experience building large-scale
data validation and intelligent automation systems at **MSCI**.

My work has included asynchronous and multithreaded Python systems operating
across tens of millions of records, Azure Databricks data pipelines, CI/CD,
AI-assisted software automation, and backend engineering.

I’m currently focused on **applied AI engineering** — particularly LLM systems,
agents, retrieval, evaluation, backend infrastructure, cloud deployment, and
optimization.

I enjoy problems where AI has to interact with a real system rather than exist
as an isolated model demo.

---

## Experience

### MSCI — Analyst
**Sep 2024 – Jun 2025**

- Engineered a Python validation system for an **Oracle → Azure Databricks migration involving 50M+ records**.
- Used **async I/O and multithreading** to reduce an otherwise impractical validation workload to under 24 hours.
- Built modular, configuration-driven validation using **Pytest, YAML, Oracle, Cosmos DB, and Databricks**.
- Integrated automated validation into **Azure DevOps CI/CD** pipelines.
- Built an AI-assisted UI/API automation proof of concept that translated natural-language test cases into executable workflows.
- Recognized internally for infrastructure-level impact and rapid technical upskilling.

---

# Featured Work

## HeatShift

### Heat-aware operational planning and optimization

[Live Product](https://heatshift-ai-zeta.vercel.app) ·
[API](https://heatshift-ai-api.vercel.app) ·
[Repository](https://github.com/SilentKnight742/heatshift-ai)

HeatShift models one day of operations at a large outdoor site and restructures
the work schedule to reduce heat exposure while preserving operational constraints.

It combines environmental conditions, site-specific risk factors, simulated
crews and workloads, and constrained scheduling into a decision-support system.

**What it does**

- Generates large fictional daily operations consisting of crews, jobs, workloads,
  PPE, acclimatization, mobility, and scheduling constraints.
- Combines environmental conditions with spatial and operational factors to
  calculate task-level heat-risk scores.
- Runs a deterministic optimizer over candidate start times and eligible crews.
- Minimizes high-risk worker exposure while preserving hard operational constraints.
- Compares the original and proposed schedules through an interactive site map.
- Reports exposure, disruption, retained work, residual risk, and constraint validity.

**Validation**

The HeatShift screening score was separately evaluated against **566 controlled
human-exposure sessions** from the public HEAT-SHIELD dataset, showing a
**0.7718 Spearman rank correlation** with measured one-hour physical-work-capacity loss.

**Stack**

`Python` · `FastAPI` · `Next.js` · `React` · `Supabase` · `Leaflet` ·
`Optimization` · `Simulation` · `Vercel`

---

## SwarmSearch

### Fault-tolerant cooperative multi-UAV search and recovery

[Repository](https://github.com/SilentKnight742/SwarmSearch)

SwarmSearch is a software-only autonomous multi-UAV coordination system built
using **Python, MAVLink, and ArduPilot SITL**.

It coordinates simulated aircraft across a shared search area, monitors live
telemetry, detects or injects mission failures, and automatically redistributes
unfinished work to surviving UAVs.

**What it does**

- Coordinates multiple ArduPilot SITL vehicles concurrently.
- Generates cooperative lawnmower-style search routes.
- Uses live MAVLink telemetry for position, altitude, armed state, flight mode,
  navigation readiness, and mission progress.
- Detects mission-level vehicle failures and preserves already completed search work.
- Reassigns unfinished coverage to healthy UAVs instead of restarting the mission.
- Handles phase-aware withdrawal during takeoff, search, return, and landing.
- Provides a browser-based 3D mission-control interface with live vehicle state,
  coverage routes, mission events, and operator-triggered failure injection.

**Architecture**

`React / Three.js → FastAPI → Swarm Coordinator → MAVLink → ArduPilot SITL`

**Stack**

`Python` · `FastAPI` · `WebSockets` · `MAVLink` · `ArduPilot SITL` ·
`React` · `Three.js` · `Autonomous Systems`

> **Status:** v0.1 — active development

---

# Currently Building / Exploring

### SubaRAG
Researching latency-aware RAG architectures built around **avoiding unnecessary
retrieval work** — speculative retrieval from stable partial speech, adaptive
retrieval depth, conditional reranking, context compression, and caching.

### OrcaTrace
Exploring **agentic investigation and graph-based reasoning** for complex,
multi-source investigative workflows.

### JalDrishti
Developing disaster-intelligence workflows around **Earth observation,
geospatial processing, infrastructure exposure, and operational impact analysis**.

### AI Systems Lab
Ongoing experiments around:

- LLM APIs and provider abstraction
- structured outputs and tool calling
- RAG and retrieval evaluation
- agentic workflows
- MCP
- context engineering
- model gateways
- observability and evaluation
- cloud deployment

---

# Earlier Work

## GeoAI ReImagined — NASA Space Apps

Explored the use of geospatial foundation models for natural-disaster monitoring.

- Built a real-time data fetcher for **NASA HLS satellite imagery**.
- Experimented with the **Prithvi-100 geospatial foundation model**.
- Investigated few-image approaches for disaster analysis from satellite data.

---

## AI-Based Crop Management System Using Drones

Designed a drone-based system for monitoring and automated treatment of fruit orchards.

- Worked on drone assembly and software configuration.
- Used **YOLOv5** for computer vision and object detection.
- Focused on mango and cashew orchard monitoring and selective treatment.
- Awarded **Design Patent 404133-001**.
- Won the **Innovation Project** category at HackMIT-WPU.

---

## Social Media Threat Detection

Built and compared machine-learning and deep-learning approaches for identifying
toxic, threatening, and propaganda-related content in social-media data.

Worked with NLP classification and LLM-based multilingual processing.

---

# Technical Toolkit

### Languages
`Python` · `SQL` · `C` · `C++`

### AI / ML
`PyTorch` · `TensorFlow` · `scikit-learn` · `Hugging Face` · `OpenCV` ·
`LangChain` · `LLM APIs` · `RAG` · `Agentic Systems` · `MCP`

### Backend
`FastAPI` · `Flask` · `Django` · `Pydantic` · `REST APIs` ·
`Async Python` · `WebSockets`

### Data
`Pandas` · `NumPy` · `Azure Databricks` · `OracleDB` · `PostgreSQL` ·
`MySQL` · `FAISS`

### Cloud / DevOps
`Azure` · `AWS` · `Docker` · `Azure DevOps` · `GitHub` · `CI/CD` · `Vercel`

### Testing / Reliability
`Pytest` · `Great Expectations` · `MLflow`

### Autonomous / Geospatial
`MAVLink` · `ArduPilot SITL` · `Drone Systems` · `Satellite Data` ·
`Geospatial AI`

---

# Research & Recognition

### Patent
**AI-Based Crop Management System Using Drones**  
Design Patent **404133-001**

### Publication
**Using Drone Technology for Fruit Orchard Management and Waste Reduction**  
International Conference on Computing Communication Control and Automation — ICCUBEA

### Recognition
- Internal recognition at MSCI for engineering impact and rapid upskilling.
- **HackMIT-WPU Innovation Project Winner** — Drone-Based Crop Management System.
- **Best Presentation, Flow Blockchain Hackathon** — blockchain-based PvP strategy game concept.

---

# Education

### B.Tech — Computer Science & Engineering
**MIT World Peace University, Pune**

**CGPA: 9.1 / 10**

2020 – 2024

---

<div align="center">

## Let’s Connect

I’m interested in building practical AI and software systems where
engineering decisions have measurable real-world impact.

[LinkedIn](https://www.linkedin.com/in/apoorvchitnis/) ·
[Email](mailto:chitnisapoorv@gmail.com) ·
[GitHub](https://github.com/SilentKnight742)

</div>
