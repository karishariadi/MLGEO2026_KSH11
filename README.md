# MLGEO2026_KSH11

Course repository for Machine Learning in the Geosciences.

My goal for this course is to learn how to build and evaluate reproducible
machine-learning workflows for geoscience data.

## How to run

This repository uses Pixi to manage the course environment.

Install the environment:

```bash
pixi install
```

Run the smoke test:

```bash
pixi run smoke
```

A successful test ends with:

```text
smoke test passed
```

## Reproducibility check

From a fresh clone, run:

```bash
git clone https://github.com/karishariadi/MLGEO2026_KSH11.git
cd MLGEO2026_KSH11
pixi install
pixi run smoke
```

The smoke test checks that the required Python environment works and performs a
small numerical calculation. A successful run ends with:

```text
smoke test passed
```

The environment was tested in GitHub Codespaces on Linux x86_64.

## Working with notebooks

Start JupyterLab from the repository root:

```bash
pixi run lab
```

Open the forwarded port 8888 in Codespaces. Run notebooks from top to bottom
after restarting the kernel. Save notebooks before committing them.

## Git workflow

Before starting work:

```bash
git pull
```

After making changes:

```bash
git status
git add FILE_NAME
git commit -m "Describe the change"
git push
```

## Data and provenance

This repository does not currently contain a project dataset. When data are
added, the README will record the source URL or DOI, version, retrieval date,
units, and processing steps. Raw data will remain unchanged, and processed
data will be written separately.

## AI assistance

AI assistance was used for troubleshooting the course environment and
documenting the HW1 verification process. Commands were checked in the
Codespaces terminal, and the verification records are stored in `AI_logs/`.