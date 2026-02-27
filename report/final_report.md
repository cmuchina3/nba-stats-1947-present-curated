# Final Report  
**Curated NBA / ABA / BAA Statistics Dataset (1947–Present)**  
Clarence Muchina   
Data Curation I – 02/27/26 

---

# 1. Data and Metadata Profile (Final Version)

The dataset selected for this project is a publicly available NBA statistics dataset spanning 1947 to the present, originally obtained from Kaggle under the title “NBA-ABA-BAA Stats (1947–Present).” The dataset contains player-level and team-level statistical data covering the BAA (1947–1949), NBA (1949–present), and ABA (1967–1976). It includes multiple CSV files representing player per-game statistics, advanced metrics, totals, award shares, draft history, team summaries, and opponent statistics.

The data originate from Basketball Reference and were compiled into structured CSV format by a Kaggle contributor. The dataset consists of multiple tabular files in comma-separated value (CSV) format. Each file represents a specific statistical perspective (e.g., per game, per 100 possessions, per 36 minutes, team totals). No proprietary formats are used.

Key stakeholders include:

- The original data compiler (Kaggle contributor)  
- Basketball Reference as an upstream source  
- End users such as sports analysts, researchers, students, and historians  
- Repository managers (e.g., Zenodo or GitHub in this curated version)  
- The designated community of sports analytics learners  

The dataset includes minimal embedded metadata beyond column headers. There is no structured metadata file accompanying the Kaggle dataset. There is limited documentation explaining variable definitions, changes in statistical recording practices across eras, or file relationships.

To enrich the dataset, this curated version includes:

- A structured README  
- A consistent file naming convention  
- A DataCite XML metadata file  
- Documentation of provenance and preservation considerations  

This transformation reflects Borgman’s definition of data as entities used as evidence. In this case, the dataset serves as evidence for arguments about historical performance trends, player efficiency, statistical evolution, and sports analytics modeling. The curated version improves the ability of future users to interpret and responsibly reuse the data.

---

# 2. Repository Profile

For my term project I previously selected a public NBA stats dataset (1947-Present) from Kaggle. For this week's assignment I've chosen the Zenodo repository from the Registry of Research data Repositories. I tried to go with sports themed repositories but found none that really gravitated to me. Zenodo was my top choice because it functions as a widely used, general purpose research repository for datasets and related research outputs. It supports persistent identifiers and is designed for broad public dissemination and long term access. Since my NBA dataset isn't inherently tied to a single academic discipline repository like a domain repository for climate data, Zenodo's generalized scope is an advantage for me. It can host sport analytic datasets and associated documentation without forcing a disciplinary fit.

From a policies and procedures standpoint, Zenodo is open to submissions, but may require a registration for data uploads. Zenodo also claims to accept most if not all file formats which is essential for an NBA dataset because sports datasets include CSV files, PDF/Markfown, data dictionaries, and many more.  For practical deposit limits, Zenodo's help documentation cites a 50GB limit per record by default, with the possibility of requesting an increased quota when needed. This is important because many sports datasets are relatively small, but a fully curated package can expand if you add multiple historical tables, derived analysis files, or extensive documentation. But one thing to keep in mind with that is that it does have size limits and content/policy constraints.

Zenodo's limit and escalation pathway provides us clarification on feasibility for a complete SIP. Zenodo's guidance to depositors shows up primarily through its deposit interface and documentation on describing records. In practice, the SIP for this dataset would include the data files themselves (so the original CSVS and any cleaned CSV outputs produced), documentation that explains how the dataset was created and curated (README, processing steps), and strucutred descriptive metadata in Zenodo's record field so the dataset can be discovered and cited. Zenodo's documentation makes it clear that some fields are required, inlcuding a Title and Creators, which reinforces that descriptive metadata isn't optional, it's a part of the deposit package. Zenodo also provides explicit guidance around access rights and licensing choices as part of deposition decisions, which are key SIP elements because they determine what downstream users can legally do with the data and under what conditions. If I were depositing a curated NBA dataset (which I sort of am), I'd use Zenodo's deposit guidance to select a clear license and to document any constraints inherited from the source (AKA Kaggle), ensuring that the curated version doesn't imply the rights the original compilation didn't grant. Zenodo does provide human assistance in the form of support and help resources, but compared to many institutional or disciplinary repositories, it's primarily a self service platform, so the burden of doing careful curation falls on us (the depositors).

