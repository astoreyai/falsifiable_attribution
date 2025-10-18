# Falsifiable Attribution for Face Verification Systems

**A Dissertation on Counterfactual Validation in Forensic Contexts**

By Aaron Storey

---

## Overview

This repository contains the LaTeX source for a PhD dissertation on developing falsifiable attribution methods for face verification systems. The research addresses the critical gap in explainable AI (XAI) where current methods lack rigorous validation frameworks, particularly for high-stakes forensic and legal applications.

### Key Research Contributions

1. **Falsifiable Attribution Framework** - First formal mathematical framework for attribution falsifiability in pairwise verification
2. **Theoretical Bounds** - Computational and geometric limits on attribution faithfulness in face embedding spaces
3. **Counterfactual Prediction System** - Algorithm with uncertainty quantification for score prediction
4. **Plausibility-Preserving Perturbations** - Face manifold-aware perturbation strategies
5. **Systematic Evaluation** - Comprehensive testing of attribution methods (Grad-CAM, SHAP, IG, LIME)
6. **Benchmark Suite** - Ground truth test cases for face verification XAI
7. **Open-Source Framework** - Reproducible implementation (MIT license)
8. **Deployment Guidelines** - Evidence-based thresholds for forensic/legal contexts

---

## Project Status

### ✅ Completed

- [x] Chapter 1: Introduction (LaTeX conversion complete)
- [x] Bibliography file (preliminary, 97 citations)
- [x] Directory structure setup
- [x] Analysis documents (theoretical, structural, citations)
- [x] Main thesis file (main.tex)

### 🚧 In Progress

- [ ] Chapter 2: Literature Review
- [ ] Chapter 3: Theoretical Foundations
- [ ] Chapter 4: Methodology
- [ ] Chapter 5: Implementation
- [ ] Chapter 6: Experimental Results
- [ ] Chapter 7: Discussion
- [ ] Chapter 8: Conclusion

### 📋 Planned

- [ ] Figures for Chapter 1 (5 recommended)
- [ ] Tables for Chapter 1 (4 recommended)
- [ ] Complete bibliography verification
- [ ] Appendices

---

## Directory Structure

```
falsifiable_attribution/
├── main.tex                              # Main thesis file
├── ThesisProposal.cls                    # Document class (template)
├── lstpatch.sty, vector.sty              # Style files
├── preliminary_bibliography.bib          # BibTeX citations (97 entries)
│
├── Chapters/
│   ├── Ch 1 - Introduction.tex          # ✅ Complete (817 lines)
│   ├── Ch 2 - Literature Review.tex     # 🚧 To be created
│   ├── Ch 3 - Theory.tex                # 🚧 To be created
│   ├── Ch 4 - Methodology.tex           # 🚧 To be created
│   ├── Ch 5 - Implementation.tex        # 🚧 To be created
│   ├── Ch 6 - Results.tex               # 🚧 To be created
│   ├── Ch 7 - Discussion.tex            # 🚧 To be created
│   └── Ch 8 - Conclusion.tex            # 🚧 To be created
│
├── Appendices/                          # Supplementary materials
├── figures/                             # Figures and diagrams
├── tables/                              # Table data
├── Datasets/                            # Dataset documentation
│
└── Analysis Documents/                  # Deep analysis by Opus agents
    ├── analysis_theoretical_framework.md    # Theoretical architecture
    ├── analysis_structure_narrative.md      # Structural analysis
    ├── analysis_citations.md                # Citation analysis (97 refs)
    ├── conversion_notes.md                  # LaTeX conversion details
    ├── TEMPLATE_ANALYSIS_INDEX.md           # Template comparison
    └── [other analysis files]
```

---

## Compilation Instructions

### Prerequisites

```bash
# Required LaTeX packages
- texlive-full (or equivalent)
- biblatex
- biber (for bibliography)
```

### Build Commands

```bash
# Standard compilation
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex

# Or use latexmk (recommended)
latexmk -pdf -pvc main.tex
```

### Current Status

⚠️ **Bibliography file needs completion**: While preliminary citations are in place, full bibliographic details are needed for all 97 references before successful compilation.

---

## Key Features

### Chapter 1 Highlights

- **Real-world motivation**: Documents 3 wrongful arrest cases (Williams, Woodruff, Parks)
- **Legal framework**: EU AI Act, GDPR, Daubert standard, Federal Rules of Evidence 702
- **Research questions**: 4 progressive RQs with theoretical foundations
- **8 Contributions**: Categorized as theoretical (2), algorithmic (2), empirical (2), applied (2)
- **Comprehensive scope**: Defines what is in/out of scope, acknowledges limitations
- **Mathematical rigor**: Full notation section with proper LaTeX formatting

### LaTeX Quality

- Professional typography (em-dashes, en-dashes, proper quotes)
- Lettrine drop cap chapter opening
- 120+ citations properly formatted
- Mathematical notation in proper math mode
- Cross-references with `\label{}` and `\ref{}`
- Template-compliant structure

---

## Analysis Documents

This repository includes ultra-deep analysis performed by specialized Opus-level agents:

### 1. Theoretical Framework Analysis
**File**: `analysis_theoretical_framework.md` (52 KB)

- Theoretical architecture (3-tier argumentative structure)
- Mathematical framework extraction (falsifiability conditions, thresholds)
- 8 contributions categorized and dependency-mapped
- Citation landscape (98 unique references)
- Critical tensions identified (ground truth paradox, scalability vs rigor)

