# Hi, I'm Defne 👋

I'm a Chemical Engineering student at Imperial College London building scientific Python tools and data systems for carbon capture, energy systems, process modelling, and thermal systems.

My work sits at the intersection of **carbon capture and pilot plant analysis**, **reactor and separation process modelling**, **solar and nuclear energy systems**, **data engineering for climate datasets**, and **scientific software engineering**.

---

## Start here

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

## What I care about in code

I like building software that is **physically grounded**, **well-tested**, **typed and readable**, and **useful beyond a single notebook or class project**.

---

## Technical stack

**Scientific Python:** NumPy · SciPy · pandas · matplotlib · pytest · mypy · Ruff
**Data engineering:** Postgres · dbt · Prefect · Pandera · Streamlit · Docker
**Systems:** Java/Spring · C++ · Go · SQL

Scientific modelling · Process systems · Thermodynamics · Heat and mass transfer · ETL pipelines

---

## Selected repositories

| Repository | Description |
|---|---|
| [`meapy`](https://github.com/defnalk/meapy) | MEA carbon capture pilot-plant calculations |
| [`energyemissions`](https://github.com/defnalk/energyemissions) | EU ETS ETL pipeline (dbt + Prefect + Streamlit) |
| [`tandem-solar`](https://github.com/defnalk/tandem-solar) | Tandem solar cell/module simulation |
| [`cooltower`](https://github.com/defnalk/cooltower) | Cooling tower psychrometrics and controls |
| [`htgr-desalination`](https://github.com/defnalk/htgr-desalination) | HTGR + MED desalination simulation |
| [`formaldehyde-reactor`](https://github.com/defnalk/formaldehyde-reactor) | Packed-bed PFR model |
| [`sepflows`](https://github.com/defnalk/sepflows) | Composable separation-process building blocks |
| [`laidlaw`](https://github.com/defnalk/laidlaw) | CCS vs. electrification decision-support tool |
| [`lab-watcher`](https://github.com/defnalk/lab-watcher) | Polyglot CLI for lab CSV validation (C++/Java/Node) |

---

## Currently interested in

Climate tech · Energy systems · Scientific software · Data engineering for climate · Technical product work · Modelling · Research-driven engineering
