---
layout: archive
title: "CV"
permalink: /cv/
description: "Julien Fars' CV: education, work experience, skills, publications, talks, and teaching."
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Biomedical researcher with a PhD in Human Biology and several years of postdoctoral research at the University of Oxford, currently moving from academic neuroscience into data science and research & development. Experience spans Python/ML pipelines on large-scale imaging (MRI/fMRI) and behavioural data, end-to-end clinical study delivery, and VR-based rehabilitation research, combined with rigorous statistical modelling (frequentist and Bayesian) and reproducible data engineering (Python, R, AWS). Rigorous, autonomous, and used to interdisciplinary work at the interface of data science, neuroscience, and health.

Education
======
* Ph.D in Research in Human Biology, Ophthalmology and Neurosciences, Friedrich-Alexander-Universität
Erlangen-Nürnberg, Germany, 2022
  * Thesis: Function and dysfunction of
rod-and cone-driven pathways: novel
approaches for measuring treatment
effects
* M.S. in Cognitive Sciences, Université Lumière Lyon 2, France, 2018
* M.S. in Neurosciences, Université Lyon 1, France, 2017
* B.S. in Biology, Biochemistry, Physiology, Université Lyon 1, France, 2016

Work experience
======
* 2022 - 2026: Postdoctoral Research Fellow in Clinical Neurosciences
  * University of Oxford Centre of Integrative Neuroimaging, Oxford, UK
  * Duties included: 
    * Led an adult amblyopia VR rehabilitation study end-to-end: ethics preparation, participant recruitment and screening (~50 recruited, ~150 assessed), safety monitoring, and study delivery.
    * Co-developed a Unity (C#) virtual reality application for the study, and built an AWS DynamoDB-backed pipeline to monitor remote VR training data.
    * Applied Python-based machine learning (scikit-learn, TensorFlow) and neuroimaging pipelines (FSL, FreeSurfer, fMRIPrep) to analyse multimodal MRI/fMRI/MRS data.
    * Built interactive reporting tools (R Shiny, R Markdown) for research collaborators, and produced study SOPs and technical documentation.
    * Formally co-supervised one Master's and one PhD student; served as EDI Ambassador and Open Science Ambassador for the department.
  * Supervisors: Prof. Holly Bridge and Prof. Betina Ip

* 2023 - 2025: Demonstrator & Open Science Ambassador
  * University of Oxford, Oxford, UK
  * Duties included: 
    * Delivered practical training sessions in vision science (visual acuity, contrast sensitivity, stereopsis, colour vision), experimental design, and data analysis methods for medical and biomedical students.
    * Demonstrated MRI/fMRI methods, GDPR principles, Git, and Open Science practices to researchers and course participants.
    * Delivered around 12 workshops (2023-2025) on Git/GitHub, reproducible workflows, and responsible data sharing as Open Science Ambassador, plus one-to-one researcher support.
    * Mentored 3 PhD and 2 Master's students through research guidance and technical support.

* 2019 - 2022: PhD in Ophthalmology/Neurosciences
  * Friedrich-Alexander-Universität
Erlangen-Nürnberg, Erlangen, DE
  * Duties included: 
    * Conducted clinical vision research in inherited retinal disease (retinitis pigmentosa, Stargardt disease), recruiting and testing around 100 participants using visual psychophysics and silent-substitution photoreceptor-specific stimulation.
    * Built a local multimodal database integrating clinical and research data, and applied frequentist and Bayesian statistical models to estimate perceptual thresholds.
    * Redesigned the study population and protocol when COVID-19 disrupted recruitment, leading to a first-author publication in Scientific Reports.
  * Supervisor: Prof. Jan Kremers and Prof. Cord Huchzermeyer
  
Skills
======
* Statistical Modelling & Analysis
  * Statistical analysis and modelling
  * Bayesian statistics
  * Machine learning
  * Predictive modelling
  * Model fitting and optimisation
  * Multivariate analysis
  * Hypothesis testing
  * Quality control
* Programming & Data
  * Python
  * R
  * MATLAB
  * C/C#/C++
  * SQL/NoSQL
  * Git
  * Data pipelines
  * Large-scale data processing
* Machine Learning
  * scikit-learn
  * TensorFlow
  * Model training and evaluation
  * Feature extraction
  * Computational modelling
* Biomedical Data & Clinical Research
  * Neuroimaging (MRI, fMRI, MRS)
  * Clinical and physiological data
  * Multimodal data analysis
  * REDCap (data quality control, data queries)
  * Good Clinical Practice (GCP) certified
  * FSL, fMRIPrep, FreeSurfer
* Computational Environment & Cloud
  * Linux
  * SLURM
  * AWS
  * Docker
  * Reproducible workflows
  * Version control
* Reporting & Visualisation
  * R Shiny
  * R Markdown
  * Power BI
  * Tableau
* Communication & Collaboration
  * Scientific communication
  * Multidisciplinary collaboration
  * Technical teaching
  * Supervision and mentoring
  * Research project management
* Languages
  * French: native
  * English: bilingual
  * German: basic

Awards
======
* OxCIN Good Citizen Award (2025)
* CSHL Regeneron Scholars Programme grant (2023)
* ARVO International Travel Grant (2022)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