### 2. Structural & Narrative Analysis
**File**: `analysis_structure_narrative.md` (93 KB)

- 4-stage narrative escalation strategy
- Section-by-section breakdown
- Wrongful arrest case details extraction
- Regulatory framework integration
- LaTeX enhancement recommendations (5 tables, 4 figures)

### 3. Citation Analysis
**File**: `analysis_citations.md` (33 KB)

- 97 unique citations categorized into 15 major categories
- 10 strategic citation clusters identified
- Temporal analysis (1959-2024, 65-year span)
- Interdisciplinary breadth analysis (40% CV, 35% XAI, 10% Legal, 5% Journalism)
- Priority verification actions (legal citations, journalism sources)

### 4. LaTeX Conversion Documentation
**File**: `conversion_notes.md` (21 KB)

- Detailed conversion decisions with rationale
- Challenges encountered and solutions
- Quality assurance verification
- Recommendations for next steps
- Estimated work remaining (21-26 hours)

---

## Source Material

This dissertation is being reformatted from the original source at:

```
/home/aaron/projects/xai/PHD_PIPELINE/falsifiable_attribution_dissertation/
```

The original contains:
- 8 chapter files (chapters/)
- Implementation code (src/, code/experiments/)
- Datasets (data/ - 7.6 GB)
- Figures and tables
- Comprehensive documentation

---

## Next Steps

### Immediate Priority (Critical)

1. **Complete Bibliography** (4-6 hours)
   - Verify all 97 citation entries
   - Add full bibliographic details
   - Check legal citation formats

2. **Test Compilation** (30 minutes)
   - Run pdflatex + biber
   - Fix undefined references
   - Verify all packages available

### Short-term (1-2 weeks)

3. **Create Essential Tables** (2 hours)
   - Table 1.1: Research Questions Summary
   - Table 1.2: Eight Contributions Summary
   - Table 1.3: Datasets Overview
   - Table 1.4: Wrongful Arrest Cases

4. **Create Priority Figure** (2-3 hours)
   - Figure 1.1: Counterfactual Falsification Framework

5. **Convert Remaining Chapters** (40-80 hours)
   - Chapter 2: Literature Review (largest, 142 KB)
   - Chapters 3-8: Theory, Methodology, Implementation, Results, Discussion, Conclusion

### Long-term (1-2 months)

6. **Add Remaining Figures** (8-10 hours)
   - 4 additional figures for Chapter 1
   - Figures for other chapters

7. **Enhance Formatting** (2 hours)
   - Callout boxes for key definitions
   - Clickable table of contents
   - PDF metadata optimization

---

## Research Context

### Problem

Face verification systems are deployed in high-stakes contexts (law enforcement, border security) but suffer from:
- **Accuracy disparities**: 10-100× higher false positive rates for certain demographics
- **Opacity**: Deep neural networks are fundamentally opaque "black boxes"
- **Wrongful arrests**: Documented cases where lack of explainability enabled miscarriages of justice
- **Regulatory pressure**: EU AI Act, GDPR demand "transparent and comprehensible" decisions
- **XAI validation gap**: No rigorous method to verify if explanations are faithful vs. plausible confabulations

### Solution

This dissertation develops a **counterfactual falsifiability framework**:

1. **Reformulate attributions as testable hypotheses**: "If feature F is important, perturbing F should change score by Δs"
2. **Enable empirical testing**: Generate counterfactual perturbations, measure actual score changes
3. **Provide falsifiability criteria**: Formal conditions for when an explanation can be trusted
4. **Establish deployment thresholds**: Quantitative criteria for forensic/legal use (>80% operational, >95% criminal proceedings)

### Impact

- **Scientific rigor**: Move XAI from subjective interpretability to objective falsifiability
- **Legal compliance**: Meet Daubert standard for scientific evidence
- **Prevent injustice**: Provide tools to detect erroneous explanations before wrongful arrests
- **Enable accountability**: Allow auditing of face verification systems in high-stakes contexts

---

## Citation

If you use this work, please cite:

```bibtex
@phdthesis{storey2025falsifiable,
  title={Falsifiable Attribution for Face Verification Systems: Counterfactual Validation in Forensic Contexts},
  author={Storey, Aaron},
  year={2025},
  school={[Institution]},
  note={In preparation}
}
```

---

## License

**Dissertation Content**: © 2025 Aaron Storey. All rights reserved.

**Code & Framework** (when released): MIT License

---

## Contact

**Author**: Aaron Storey
**Email**: storeyaw@clarkson.edu
**GitHub**: https://github.com/astoreyai/falsifiable_attribution

---

## Acknowledgments

This work draws on extensive prior research in:
- Explainable AI (Grad-CAM, SHAP, Integrated Gradients, LIME)
- Face verification (ArcFace, CosFace, FaceNet)
- Evaluation frameworks (sanity checks, insertion-deletion metrics)
- Legal/regulatory frameworks (EU AI Act, GDPR, Daubert standard)
- Documented wrongful arrest cases (Williams, Woodruff, Parks)

Special thanks to the XAI research community, forensic science standards bodies, and civil liberties organizations documenting algorithmic accountability failures.

---

**Last Updated**: October 17, 2025
**Status**: Chapter 1 complete, Chapters 2-8 in progress
**Estimated Completion**: [Date TBD]
