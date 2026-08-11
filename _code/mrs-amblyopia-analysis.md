---
title: "MRS Analysis Pipeline — Amblyopia Plasticity Study"
excerpt: "A Python/Bash pipeline for preprocessing and analysing magnetic resonance spectroscopy (MRS) data, built to study GABAergic disinhibition after visual training in adult amblyopia."
collection: code
language: "Python"
github: "https://github.com/julienfars/mrs_amblyopia_analysis"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-mrs__amblyopia__analysis-181717?logo=github)](https://github.com/julienfars/mrs_amblyopia_analysis)
[![Top language](https://img.shields.io/github/languages/top/julienfars/mrs_amblyopia_analysis)](https://github.com/julienfars/mrs_amblyopia_analysis)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/mrs_amblyopia_analysis)](https://github.com/julienfars/mrs_amblyopia_analysis)

Amblyopia ("lazy eye") is linked to disrupted binocular processing, potentially mediated by GABAergic inhibition. This pipeline processes the magnetic resonance spectroscopy (MRS) data from our study asking whether perceptual training induces cortical disinhibition in the amblyopic visual cortex — the same project behind the [AVA 30th Xmas Meeting talk]({{ base_path }}/talks/2025-12-15-ava-xmas-meeting-gaba-amblyopia) on effects of visual training on perception and GABA.

**What's in the repo:**
- a Bash preprocessing pipeline to organise and standardise MRI/MRS data,
- a Python package (`mrs_pipeline`) for MRS preprocessing, analysis, and data aggregation,
- a Jupyter notebook demonstrating the full analysis workflow end to end.

Built on top of [FSL](https://fsl.fmrib.ox.ac.uk/) and [`fsl_mrs`](https://github.com/wtclarke/fsl_mrs), with dependencies managed through a Conda environment for reproducibility.

The battery of psychophysical tests used alongside the MRS scans, before and after training, is in a companion repository: [`visual_tests_amblyopia`]({{ base_path }}/code/visual-tests-amblyopia).

[View the repository on GitHub →](https://github.com/julienfars/mrs_amblyopia_analysis)
