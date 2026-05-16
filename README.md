# Defne Nihal Ertugrul

**MEng Chemical Engineering @ Imperial College London**

---

## About

Building at the boundary of simulation, data, and energy systems.
---

## Featured Project: `meapy`

[![meapy CI](https://github.com/defnalk/meapy/actions/workflows/ci.yml/badge.svg)](https://github.com/defnalk/meapy/actions/workflows/ci.yml)
[![Release](https://github.com/defnalk/meapy/actions/workflows/release.yml/badge.svg)](https://github.com/defnalk/meapy/actions/workflows/release.yml)
[![CodeQL](https://github.com/defnalk/meapy/actions/workflows/codeql.yml/badge.svg)](https://github.com/defnalk/meapy/actions/workflows/codeql.yml)
[![mypy strict](https://img.shields.io/badge/mypy-strict-2A6DB2)](https://github.com/defnalk/meapy)
[![cosign](https://img.shields.io/badge/images-signed%20with%20cosign-4B0082)](https://github.com/defnalk/meapy)

A typed, tested Python package for the core calculations used in MEA based **carbon capture pilot plant** commissioning and evaluation, wrapped in the rigour of a production service:

- 124 unit tests, ≥ 90 % coverage, `mypy --strict`, ruff lint+format
- Multi stage Docker image (non root, < 150 MB) + Lambda and Cloud Run variants
- GitHub Actions CI across **py3.10/3.11/3.12 × Ubuntu/macOS**, Codecov, Docker Scout
- Tag driven release: TestPyPI → PyPI (OIDC) → multi arch GHCR with **cosign signed images** + **SPDX SBOM attestation**
- Terraform IaC for **AWS Lambda** (arm64 container, ECR, IAM least priv, Function URL or API Gateway v2) and **GCP Cloud Run**
- Keyless deploys via GitHub OIDC trust role · CodeQL · Dependabot · CODEOWNERS

→ [github.com/defnalk/meapy](https://github.com/defnalk/meapy)

---

## What I'm Building

| Repository | Description |
|:-----------|:------------|
| [`SURF2026`](https://github.com/defnalk/SURF2026) | Molecular simulation of electrochemical interfaces, Caltech SURF 2026, Fong Lab |
| [`meapy`](https://github.com/defnalk/meapy) | Typed Python library for MEA carbon capture pilot plant calculations |
| [`energyemissions`](https://github.com/defnalk/energyemissions) | End to end ETL pipeline for EU ETS emissions: Pandera → Postgres → dbt → Streamlit |
| [`laidlaw`](https://github.com/defnalk/laidlaw) | Decision support tool comparing CCS retrofits vs. electrification for hard to abate industries |
| [`sepflows`](https://github.com/defnalk/sepflows) | Composable building blocks for separation process design: distillation, absorption, membranes |

---

## Skills & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LAMMPS](https://img.shields.io/badge/LAMMPS-800020?style=flat)
![GROMACS](https://img.shields.io/badge/GROMACS-2E8B57?style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![MDAnalysis](https://img.shields.io/badge/MDAnalysis-FF6F00?style=flat)
![matplotlib](https://img.shields.io/badge/matplotlib-11557C?style=flat)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat&logo=latex&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Research Interests

- **Electric double layers**: structure and dynamics of ions at electrified solid/liquid interfaces
- **Ion transport**: diffusion and migration mechanisms in confined electrolytes
- **Direct air capture**: sorbent design, process modelling, and technoeconomic analysis
- **Process systems engineering**: optimisation and control of large scale chemical processes

---

  </a>
</p>
