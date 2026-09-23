# Introduction to Programming — Space Engineering

Course materials for the 2026/2027 Introduction to Programming course.

## Quick start

```text
conda env create -f environment.yml
conda activate space-programming
jupyter lab
```

Student notebooks are in `labs/student/`. Open the current lab from JupyterLab and save your work regularly.

## Repository layout

| Path | Purpose |
|---|---|
| `labs/student/` | Student lab notebooks |
| `assignments/` | Longer assessed tasks and project briefs |
| `data/raw/` | Original small course datasets; do not edit in place |
| `data/processed/` | Reproducible derived data; normally ignored by Git |
| `assets/` | Images and other files used by notebooks |
| `scripts/` | Reusable setup and data preparation scripts |
| `tests/public/` | Tests students may run themselves |
| `docs/` | Setup, policies, and reference material |

Large datasets should normally be downloaded by a script or distributed through an external data archive instead of committed directly. Instructor solutions and hidden tests belong in a separate private repository, not in this repository or its Git history.
