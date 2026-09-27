# Masters Thesis

LaTeX source files for Michael Montemurri's master's thesis:

**Hybrid Graph Representation Learning for Molecular Optical Property Prediction in Low-Data Regimes**

## Build

From this directory, run:

```bash
latexmk -pdf main.tex
```

The main thesis entry point is `main.tex`.

## Contents

- `Chapters/`: thesis chapter source files
- `Manuscript/`: manuscript content and figures included in the thesis
- `Images/`: thesis images used outside the manuscript
- `references.bib`: bibliography database
- `main.xmpdata`: PDF metadata used by `pdfx`

Generated build files and PDFs are ignored by Git.
