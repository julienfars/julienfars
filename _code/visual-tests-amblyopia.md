---
title: "Amblyopia Test Battery — Psychtoolbox Visual Assessments"
excerpt: "A MATLAB/Psychtoolbox battery of visual tests (acuity, contrast sensitivity, binocular imbalance, dichoptic and stereo tasks) used to assess amblyopic vision before and after training. <br/><img src='/images/code/visual-tests-amblyopia-icon.png'>"
collection: code
language: "MATLAB"
github: "https://github.com/julienfars/visual_tests_amblyopia"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-visual__tests__amblyopia-181717?logo=github)](https://github.com/julienfars/visual_tests_amblyopia)
[![Top language](https://img.shields.io/github/languages/top/julienfars/visual_tests_amblyopia)](https://github.com/julienfars/visual_tests_amblyopia)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/visual_tests_amblyopia)](https://github.com/julienfars/visual_tests_amblyopia)

<img src="{{ base_path }}/images/code/visual-tests-amblyopia-icon.png" alt="Amblyopia test battery" width="220">

A Psychtoolbox/MATLAB battery of psychophysical tests measuring visual acuity, contrast sensitivity, interocular imbalance, dichoptic combination, and 3D binocular perception in adults with amblyopia, run on participants before and after VR-based dichoptic training (see [`lazy_eye_VR_training`]({{ base_path }}/code/lazy-eye-vr-training)).

Amblyopia ("lazy eye") involves disrupted binocular processing thought to be linked to GABAergic inhibitory mechanisms in primary visual cortex. This battery, combined with fMRI/MRS scanning (see [`mrs_amblyopia_analysis`]({{ base_path }}/code/mrs-amblyopia-analysis)), was used to characterise the neural correlates of perceptual-training-induced changes in amblyopic vision.

**Test sequence:** Cutoff (acuity) → Contrast Sensitivity → Interocular Imbalance → Dichoptic → Asteroid (stereo) → Tumbling E / Tumbling E Crowded, tested monocularly and binocularly with a Display++ and passive 3D glasses.

The battery builds on and adapts scripts from several other researchers, including Alex S. Baldwin's staircase protocol, Jun-Yun Zhang's dichoptic test, Alice Grasso McCaslin's Asteroid test, and Peter Scarfe's Psychtoolbox tutorials — credited in full in the repository.

[View the repository on GitHub →](https://github.com/julienfars/visual_tests_amblyopia)
