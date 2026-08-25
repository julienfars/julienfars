---
title: "Biometrics Tracker — Local-Only Health Metrics App"
excerpt: "A local Python/Streamlit app for tracking body composition and measurements over time, storing everything in a local SQLite file — no cloud, no account, no network calls."
collection: code
language: "Python"
github: "https://github.com/julienfars/biometrics-tracker"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-biometrics--tracker-181717?logo=github)](https://github.com/julienfars/biometrics-tracker)
[![Top language](https://img.shields.io/github/languages/top/julienfars/biometrics-tracker)](https://github.com/julienfars/biometrics-tracker)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/biometrics-tracker)](https://github.com/julienfars/biometrics-tracker)

A work-in-progress local app for tracking body composition and body measurements over time — built to explore data modelling, trend analysis, and sourced clinical reference ranges for personal health metrics, as a tidy, transparent app rather than a polished product.

**Privacy by design:** all data stays in a local SQLite file on the machine it runs on. No network requests, no accounts, no telemetry — the app never phones home.

**Stack:** Python 3.12, [Streamlit](https://streamlit.io/) for the UI, SQLite via SQLAlchemy for storage, Altair for charts.

Currently in early stages — the core data layer and a first pass at reference ranges are in, with the entry form, multi-profile support, and trend/reference-range dashboard still ahead. Follow progress on the [Explorations page]({{ base_path }}/biometrics/biometrics-tracker/).

[View the repository on GitHub →](https://github.com/julienfars/biometrics-tracker)
