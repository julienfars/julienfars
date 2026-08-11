---
title: "Stargardt Disease — Temporal Contrast Sensitivity Analysis"
excerpt: "R analysis code behind our study comparing L-cone-, S-cone-, and rod-driven perifoveal temporal contrast sensitivity in patients with Stargardt disease/Fundus Flavimaculatus."
collection: code
language: "R"
github: "https://github.com/julienfars/Stargardt_paper_2021"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-Stargardt__paper__2021-181717?logo=github)](https://github.com/julienfars/Stargardt_paper_2021)
[![License](https://img.shields.io/github/license/julienfars/Stargardt_paper_2021)](https://github.com/julienfars/Stargardt_paper_2021/blob/master/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/Stargardt_paper_2021)](https://github.com/julienfars/Stargardt_paper_2021)

Analysis code for our study comparing L-cone–, S-cone–, and rod-driven perifoveal temporal contrast sensitivity (tCS) in patients with Stargardt disease 1/Fundus Flavimaculatus (STGD1/FF), measured with the photoreceptor-isolating stimulator from [tCSF]({{ base_path }}/code/tcsf-light4sightng).

Fourteen genetically confirmed patients were tested across nine temporal frequencies (1–20 Hz) in an annular perifoveal field (1°–6° eccentricity). Sensitivity losses relative to age-matched normal values were compared across photoreceptor/pathway classes and correlated with two clinical outcome measures — IR-SLO area of hyporeflectance and standard automated perimetry mean deviation. Photoreceptor-driven tCS was generally reduced in patients, without a systematic difference between photoreceptor classes, but luminance-driven L-cone sensitivity correlated best with the clinical parameters, suggesting it as a candidate functional biomarker for clinical trials.

**Repository contents:**
- R Markdown notebooks reproducing the paper's figures and tables (group comparisons, correlation analyses)
- `fig1.R` — spectral sensitivity / stimulus figure generation
- `pca.R` — PCA on clinical variables
- a de-identified clinical summary table matching the data released with the published paper

The underlying patient-level dataset (raw clinical records, genetic testing, retinal imaging) is not included, as it is protected health information collected under institutional research ethics approval — this repository is analysis code only, released for methodological transparency.

**Related publication:** [Fars J, Pasutto F, Kremers J, Huchzermeyer C. Perifoveal cone- and rod-mediated temporal contrast sensitivities in Stargardt disease/fundus flavimaculatus. *Invest Ophthalmol Vis Sci.* 2021;62(14):24.]({{ base_path }}/publication/2021-11-01-Perifoveal_Stargardt)

[View the repository on GitHub →](https://github.com/julienfars/Stargardt_paper_2021)
