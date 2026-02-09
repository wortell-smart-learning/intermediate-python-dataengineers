# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

Training companion repository for Wortell Smart Learning's "Intermediate Python for Data Engineers" course. Contains Jupyter notebooks organized as 8 modules, each with an exercise notebook and an answers notebook. Content is written in English.

## Setup

```bash
pip install -r requirements.txt
```

Dependencies: pandas, requests, numpy, matplotlib, scikit-learn, azure-storage-blob, sqlalchemy, grequests, thefuzz, pyodbc.

No build system or test suite — run notebooks directly with Jupyter.

## Structure

- **Module 1–8 directories** — Each contains `Module N; Topic.ipynb` (exercises) and `Module N; Topic - Answers.ipynb` (solutions). Some modules include data files (XML, pickle) used by the notebooks.
- **Supplementary/** — Supplementary topic notebooks (async requests, auth headers, config files, deduplication, CSV handling, SQL connections) used as optional add-ons during training.
- **Usecase/** — End-of-training capstone exercise combining multiple module concepts.
- **templates/** — `template_module.ipynb` defines the standard notebook structure for creating new modules.

## Notebook Conventions

- Notebooks follow a repeating pattern: theory/concept explanation (markdown) → example code (embedded in markdown, not executed) → exercises for participants.
- Exercise code cells use `### FILL IN; START` / `### FILL IN; END` markers to indicate where participants write code.
- Answers notebooks contain the same exercises with completed solutions. Each solution code cell is preceded by a markdown explanation cell describing the approach, key concepts, and common pitfalls.
- Keep theory sections short and interactive with frequent alternation between explanation and practice. Reference library documentation where relevant.

## Language

All notebook content is written in English.
