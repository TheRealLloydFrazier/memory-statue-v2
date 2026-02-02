# Paper Source Files

This folder contains the LaTeX source and figures for the Memory Statue v2 paper.

## Contents

- `main.tex` - LaTeX source file
- `figures/` - Figure images (JPG)
  - `fig1_architecture_cropped.jpg`
  - `fig2_retrieval_pipeline_cropped.jpg`
  - `fig3_drift_loop_cropped.jpg`
  - `fig4_validation_harness_cropped.jpg`
- `Memory_Statue_v2_v1.4.4_publish.md` - Markdown version of the paper

## Building the PDF

From this directory:

```bash
# Using latexmk (recommended)
latexmk -pdf -interaction=nonstopmode main.tex

# Or manual compilation
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Note

Upload your LaTeX source files and figures to this directory.
The compiled PDF should go in the `release/` folder.
