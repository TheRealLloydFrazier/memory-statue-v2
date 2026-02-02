# Memory Statue v2: A Structured Memory Architecture for Long-Horizon AI Agents

**Author:** Lloyd D. Frazier  
**Date:** 2026-01-29  
**DOI:** [https://doi.org/10.5281/zenodo.18452213](https://doi.org/10.5281/zenodo.18452213)

This repository contains the preprint and accompanying artifacts for **Memory Statue v2**, a structured memory architecture for long-horizon AI agents designed to make memory behavior **testable, governable, and resistant to drift**.

## What is this?

Memory Statue v2 is a blueprint for drift-resistant, long-horizon memory in agentic systems—with explicit artifacts, retrieval gates, and a test harness you can actually run. It treats memory like a reliability problem: logs, audits, failure criteria—not vibes.

**The one-sentence pitch:**  
Memory Statue v2 is a structured memory architecture for long-horizon AI agents that makes memory behavior testable, governable, and resistant to drift.

## Canonical record

The canonical archived release lives on Zenodo:
- **DOI:** [https://doi.org/10.5281/zenodo.18452213](https://doi.org/10.5281/zenodo.18452213)

## How to cite

**Cite as:**
> Frazier, Lloyd D. (2026). *Memory Statue v2: A Structured Memory Architecture for Long-Horizon AI Agents.* Zenodo. https://doi.org/10.5281/zenodo.18452213

**BibTeX:**
```bibtex
@article{frazier2026memorystatue,
  title={Memory Statue v2: A Structured Memory Architecture for Long-Horizon AI Agents},
  author={Frazier, Lloyd D.},
  year={2026},
  month={1},
  day={29},
  publisher={Zenodo},
  doi={10.5281/zenodo.18452213},
  url={https://doi.org/10.5281/zenodo.18452213}
}
```

## Repository contents

```
memory-statue-v2/
├── README.md                  (this file)
├── LICENSE                    (source-available, non-commercial)
├── CITATION.cff              (machine-readable citation)
├── CHANGELOG.md              (version history)
├── paper/
│   ├── main.tex              (LaTeX source)
│   ├── figures/
│   │   ├── fig1_architecture_cropped.jpg
│   │   ├── fig2_retrieval_pipeline_cropped.jpg
│   │   ├── fig3_drift_loop_cropped.jpg
│   │   └── fig4_validation_harness_cropped.jpg
│   └── Memory_Statue_v2_v1.4.4_publish.md (Markdown version)
└── release/
    └── Memory_Statue_v2_v1_4_4_arxiv_source_DOI.pdf
```

## Build the PDF from source

From the `paper/` directory containing `main.tex`:

```bash
# Using latexmk (recommended)
latexmk -pdf -interaction=nonstopmode main.tex

# Or manual compilation
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Resource hub

For supporting visuals, diagrams, terminology cards, and updates:
- [https://epicdreamsaisolutions.com/](https://epicdreamsaisolutions.com/)

## Key features

- **Structured storage**: Memory stored in typed objects (capsules) with explicit fields
- **Deterministic retrieval**: Pipeline with clear stages, budgets, and policies
- **Governed canon**: Controlled promotion of canonical knowledge (CANON)
- **Maintenance routines**: Drift reduction via annealing (re-embed, summarize, repair)
- **Auditability**: Append-only trail for all memory changes
- **Validation harness**: Measures memory health, not just task metrics

## License

This project is **source-available and non-commercial**. See [LICENSE](LICENSE) for full terms (verbatim from §11.1 of the paper).

**TL;DR:**
- ✅ **Non-commercial use**: Research, education, personal study (with attribution)
- ❌ **Commercial use**: Requires separate negotiated license
- 🤝 **Community sharing**: Encouraged but not required

## Contributing

Users are encouraged to share use cases, implementation notes, and empirical findings—publicly or privately, anonymized/redacted is acceptable. Commercial teams interested in collaboration: contact the author.

## Version

- **Current version:** v1.4.4
- **Released:** 2026-01-29
- See [CHANGELOG.md](CHANGELOG.md) for version history

---

**Contact:** For licensing inquiries or collaboration opportunities, visit [Epic Dreams AI Solutions](https://epicdreamsaisolutions.com/)
