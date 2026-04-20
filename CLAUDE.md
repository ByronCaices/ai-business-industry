# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

Course material for **"IA Aplicada a la Industria"** (AI Applied to Industry) — a 16-week program at Universidad de Santiago de Chile for Industrial Engineering students. The focus is strategic and interpretive use of AI, not deep programming. Students run pre-written Python notebooks and analyze results.

## Repository Structure

- `Clases Laboratorios/` — Lecture materials: LaTeX slide decks (`clase1.tex`), in-class example notebooks (`clase1_ejemplos.ipynb`), and slide-summary guides (`guia-clase1.md`).
- `Laboratorios y Proyecto Final/Laboratorios y Proyecto Final/` — Student-facing lab notebooks (`Laboratorio_1.ipynb` … `Laboratorio_12.ipynb`) and `Proyecto_Final.ipynb`. These are templates meant to be run by students.
- `Laboratorios y Proyecto Final EJECUTADO/Laboratorios y Proyecto Final EJECUTADO/` — Fully executed reference versions of each lab (`EJEC_Laboratorio_*.ipynb`, `EJEC_Proyecto_Final.ipynb`). These show expected outputs.
- `resumen_curso.md` — Authoritative course program reference: units, weekly schedule, evaluation breakdown, and bibliography.

## Notebook Conventions

- **Template notebooks** (in `Laboratorios y Proyecto Final/`) have empty or minimal cell outputs — students fill them in.
- **Executed notebooks** (prefixed `EJEC_`) are the reference answers with full outputs. When adding a new lab, create both versions.
- Notebooks run on **Google Colab** or Jupyter. Avoid OS-specific paths; use relative paths or Google Drive mounts.
- Standard stack: `pandas`, `numpy`, `scikit-learn`, `keras`/`tensorflow`, `matplotlib`.

## Running Notebooks Locally

```bash
# Install dependencies (if not using Colab)
pip install pandas numpy scikit-learn tensorflow matplotlib jupyter

# Launch Jupyter
jupyter notebook
```

In Google Colab, open via `colab.research.google.com` and upload or open from Drive.

## Lecture Slides

Slides are authored in LaTeX (`Clases Laboratorios/clase1.tex`). Compile with:

```bash
pdflatex clase1.tex
```

## Evaluation Structure

- **Lab reports (50%)**: 10 reports based on weekly lab execution (Labs 1–10 align with Weeks 3–12).
- **Final project (50%)**: Strategic analysis of a real industrial AI case (Weeks 13–16).

Labs 11 and 12 exist as additional material beyond the graded 10. `Respuestas Laboratorios con alternativas.xlsx` and `Respuestas Laboratorios 9 al 11.docx` contain answer keys.
