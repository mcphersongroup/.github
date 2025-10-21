<!-- .github/profile/README.md -->

<p align="center">
  <img src="https://img.shields.io/badge/Discipline-Pharmacology-informational" alt="Pharmacology badge">
  <img src="https://img.shields.io/badge/Focus-PK%2FPD-blue" alt="PK/PD badge">
  <img src="https://img.shields.io/badge/Areas-AMR%20%7C%20Microbiome%20%7C%20C._difficile-orange" alt="Areas badge">
  <img src="https://img.shields.io/badge/Methods-R%20%7C%20Python%20%7C%20Quarto%20%7C%20Docker-success" alt="Methods badge">
</p>

<h1 align="center">McPherson Group</h1>
<p align="center"><em>A research group of pharmacists, scientists, and clinician-scientists advancing pharmacology through open, reproducible science.</em></p>

---

## 👋 Who we are
We study how drugs move through and act within complex biological systems—linking **pharmacokinetics (PK)**, **pharmacodynamics (PD)**, and **microbiome-host interactions** to improve anti-infective therapy. 
We emphasize:
- **Antimicrobial resistance (AMR)** and microbiome-sparing antibiotics 
- **C. difficile** pathobiology, bile acids, and colonization resistance  
- **Mechanistic PK/PD modeling**, **exposure–response**, and **fitness landscapes**  
- **Reproducible pipelines** (R/Python, Quarto, Docker, GitHub Actions)

---

## 🔗 Quick links
- 🌐 Website: **[mcphersongroup.github.io](https://mcphersongroup.github.io)**
- 📚 Publications: **[Google Scholar](https://scholar.google.com/citations?user=MsZPCoIAAAAJ&hl=en)**
- 🧑‍💻 Recruting / Collaboration: **[JOIN_US_URL](https://mcphersongroup.github.io/people/join.html)**
- ✉️ Contact: **[CONTACT_EMAIL](mailto:jacobmcpherson@utexas.edu;jkmcpherson@uh.edu;jacob@jacobkmcpherson.com)**

<p>
  <a href="[ORCID_URL]"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0000-0001-5486-4945-brightgreen"></a>
  <a href="[LICENSE_URL]"><img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
</p>

---

## 🧭 What we work on
- **PK/PD for anti-infectives**: target attainment, PTA/MIC distributions, dose optimization  
- **Microbiome pharmacology**: bile acids, SCFAs, colonization resistance, narrow-spectrum agents  
- **Computational pipelines**: 16S + shotgun, ASVs, metagenomic classification, reproducible reports  
- **Translational frameworks**: clinical decision support, stewardship, prospective monitoring

---

## 📦 Featured projects
> Pin or star key repos so they appear below; list anchors here for clarity.

- **[project-pkpd-models](https://github.com/ORG_OR_USER/project-pkpd-models)** – Nonlinear mixed-effects / Monte Carlo simulation templates for dose finding  
- **[microbiome-pipelines](https://github.com/ORG_OR_USER/microbiome-pipelines)** – Reproducible amplicon + shotgun workflows (R/Python, Quarto, Docker)  
- **[cdi-bile-acids](https://github.com/ORG_OR_USER/cdi-bile-acids)** – Bile acid profiling + colonization resistance analyses  
- **[quarto-lab-style](https://github.com/ORG_OR_USER/quarto-lab-style)** – Shared theme, color tokens, and figure style guide for publications

---

## 🗂️ Datasets & resources
- **Clinical PK datasets** (anonymized / simulated): **[LINK]**  
- **AMR susceptibility panels & MIC distributions**: **[LINK]**  
- **Reference genomes / taxonomies** (manifest + checksums): **[LINK]**

> Please review data use terms and cite the DOI(s) listed in each repository.

---

## 🛠️ Software & reproducibility
- **Languages**: R, Python  
- **Docs/Reports**: Quarto; CI with GitHub Actions → HTML/PDF  
- **Containers**: Docker (per-repo `Dockerfile` and `compose.yaml`)  
- **Envs**: `renv` (R) / `conda` or `uv` (Python)  
- **QA**: unit tests, linting, and pre-commit hooks

```mermaid
flowchart LR
  A(Code) --> B(Tests & Lint)
  B --> C(Docker Build)
  C --> D(CI: Render Quarto)
  D --> E(Artifacts: HTML/PDF)
  E --> F(Release + Zenodo DOI)
