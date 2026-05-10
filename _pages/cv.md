---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Quantitative Biomedical Science, Dartmouth College, Aug 2025 – present
* M.S. in Biostatistics (Modeling and Methods pathway), University of Washington, Sep 2023 – Mar 2025 (GPA: 3.9/4.0)
* B.S. in Data Science (Concentration: Genomics; Minor: Mathematics), New York University Shanghai, Sep 2019 – May 2023 (GPA: 3.6/4.0)
  * Dean's List: 2021–2022, 2022–2023
  * Study away at New York University, New York, Jan–Dec 2022 (GPA: 3.96/4.0)

Research Experience
======
* Nov 2023 – Apr 2026: Main Contributor — *Contrastive Learning for Lineage Barcoded scRNA-seq Data*
  * University of Washington / University of Michigan
  * Designed and implemented a contrastive deep learning algorithm to learn low-dimensional embeddings for single-cell data, facilitating the identification of cell fate-determining signatures.
  * Supervisors: Kevin Z. Lin (UW), Yixin Wang (U of Michigan)

* Jan 2024 – Apr 2026: Researcher — *Small Area Estimation using MICS Data*
  * University of Washington
  * Implemented small area estimation techniques to derive subnational estimates from MICS survey data; conducted spatial analysis on child health indicators (NMR, vaccination, stunting) across Sierra Leone, Gambia, and Laos.
  * Supervisor: Jon Wakefield (UW)

* Jun – Dec 2022: Research Assistant — *Python-based RNA-seq Analysis using Negative Binomial GLM*
  * New York University
  * Implemented negative binomial GLMs for DGE analysis; reduced runtime from ~3 hours to ~3 minutes via multiprocessing.
  * Supervisor: Manpreet Katari (NYU)

* Jun 2021 – Jan 2022: Research Assistant — *Investigation of Horizontal Gene Transfer in Metagenomics*
  * NYU Shanghai
  * Implemented RNA-seq pipelines on NGS data of human gut microbiome; applied Louvain method for pseudo ortholog community detection.
  * Supervisor: Gang Fang (NYU Shanghai)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks & Poster Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and Leadership
======
* ASA DataFest 2024 Mentor, Department of Statistics, University of Washington (Mar 2024)

Skills
======
* **Programming:** Python (PyTorch), R, Linux/Shell, SQL, MongoDB, HTML, MATLAB, JavaScript
* **Analytics:** Statistical modeling, Numerical analysis, Machine Learning, Deep Learning
* **Bioinformatics:** SPAdes, Bowtie2, Hisat2, Samtools, Diamond, BLAST, Limma, DESeq2
* **Languages:** Chinese (native), English (fluent)
