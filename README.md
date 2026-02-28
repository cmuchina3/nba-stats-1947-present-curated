# Curated NBA / ABA / BAA Statistics Dataset (1947–Present)

## Project Overview

This repository contains a curated version of a public NBA statistics dataset originally obtained from Kaggle. The dataset includes player-level statistics spanning the BAA (1947–1949), NBA (1949–present), and ABA (1967–1976).

The purpose of this project is to enhance the original dataset with improved documentation, structured metadata, and preservation-oriented organization so that it could realistically be submitted to a research data repository such as Zenodo.

This repository was developed as part of a Data Curation course project and demonstrates best practices in dataset organization, documentation, metadata creation, and long-term accessibility.

---

## Original Data Source

- **Source Platform:** Kaggle  
- **Dataset Title:** NBA / ABA / BAA Stats (1947–Present)  
- **Original Compiler:** Sumitro Datta  
- **Underlying Source:** Compiled from Basketball Reference  

The dataset contains regular season player statistics, including both traditional and advanced metrics. It includes player-season level data, career summaries, and team-level information.

According to the Kaggle listing, the dataset is described as public domain. Users should verify upstream licensing considerations when redistributing or reusing the data.

---

## Repository Structure

nba-stats-1947-present-curated/
│
├── README.md
│
├── data/
│   ├── raw/
│   │   └── (original Kaggle CSV files)
│   └── processed/
│       └── (curated or renamed files, if applicable)
│
├── docs/
│   ├── data-dictionary.md
│   └── processing-notes.md
│
├── metadata/
│   └── datacite-metadata.xml
│
└── report/
└── final-report.pdf

## File and Folder Descriptions

### README.md
Provides an overview of the dataset, repository structure, provenance, licensing notes, and reuse guidance.

### /data/raw/
Contains the original data files downloaded from Kaggle in their original CSV format. These files are preserved to maintain provenance and authenticity.

Typical files include:
- Player season statistics  
- Career summaries  
- Team-level statistics  
- Player identifiers and team abbreviations  

No structural modifications were made to these raw files.

### /docs/data-dictionary.md
Provides column-level definitions for key variables in the dataset, including:
- Variable meanings  
- Units of measurement  
- Definitions of advanced statistics  
- Notes on missing or ambiguous values  

This improves interpretability beyond CSV headers alone.

### /docs/processing-notes.md
Documents any steps taken during curation, including:
- Cleaning decisions  
- Standardization choices  
- Assumptions about missing data  
- Clarifications regarding statistical changes across eras  

This file supports transparency and reproducibility.

### /metadata/datacite-metadata.xml
Structured metadata file created using the DataCite Metadata Schema, used CoPilot to help complete this.

Includes:
- Creator(s)  
- Title  
- Publication year  
- Resource type (Dataset)  
- Abstract/description  
- Subject keywords  
- Rights/license information  

If AI tools (e.g., Microsoft CoPilot) were used to assist in generating this XML file, the output was manually reviewed and validated against the DataCite schema.

### /report/final-report.pdf
Final project report containing:
- Updated Data & Metadata Profile  
- Updated Repository Profile (Zenodo)  
- Recommended data citation  
- Long-term preservation considerations  
- Copyright/license statement  
- Human subjects and ethical considerations  

---

## Recommended Citation

Curator Last Name, First Name. (2026). *Curated NBA / ABA / BAA Statistics Dataset (1947–Present)* [Dataset]. GitHub repository. Original data compiled by Sumitro Datta via Kaggle.

---

## File Formats and Preservation Considerations

The primary file format used in this dataset is CSV (`.csv`), which is:

- Non-proprietary  
- Widely supported  
- Suitable for long-term preservation  
- Compatible with Excel, R, Python, and most statistical software  

No proprietary software is required to open the data files.

Long-term risks are minimal due to open file formats. Interpretive risks (e.g., evolving statistical definitions across eras) are addressed through documentation and the data dictionary.

---

## Human Subjects and Ethical Considerations

This dataset contains publicly available professional sports performance statistics. It does not include:

- Personally identifiable private information  
- Sensitive demographic data  
- Confidential research subjects  

No anonymization procedures were required.

---

## Rights and Licensing

The Kaggle listing describes the dataset as public domain. This curated repository enhances documentation and metadata but does not claim ownership of the original compiled statistics.

Users are encouraged to confirm upstream licensing conditions before redistribution or derivative publication.

---

## Purpose of This Repository

This curated dataset demonstrates:

- Structured metadata implementation (DataCite XML)  
- Improved documentation and transparency  
- Clear file organization  
- Preservation-aware formatting  
- Alignment with repository submission standards  

It is designed to function as a realistic submission package for a general-purpose research repository such as Zenodo.