Zenodo's metadata practices are one of the biggest reasons it fits a dataset intended for broad reuse. Zenodo is strongly associated with DataCite style citation infrastructure, it collects deposit metadata through required fields and maps them to DataCite metadata for DOI registration. It also has similarities to repository registries like re3data, which indicate the metadata standards and interoperability approaches that Zenodo supports. In other words, depositing my curated NBA dataset on Zenodo would encourage discoverability and reuse because the record will present standardized descriptive information to users and indexing services, and it'll provide a persistent identifier and citation components. This strengthens the information package concept discussed in lecture, we're not only providing bits (data files), but we're also representing information and metadata that helps a designated community (my fellow sports analytic learners like our professor) understand what the data means and how to use it responsibly.

In terms of data access mechanisms, Zenodo's default model for openly shared record is pretty straightforward, users can typically download files directly from the record page without needing to create an account, which supports low friction dissemination and aligns with our goal for this project of making our curated dataset publicly accessible. But, logins do become relevant when records aren't fully open or when one is looking to deposit data. For instance, if I choose to restricted access, Zenodo's access rights model would affect who can retrieve my files and under what conditions. Zenodo also supports more than just click to download access because it offers structured metadata exposure and integration patterns. All in all, this is what makes Zenodo's DIP strong, it's not just the downloadable data files, but also the landing page, citation info, human readable descriptions, and the machine readable metadata that's displayed and shared.  The culmination of the things I've discussed above is what makes Zenodo such a good fit for my dataset.

Link To Repo: https://www.re3data.org/repository/r3d100010468

References:

https://help.zenodo.org/docs/

---

# 3. Recommended Data Citation

Muchina, C. (2026). *Curated NBA/ABA/BAA Player and Team Statistics Dataset (1947–Present)* (Version 1.0) [https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats/code]. GitHub repository. Derived from Kaggle dataset “NBA-ABA-BAA Stats (1947–Present).”

This citation includes:

- Creator  
- Year  
- Title  
- Version  
- Resource type  
- Location of repository  
- Provenance acknowledgment  

This aligns with DataCite citation principles discussed in lecture.

---

# 4. Long-Term Preservation Considerations

## File Formats

All primary data files are stored in CSV format. CSV is:

- Non-proprietary  
- Plain text  
- Widely supported  
- Human-readable  
- Machine-processable  

This significantly reduces the risk of format obsolescence. Unlike Excel (.xlsx), CSV does not require proprietary software and is unlikely to become unreadable in the foreseeable future.

The repository also includes:

- Markdown (.md) documentation  
- XML metadata structured under the DataCite schema  

Both formats are open, standardized, and preservation-friendly.

## Software Requirements

No specialized or proprietary software is required to access the data. Files can be opened using:

- Excel  
- Google Sheets  
- R  
- Python (pandas)  
- Any text editor  

This reduces technological dependency risk.

## Versioning

The repository is labeled Version 1.0. Future updates should follow semantic versioning to prevent citation ambiguity. Version control through GitHub preserves file history and provenance.

## Interpretive Preservation Risk

A more significant long-term preservation concern is semantic drift. Statistical definitions in basketball have evolved over time (e.g., introduction of the three-point line, advanced metrics such as PER). Documentation is therefore essential to preserve interpretive context.

---

# 5. Copyright and Licensing Statement

The original dataset was obtained from Kaggle, where it is described as publicly available. However, because the dataset is derived from Basketball Reference and compiled by a third party, reuse rights may depend on upstream licensing terms.

For this curated repository:

- No new proprietary claims are made  
- The curated materials (documentation and metadata) are original  
- The repository includes a statement directing users to review the original Kaggle licensing terms  

The safest licensing posture for this project is to defer to the original source license and clearly document provenance, rather than asserting independent ownership of the underlying statistics.

---

# 6. Human Subjects and Ethical Considerations

This dataset contains publicly available professional sports performance statistics. It does not include:

- Private personal data  
- Contact information  
- Sensitive demographic information  
- Health records  

All data describe public athletic performance within a professional league context.

Because the dataset does not contain personally identifiable private information or confidential records, no anonymization procedures were necessary.

However, ethical considerations still apply:

- Proper attribution must be maintained  
- Data should not be misrepresented  
- Historical statistics should be interpreted in context  

This aligns with broader data ethics principles discussed in course readings.
