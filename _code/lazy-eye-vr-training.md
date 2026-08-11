---
title: "Amblyopia VR — Dichoptic Training in Virtual Reality"
excerpt: "A Unity/C# app for the Meta Quest 2 that delivers adaptive dichoptic training for amblyopia (lazy eye), used in a clinical study. <br/><img src='https://julienfars.github.io/julienfars/images/code/lazy-eye-vr-training.png'>"
collection: code
language: "C#"
github: "https://github.com/julienfars/lazy_eye_VR_training"
---

{% include base_path %}

[![Repo](https://img.shields.io/badge/GitHub-lazy__eye__VR__training-181717?logo=github)](https://github.com/julienfars/lazy_eye_VR_training)
[![Top language](https://img.shields.io/github/languages/top/julienfars/lazy_eye_VR_training)](https://github.com/julienfars/lazy_eye_VR_training)
[![Last commit](https://img.shields.io/github/last-commit/julienfars/lazy_eye_VR_training)](https://github.com/julienfars/lazy_eye_VR_training)

A Unity/C# application built for the Meta Quest 2 that delivers a dichoptic de-masking training task for adults with amblyopia (lazy eye), adapted from [Liu & Zhang (2019)](https://doi.org/10.1167/iovs.18-26483).

<img src="{{ base_path }}/images/code/lazy-eye-vr-training.png" alt="Amblyopia VR training app">

In the amblyopic eye, the participant is shown two Gabor gratings; in the fellow eye, a masking noise patch. A 3-up-1-down staircase adjusts the noise contrast, and — the key addition over the original paradigm — the *target* contrast itself adapts to participant performance, making the task self-calibrating and considerably more challenging over repeated sessions than a fixed-target design.

Participants trained once a day for around an hour, aiming for at least 15 sessions across 3 weeks. This is the same training programme behind our [MRS analysis pipeline]({{ base_path }}/code/mrs-amblyopia-analysis) and the [AVA 30th Xmas Meeting talk]({{ base_path }}/talks/2025-12-15-ava-xmas-meeting-gaba-amblyopia) on visual training and GABA.

The version of the app used in the original study synced to a private AWS backend for remote monitoring; this public release removes that entirely and stores all patient configuration and trial results locally on the headset — no internet connection, server, or credentials required to build or run it.

[View the repository on GitHub →](https://github.com/julienfars/lazy_eye_VR_training)
