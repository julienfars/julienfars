---
title: "tCSF (Light4SightNG) — Silent-Substitution Stimulator for Temporal Contrast Sensitivity"
excerpt: "A Windows/C# application that drives a soundcard-based LED stimulator to isolate individual photoreceptor classes (L-, M-, S-cones and rods) and measure temporal contrast sensitivity psychophysically."
collection: code
language: "C#"
github: "https://github.com/julienfars/tCSF"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-tCSF-181717?logo=github)](https://github.com/julienfars/tCSF)
[![Top language](https://img.shields.io/github/languages/top/julienfars/tCSF)](https://github.com/julienfars/tCSF)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/tCSF)](https://github.com/julienfars/tCSF)

Standard computer monitors are too slow and spectrally limited to isolate the response of individual photoreceptor types. `tCSF` (internally named `Light4SightNG`) is a Windows desktop app, written in C#/WinForms, that instead drives a bank of wavelength-specific LEDs through a PC's soundcard — used as a fast, precise digital-to-analog converter — following the "audiophile hardware in vision science" approach (Puts et al., 2005).

By modulating several LEDs together with carefully chosen relative contrasts and phases — the **silent substitution** technique (Estévez & Spekreijse, 1982) — the stimulator can target a single photoreceptor class (only L-cones, only M-cones, S-cones, or rods) or a known mix of several, isolating which retino-geniculate pathway (parvocellular vs. magnocellular) mediates perception at a given temporal frequency.

The software:
- generates the multi-channel LED drive waveforms via SlimDX/XAudio2,
- runs adaptive PEST staircases to find contrast-detection thresholds,
- lets the experimenter configure and calibrate stimulus channels,
- and exports per-subject/session threshold measurements for later analysis.

This general paradigm — perifoveal flicker thresholds to photoreceptor-isolating stimuli — underpins several studies from the Department of Ophthalmology, University Hospital Erlangen, including our work on [temporal contrast sensitivity in Stargardt disease]({{ base_path }}/code/stargardt-tcs-analysis) and the related [publication]({{ base_path }}/publication/2021-11-01-Perifoveal_Stargardt).

This is legacy research software, published for reference and reproducibility alongside the associated publications rather than as an actively maintained product.

[View the repository on GitHub →](https://github.com/julienfars/tCSF)
