# resource-constrained-edge-ai-review
Data and screening records supporting a 55-study review of resource-constrained Edge AI, including analysis matrices and registries.
## Overview

This repository contains the data, screening registries, study-level extraction matrix, and quantitative analysis files supporting the review manuscript:

**Resource-Constrained Edge AI: Architectures, Optimization, Deployment, and Experimental Validation**

The repository is intended to support methodological transparency, auditability, and independent inspection of the evidence synthesis. It does not redistribute the full texts of the reviewed publications.

## Review corpus

The closed review corpus contains **55 publications**:

- **29 core publications** selected for detailed synthesis;
- **26 complementary publications** selected for targeted analytical coverage;
- **54 publications** reviewed in full text;
- **1 publication** retained at abstract level only.

The quantitative synthesis uses question-specific analytical populations:

- **D01 — Complete review corpus:** 55 publications;
- **D02 — Full-text-reviewed corpus:** 54 publications;
- **D03 — Original-evaluation set:** 48 publications;
- **D04 — Robust empirical set:** 43 publications;
- **D05 — Concrete AI-workload set:** 40 publications.

These denominators prevent review-only, abstract-only, insufficiently supported, or non-workload publications from inflating empirical prevalence estimates.

## Repository contents

### 01_Edge_AI_Extraction_Matrix_55_Studies.xlsx

Study-level evidence extraction matrix for the complete 55-publication corpus.

It contains:

- the bibliographic master list;
- exhaustive extraction for the 29 core publications;
- directed extraction for the 26 complementary publications;
- the controlled codebook;
- reproducibility coding;
- quality-control records;
- pilot and batch summaries.

The matrix preserves distinctions among measured, profiler-derived, simulated, modelled, estimated, claimed, review-only, and abstract-only evidence. Missing values were not inferred.

### 02_Edge_AI_Review_Quantitative_Analysis.xlsx

Final quantitative analysis workbook derived from the completed extraction matrix.

It contains:

- the denominator registry;
- study-level analytical coding;
- reproducibility coding;
- category flags;
- quantitative tables;
- data used for the manuscript figures;
- the review dashboard;
- manuscript-ready quantitative statements.

This is the principal file for reproducing the counts, percentages, tables, and figure data reported in the manuscript.

### 03_Computing_Review_Supplementary_Registries.docx

Human-readable supplementary screening registries.

It documents:

- **144 pertinent publications outside the configured synthesis quota**;
- **31 bibliographically unresolved records**.

The potential contributions listed for outside-quota publications were derived from screening metadata and must not be interpreted as full-text findings. Bibliographically unresolved records were excluded from the closed analytical corpus.

### 04_Near_Miss_Sources.csv

Machine-readable registry of the **144 pertinent outside-quota publications**.

These records passed thematic screening but were not all incorporated into the detailed synthesis because of the configured quota, bibliographic priority, methodological diversity, or related selection rules.

### 05_Excluded_Sources.csv

Machine-readable registry of the **367 excluded records** and their screening information.

The exclusion categories include:

- missing mandatory evidence groups;
- missing required concept co-occurrence;
- predefined exclusion terms;
- keyword-only correspondence;
- contextual irrelevance.

### 06_Non_Selected_Sources.csv

Complete machine-readable registry of all **511 non-selected records**.

This file consolidates:

- the 144 pertinent outside-quota records; and
- the 367 excluded records.

It is retained as a master audit file. The two preceding CSV files provide the same records separated by screening outcome for easier inspection.

## Recommended reading order

For a concise understanding of the repository:

1. Read this `README.md`.
2. Open `03_Computing_Review_Supplementary_Registries.docx` for the screening overview.
3. Consult `01_Edge_AI_Extraction_Matrix_55_Studies.xlsx` for study-level evidence.
4. Consult `02_Edge_AI_Review_Quantitative_Analysis.xlsx` for denominators, calculations, tables, and figure data.
5. Use the CSV registries only when machine-readable screening records or record-level auditability are required.

## Relationship among the files

The extraction matrix is the evidence base.

The quantitative analysis workbook applies the final analytical denominators and category coding to that evidence base.

The supplementary document provides a readable account of outside-quota and unresolved records.

The CSV files preserve raw, machine-readable screening outputs. `06_Non_Selected_Sources.csv` is the complete master registry, while `04_Near_Miss_Sources.csv` and `05_Excluded_Sources.csv` are outcome-specific subsets.

## Reuse and interpretation

Users may inspect, reproduce, and extend the analysis, provided that:

- the repository and associated article are cited;
- the analytical denominator used for each result is preserved;
- multi-label categories are not interpreted as mutually exclusive;
- abstract-only, unresolved, and low-confidence evidence is not treated as equivalent to robust full-text empirical evidence;
- screening-metadata summaries are not represented as full-text findings;
- no universal model, hardware, or performance ranking is inferred across incompatible tasks, devices, datasets, or measurement boundaries.

## Data availability

The study-level extraction matrix, quantitative analysis workbook, screening registries, analytical-denominator definitions, and supporting materials generated for the review are available in this repository.

Repository DOI: **[insert Zenodo DOI after publication]**

## Citation

Please cite both the review article and the archived repository version.

### Repository citation template

> [Authors]. (2026). *Resource-Constrained Edge AI Review: Extraction Matrix, Quantitative Analysis, and Screening Registries* (Version 1.0). Zenodo. https://doi.org/[DOI]

The final article citation will be added after publication.

## License

The repository data and documentation are licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. See `LICENSE.md`.

The bibliographic metadata and summaries remain subject to the rights and terms of their original sources. No full-text publications are redistributed in this repository.

## Version

**Version 1.0 — August 2026**

This version corresponds to the frozen 55-publication corpus used for journal submission.
