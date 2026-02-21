# Ultrafilter Aggregation of ∆0-Definable Fragments and Induced Hilbert Structures
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18720082.svg)](https://doi.org/10.5281/zenodo.18720082)

Author: Jürgen Bigalke
Status: Preprint (Version 1.0)  
Discipline: Mathematical Logic (math.LO)  
---

## Overview

This repository contains the LaTeX source and compiled PDF of a research article
developing a structural framework based on bounded Δ₀-definability over the
Jensen level

    J₂ = rud(HF).

The central objective is to analyse how countable families of locally Δ₀-definable fragments over
(J₂, ∈) give rise to canonical global comparison structures via ultrafilter
aggregation.

The work is strictly formulated over J₂ = rud(HF). No admissible background
structures beyond J₂ are assumed.

---

## Foundational Framework

We work with the initial levels of Jensen’s hierarchy:

    J₀ = ∅
    J₁ = HF
    J₂ = rud(HF)

All definability notions refer to bounded (Δ₀) definability over (J₂, ∈),
with parameters from J₂.

Ultrasheaves are treated as second-order aggregation classes of countable
families of locally Δ₀-definable fragments via a fixed non-principal
ultrafilter. They are not elements of J₂ but are definable over it.

The framework distinguishes strictly between:

- internal generability in J₂,
- global reconstructibility via aggregation.

This distinction yields a structural notion referred to as a
Reconstruction Gap.

---

## Main Contributions

The article establishes:

1. Canonical comparison kernels induced by Δ₀-definable local invariants.
2. Structural conditions under which these kernels are positive semidefinite.
3. Uniqueness up to unitary equivalence of the induced Hilbert-space
   representation (when positivity holds).
4. Formal separation between internal definability and global
   reconstruction coherence.

All results are formulated entirely within the definability constraints
of J₂.

---

## Repository Structure

/src  
    main.tex  
    preamble-base.tex  
    refs.bib  

/pdf  
    main_v1.pdf  

---

## Versioning

Tagged releases correspond to stable preprint versions.

v1.0 – Initial public release.  

Subsequent minor revisions will be versioned incrementally.

---

## Citation

If you wish to cite this work, please reference the DOI.

BibTeX entry 
```bibtex
@misc{Bigalke2026,
  author       = {Bigalke, Jürgen},
  title        = {Ultrafilter Aggregation of $\Delta_0$-Definable Fragments and Induced Hilbert Structures},
  year         = {2026},
  howpublished = {Zenodo},
  doi          = {10.5281/zenodo.18720082}
}
```
---

## License

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

---

## Disclaimer

This manuscript is a preprint and has not yet undergone peer review.
The contents may evolve in subsequent versions.

---

## Contact

For correspondence regarding the manuscript, please open an issue
in this repository.
