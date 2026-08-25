---
title: "Starting a local biometrics tracker"
categories: Biometrics
tags:
  - python
  - streamlit
  - sqlite
excerpt: "Building a local-only Python app to track body composition and measurements over time — no cloud, no account, no network calls."
---

{% include base_path %}

First entry under a new topic: a local app for tracking body composition and body measurements over time. Code is on GitHub at [julienfars/biometrics-tracker](https://github.com/julienfars/biometrics-tracker).

## Why

I wanted a project to explore data modelling, trend analysis, and sourcing proper clinical reference ranges for personal health metrics — built as a tidy, transparent (not black-box) app, rather than a polished product.

## Privacy, by design

- All data stays in a local SQLite file on my own machine.
- No network requests, no accounts, no telemetry.
- The app never phones home — that's a deliberate design choice, not just a default.

## Tech stack

- Python 3.12
- [Streamlit](https://streamlit.io/) for the UI
- SQLite via SQLAlchemy for storage
- Altair for charts

## Where it's at

Early days — the core data layer (`db.py`, a tidy `date` / `metric` / `value` / `unit` schema) and a first pass at reference ranges are in, but most of the app (multi-profile support, the entry form, trend/reference-range assessment, the actual dashboard) is still ahead. See the [repo's progression tree](https://github.com/julienfars/biometrics-tracker#progression-tree) for the current state — it's a living roadmap, not a fixed spec.

<img src="{{ base_path }}/images/code/biometrics_1.png" alt="db.py — the SQLAlchemy data layer and schema for the local biometrics tracker, with a quick test run in the terminal">

<img src="{{ base_path }}/images/code/biometrics_2.png" alt="Setting up the Python virtual environment for the biometrics tracker in the terminal">

Body-composition figures will come from a consumer bioimpedance scale, which is known to have systematic error (hydration, food intake, time of day) compared to clinical methods like DEXA — this is not a medical device and makes no diagnostic claims. Where the app compares a value against a reference range, the source of that range will be cited in the app itself.

I'll post updates here as the project moves along.
