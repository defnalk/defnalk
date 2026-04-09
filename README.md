<h1 align="center">Hi, I'm Defne 👋</h1>

<p align="center">
  <b>Chemical Engineering @ Imperial College London</b><br/>
  Scientific software · Process modelling · Carbon capture · Energy systems · Data engineering for climate
</p>

<p align="center">
  <a href="mailto:defne.ertugrul22@imperial.ac.uk">
    <img src="https://img.shields.io/badge/email-defne.ertugrul22%40imperial.ac.uk-red?logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://img.shields.io/badge/London-UK-blue?logo=googlemaps&logoColor=white" alt="London, UK"/>
  <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Research-brightgreen" alt="Open to opportunities"/>
</p>

---

I build scientific Python tools and data systems for **carbon capture, energy systems, process modelling, and thermal systems**.

My work sits at the intersection of **carbon capture and pilot plant analysis**, **reactor and separation process modelling**, **solar and nuclear energy systems**, **data engineering for climate datasets**, and **scientific software engineering**.

---

## ⭐ Featured project — `meapy`

[![meapy CI](https://github.com/defnalk/meapy/actions/workflows/ci.yml/badge.svg)](https://github.com/defnalk/meapy/actions/workflows/ci.yml)
[![Release](https://github.com/defnalk/meapy/actions/workflows/release.yml/badge.svg)](https://github.com/defnalk/meapy/actions/workflows/release.yml)
[![CodeQL](https://github.com/defnalk/meapy/actions/workflows/codeql.yml/badge.svg)](https://github.com/defnalk/meapy/actions/workflows/codeql.yml)
[![mypy strict](https://img.shields.io/badge/mypy-strict-2A6DB2)](https://github.com/defnalk/meapy)
[![cosign](https://img.shields.io/badge/images-signed%20with%20cosign-4B0082)](https://github.com/defnalk/meapy)

A typed, tested Python package for the core calculations used in MEA-based **carbon capture pilot plant** commissioning and evaluation — wrapped in the rigour of a production service:

- 124 unit tests, ≥ 90 % coverage, `mypy --strict`, ruff lint+format
- Multi-stage Docker image (non-root, < 150 MB) + Lambda and Cloud Run variants
- GitHub Actions CI across **py3.10/3.11/3.12 × Ubuntu/macOS**, Codecov, Docker Scout
- Tag-driven release: TestPyPI → PyPI (OIDC) → multi-arch GHCR with **cosign-signed images** + **SPDX SBOM attestation**
- Terraform IaC for **AWS Lambda** (arm64 container, ECR, IAM least-priv, Function URL or API Gateway v2) and **GCP Cloud Run**
- Keyless deploys via GitHub OIDC trust role · CodeQL · Dependabot · CODEOWNERS

→ [github.com/defnalk/meapy](https://github.com/defnalk/meapy)

---

## 🚀 Start here

If you're new to my work, these are the best places to start:

### [`meapy`](https://github.com/defnalk/meapy)
A typed, tested Python package for the core calculations used in MEA-based carbon capture pilot plant commissioning and evaluation.
- Turns pilot-plant calculations into reusable scientific software
- Focuses on reliability, validation, and engineering clarity
- Strongest example of production-style package structure

### [`energyemissions`](https://github.com/defnalk/energyemissions)
A production-grade ETL pipeline for EU ETS verified emissions: Pandera-validated ingest → Postgres → dbt marts → Streamlit dashboard, orchestrated by Prefect, with OLS forecasts and z-score anomaly detection.
- End-to-end data engineering: Docker Compose, dbt, Prefect, testcontainers
- Strict typing (`mypy --strict`), CI, integration tests against ephemeral Postgres
- Climate-data application of modern analytics tooling

### [`tandem-solar`](https://github.com/defnalk/tandem-solar)
A simulation toolkit for perovskite–silicon tandem solar modules, including I–V modelling, terminal configurations, CTM losses, and bypass diode behaviour.
- Device-to-module level modelling
- Combines numerical methods with energy-system relevance
- Physics-aware simulation code

### [`cooltower`](https://github.com/defnalk/cooltower)
A Python package for psychrometrics, steady-flow balances, and PI controller tuning in cooling tower analysis.
- Strong engineering fundamentals
- Practical thermofluids + controls application
- Typed, validated scientific code

---

## 📚 Selected repositories

| Repository | Description |
|---|---|
| [`meapy`](https://github.com/defnalk/meapy) | MEA carbon capture pilot-plant calculations — full prod stack |
| [`energyemissions`](https://github.com/defnalk/energyemissions) | EU ETS ETL pipeline (dbt + Prefect + Streamlit) |
| [`tandem-solar`](https://github.com/defnalk/tandem-solar) | Tandem solar cell/module simulation |
| [`cooltower`](https://github.com/defnalk/cooltower) | Cooling tower psychrometrics and controls |
| [`htgr-desalination`](https://github.com/defnalk/htgr-desalination) | HTGR + MED desalination simulation |
| [`formaldehyde-reactor`](https://github.com/defnalk/formaldehyde-reactor) | Packed-bed PFR model |
| [`sepflows`](https://github.com/defnalk/sepflows) | Composable separation-process building blocks |
| [`laidlaw`](https://github.com/defnalk/laidlaw) | CCS vs. electrification decision-support tool |
| [`lab-watcher`](https://github.com/defnalk/lab-watcher) | Polyglot CLI for lab CSV validation (C++/Java/Node) |

---

## 🛠️ Technical stack

**Scientific Python**
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/-SciPy-8CAAE6?logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/-pandas-150458?logo=pandas&logoColor=white)
![matplotlib](https://img.shields.io/badge/-matplotlib-11557C)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?logo=pytest&logoColor=white)
![mypy](https://img.shields.io/badge/-mypy-2A6DB2)
![ruff](https://img.shields.io/badge/-ruff-000000)

**Data engineering**
![Postgres](https://img.shields.io/badge/-Postgres-4169E1?logo=postgresql&logoColor=white)
![dbt](https://img.shields.io/badge/-dbt-FF694B?logo=dbt&logoColor=white)
![Prefect](https://img.shields.io/badge/-Prefect-024DFD?logo=prefect&logoColor=white)
![Pandera](https://img.shields.io/badge/-Pandera-007ACC)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?logo=streamlit&logoColor=white)

**Platform & infra**
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

**Systems**
![Java](https://img.shields.io/badge/-Java%2FSpring-007396?logo=spring&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?logo=postgresql&logoColor=white)

---

## 🎯 What I care about in code

I like building software that is **physically grounded**, **well-tested**, **typed and readable**, and **useful beyond a single notebook or class project**.

Scientific modelling · Process systems · Thermodynamics · Heat and mass transfer · ETL pipelines

---

## 📈 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=defnalk&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=default" alt="Defne's GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=defnalk&layout=compact&hide_border=true&langs_count=8&theme=default" alt="Top languages"/>
</p>

---

## 🌱 Currently interested in

Climate tech · Energy systems · Scientific software · Data engineering for climate · Technical product work · Modelling · Research-driven engineering

---

## 📫 Get in touch

- 📧 [defne.ertugrul22@imperial.ac.uk](mailto:defne.ertugrul22@imperial.ac.uk)
- 💼 Open to internships, research collaborations, and climate-tech roles
