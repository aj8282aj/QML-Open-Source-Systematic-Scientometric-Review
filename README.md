# Supporting Data — Open-Source Quantum Machine Learning Algorithms: A Systematic and Scientometric Review

This repository contains the supporting data and analysis files for the manuscript. The final review corpus comprises 68 QML studies indexed through Papers with Code.

## Contents

The repository is organized to provide the seven requested reproducibility components: final 68-paper corpus; extracted metadata/classifications; Table A3 reproducibility assessments; Figure 6–7 country/institution data; Figure 8–10 data; VOSviewer/network input files; and documentation of files and methodology.


### data/
1. `01_final_68_paper_dataset.csv` — final 68-paper corpus with manuscript classifications and repository links.
2. `02_extracted_metadata_and_classifications.csv` — paper metadata, classifications, repository information, and reproducibility fields.
3. `03_reproducibility_assessment_Table_A3.csv` — row-level data corresponding to Table A3.
4. `04_country_counts_Figure_6.csv` — corrected paper-level country frequencies used for Figure 6.
5. `05_institution_counts_Figure_7.csv` — corrected paper-level institution frequencies used for Figure 7.
6. `06_author_counts_Figure_8.csv` — author publication frequencies for the 68-study corpus.
7. `07_subject_category_data_Figure_10.csv` — paper-to-arXiv-subject-class associations.
8. `08_subject_category_counts_Figure_10.csv` — arXiv subject-class frequency summary.
9. `09_repository_file_manifest.csv` — repository file inventory.
10–15. Summary tables, PRISMA selection counts, Figure 6–7 consistency checks, and arXiv class-code mapping.

### vosviewer/
Network nodes and edges, simple network/map text files, and Pajek `.net` files that can be imported into network software. These are derived inputs reconstructed from the available matched metadata and should not be described as the original VOSviewer project files unless the original project files are added separately.

### source_metadata/
`Myeeeeeeeibrary.ris` contains bibliographic metadata and arXiv keyword/classification fields. `raw_affiliations_68_papers.txt` contains the raw affiliation text used as supporting material for affiliation-based analyses.

### supplementary/
Methodological and provenance notes.

## Key methodological definitions

Country and institution frequencies use the reviewed paper as the unit of analysis. Each country is counted once per paper if represented by at least one author affiliation; each institution is counted once per paper if present as an author affiliation.

The co-authorship analysis uses authors as the unit of analysis and counts joint-authorship relations within the 68 reviewed publications.

The Figure 10 subject-category analysis uses **arXiv subject classes** associated with the reviewed publications. It does not use Scopus ASJC classifications. Two subject classes co-occur when they are associated with the same reviewed publication.

## Provenance and reproducibility note

The 68-paper dataset, algorithm/framework/application classifications, repository links, and Table A3 values are transcribed from the revised manuscript. Author and arXiv classification fields were supplemented from title-matched RIS metadata. The country and institution frequency files are the corrected files used for Figures 6 and 7.

The original VOSviewer project files containing exact coordinates, cluster assignments, and saved visualization settings should be added by the authors if available. The network text files in this repository provide the derived node/edge data but do not claim to reproduce the original layout.

## Copyright note

The repository should contain derived data and analysis files rather than copies of copyrighted research-paper PDFs unless redistribution is permitted.
