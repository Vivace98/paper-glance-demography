# Paper-Glance-Demography

An AI-assisted academic reading workflow for demography, migration studies, and quantitative social science research.

This repository provides reusable research-oriented skills for:

- literature screening
- literature synthesis
- deep paper reading
- theory extraction
- methodological reconstruction
- research workflow automation

Designed for Codex / Claude-style agent workflows.

---

# Workflow

The repository follows a three-stage academic reading pipeline:

## 1. `paper-matrix-extract`

Rapidly extracts structured information from a single academic paper and converts it into a literature matrix entry.

Focus:

- rapid screening
- variable extraction
- theory extraction
- method identification
- Excel / TSV literature matrix generation

---

## 2. `literature-pattern-analysis`

Analyzes a literature matrix and identifies:

- dominant theories
- common methods
- variable patterns
- recurring mechanisms
- research gaps
- under-studied combinations

Focus:

- literature review synthesis
- field mapping
- research gap detection

---

## 3. `paper-research-core`

Performs deep structured reading of important papers.

Focus:

- research question reconstruction
- literature review logic
- data and modeling strategy
- identification assumptions
- contribution and limitations
- critical evaluation

The goal is not only to summarize papers, but to reconstruct the research logic behind them.

---

# Repository Structure

```text
Paper-Glance-Demography/
│
├── README.md
│
└── skills/
    ├── paper-matrix-extract/
    │   └── SKILL.md
    │
    ├── literature-pattern-analysis/
    │   └── SKILL.md
    │
    └── paper-research-core/
        └── SKILL.md
```

---

# Installation / Usage

Place the `skills/` folder inside the root directory of your Codex or Claude workflow environment.

Example:

```text
codex-project/
│
├── skills/
│   ├── paper-matrix-extract/
│   ├── literature-pattern-analysis/
│   └── paper-research-core/
│
└── ...
```

The skills can then be invoked directly by the agent.

---

# Intended Use

This repository is designed for:

- literature review
- thesis preparation
- demographic research
- migration studies
- social science research
- AI-assisted academic workflows

---

# Research Areas

Primary focus areas include:

- Demography
- Migration Studies
- Gender and Inequality
- Educational Research
- Quantitative Social Science
- Bayesian and Statistical Thinking
