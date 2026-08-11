---
title: "Chromatic Discrimination & Response Window (CCT Analysis)"
excerpt: "R code and anonymised data behind our Scientific Reports paper on how response window duration affects chromatic discrimination measures in mature observers."
collection: code
language: "R"
github: "https://github.com/julienfars/CCT_Chromatic_measurements"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-CCT__Chromatic__measurements-181717?logo=github)](https://github.com/julienfars/CCT_Chromatic_measurements)
[![License](https://img.shields.io/github/license/julienfars/CCT_Chromatic_measurements)](https://github.com/julienfars/CCT_Chromatic_measurements/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/CCT_Chromatic_measurements)](https://github.com/julienfars/CCT_Chromatic_measurements)

Code and anonymised data accompanying [Fars, Fernandes, Huchzermeyer, Kremers & Paramei (2022), *Scientific Reports*]({{ base_path }}/publication/2022-04-31-Chromatic_measures) — the same study behind the [ECVP 2021]({{ base_path }}/talks/2021-08-25-ecvp-2021-chromatic-discrimination) poster and [AVA Christmas Meeting 2022]({{ base_path }}/talks/2022-ava-christmas-meeting-chromatic-discrimination) talk.

We used the Cambridge Colour Test (CCT) Trivector procedure to measure chromatic discrimination thresholds (Protan, Deutan, Tritan vector lengths) in 30 normal trichromats across three age groups (young, middle-aged, mature), under three response windows (3s, 5s, 8s), tested twice (test/retest). Young and middle-aged observers performed comparably across all response windows, but mature observers needed a longer response window to reach their best (lowest) discrimination thresholds — consistent with an age-related increase in the time needed for accurate chromatic processing.

**Repository contents:**
- `CCT.R` — full analysis: figures, frequentist and Bayesian statistics (including multilevel `brms` models of threshold ~ age group × response window)
- `Data/CCT_data.xlsx` — anonymised per-trial CCT vector lengths, with age, gender, response window, and test/retest session (participants identified only by a pseudonymous numeric ID)

Dataset also archived on [figshare](https://doi.org/10.6084/m9.figshare.16615999).

[View the repository on GitHub →](https://github.com/julienfars/CCT_Chromatic_measurements)
