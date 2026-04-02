# eScience Research Group — Fluminense Federal University (UFF)

> **Institute of Computing · Universidade Federal Fluminense · Niterói, Brazil**
> 📧 [danielcmo@ic.uff.br](mailto:danielcmo@ic.uff.br) · 🌐 [github.com/UFFeScience](https://github.com/UFFeScience)

---

## About

The **eScience Research Group** at the Institute of Computing of the Fluminense Federal University (IC/UFF) develops open-source tools, middleware, and frameworks focused on **scientific workflows**, **provenance data management**, **high-performance computing**, and **distributed systems**. Our work spans from containerized workflow orchestration to deep learning provenance, serving both academic and industrial research communities.

---

## Featured Projects

### 🔷 [AkôFlow](https://github.com/UFFeScience/akoflow)
> **Open-source middleware for orchestrating and executing container-based scientific workflows across heterogeneous environments.**

AkôFlow supports execution on Kubernetes clusters (AWS EKS, GCP GKE, Azure AKS), Singularity for HPC isolated environments, and the SDumont supercomputer at LNCC (Brazil). Originally started as a final undergraduate project, it has grown into a production-ready workflow engine actively maintained by the group.

- **Language:** Go · **Stars:** ⭐ 63 · **Latest release:** v0.5.1
- **Install:**
  ```bash
  curl -fsSL https://akoflow.com/run | bash
  ```
- **Docs:** [uffescience.github.io/akoflow](https://uffescience.github.io/akoflow/)

---

### 🔷 [SAMbA](https://github.com/UFFeScience/SAMbA)
> **Extending Apache Spark for Scientific Computational Experiments.**

SAMbA adds provenance-aware capabilities to Apache Spark, enabling scientists to track and analyze data transformations throughout large-scale computational experiments.

- **Language:** Scala · **Stars:** ⭐ 16

---

### 🔷 [DLProv](https://github.com/UFFeScience/dlprov)
> **Provenance data integration service for Deep Learning workflows.**

Evolved from DNNProv, DLProv supports online hyperparameter analysis and retrospective provenance capture across the full deep learning lifecycle — from data pre-processing through model training and evaluation. It integrates with MonetDB for online analysis and Neo4j for W3C PROV-compliant graph queries.

- **Language:** Python · **Stars:** ⭐ 15
- **Docker:**
  ```bash
  docker pull dbpina/dlprov
  ```

---

### 🔷 [SciCumulus](https://github.com/UFFeScience/SciCumulus)
> **Workflow Engine for scientific experiments in cloud environments.**

SciCumulus is a cloud-based scientific workflow engine designed to manage and execute parameter sweep experiments across distributed resources.

- **Language:** Java · **Stars:** ⭐ 14

---

### 🔷 [Phenomanager](https://github.com/UFFeScience/Phenomanager)
> **Management system for phenotyping experiments.**

A platform for organizing, tracking, and analyzing data from phenotyping experiments in agricultural and biological research.

- **Language:** CSS/Web · **Stars:** ⭐ 13

---

### 🔷 [Denethor](https://github.com/UFFeScience/denethor)
> **Serverless scientific workflow analysis and provenance tool.**

Denethor focuses on provenance data collection and analysis for scientific workflows executed in serverless computing environments.

- **Language:** Python · **Stars:** ⭐ 13 · **License:** GPL-3.0

---

## AkôFlow Ecosystem

The group maintains a full ecosystem of repositories around AkôFlow:

| Repository | Description |
|---|---|
| [akoflow](https://github.com/UFFeScience/akoflow) | Core workflow engine (Go) |
| [akoflow-deployment-control-plane](https://github.com/UFFeScience/akoflow-deployment-control-plane) | Deployment control plane backend (PHP) |
| [akoflow-deployment-control-plane-ui](https://github.com/UFFeScience/akoflow-deployment-control-plane-ui) | Control plane frontend UI (TypeScript) |
| [akoflow-driver-s3-uploader](https://github.com/UFFeScience/akoflow-driver-s3-uploader) | AWS S3 storage driver (Python) |
| [akoflow-driver-gcs-uploader](https://github.com/UFFeScience/akoflow-driver-gcs-uploader) | Google Cloud Storage driver (Python) |
| [akoflow-driver-dataverse-uploader](https://github.com/UFFeScience/akoflow-driver-dataverse-uploader) | Dataverse repository driver (Python) |
| [akoflow-example-wf-etl-clothing](https://github.com/UFFeScience/akoflow-example-wf-etl-clothing) | Example ETL workflow (Python) |

---

## Research Topics

- Scientific Workflow Management Systems (WfMS)
- Provenance Data Capture & Analysis
- High-Performance Computing (HPC) & Supercomputing
- Containerized & Serverless Computing
- Deep Learning Lifecycle Management
- Data-Centric AI & Reproducibility
- Cloud & Kubernetes Orchestration

---

## Technologies

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat&logo=scala&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## Selected Publications

- Ferreira, W. et al. (2024). *AkôFlow: um Middleware para execução de Workflows científicos em múltiplos ambientes conteinerizados.* SBBD 2024. [DOI:10.5753/sbbd.2024.241126](https://doi.org/10.5753/sbbd.2024.241126)
- Ferreira, W. et al. (2025). *Plug and Flow: Execução de Workflows Científicos em Contêineres com o Middleware AkôFlow.* SBBD 2025. *(accepted)*
- Pina, D. et al. (2024). *DLProv: A Data-Centric Support for Deep Learning Workflow Analyses.* DEEM @ SIGMOD 2024. [ACM DL](https://dl.acm.org/doi/abs/10.1145/3650203.3663337)
- Pina, D. et al. (2023). *Deep learning provenance data integration: a practical approach.* WWW Companion 2023. [ACM DL](https://dl.acm.org/doi/abs/10.1145/3543873.3587561)
- de Oliveira, L.S. et al. (2023). *PINNProv: Provenance for Physics-Informed Neural Networks.* SBAC-PADW 2023. [IEEE](https://ieeexplore.ieee.org/abstract/document/10306106)

---

## Contributors & Team

| Name | Role | Affiliation |
|---|---|---|
| [D.Sc. Daniel de Oliveira](http://profs.ic.uff.br/~danielcmo/) | Research Advisor | IC/UFF |
| [Wesley Ferreira (@ovvesley)](https://github.com/ovvesley) | Maintainer (AkôFlow) | IC/UFF |
| Liliane Kunstmann | Researcher | COPPE/UFRJ |
| Debora Pina | Researcher | COPPE/UFRJ |
| Raphael Garcia | Researcher | IC/UFF |
| [Yuri Frota](http://www.ic.uff.br/~yuri/) | Collaborator | IC/UFF |
| [Marcos Bedo](https://www.professores.uff.br/marcosbedo/) | Collaborator | IC/UFF |
| [Aline Paes](http://www.ic.uff.br/~alinepaes/) | Collaborator | IC/UFF |
| Luan Teylo | Collaborator | INRIA / Univ. de Bordeaux |

---

## Getting Involved

We welcome contributions, collaborations, and feedback from the community.

- 📂 Browse our [68+ repositories](https://github.com/orgs/UFFeScience/repositories)
- 🐛 Open issues on individual project repositories
- 📧 Contact the group at [danielcmo@ic.uff.br](mailto:danielcmo@ic.uff.br)
- 🎥 Watch the [AkôFlow demo video (Portuguese)](https://www.youtube.com/watch?v=RmrAMWkJij4)

---

*eScience Research Group · Institute of Computing · Universidade Federal Fluminense (UFF) · Brazil*
