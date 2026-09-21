# Supplementary methodology and data dictionary

## Data provenance

1. Manuscript Tables 2–4 supply the 68 paper IDs, years, titles, algorithm categories, quantum frameworks, application domains, and repository links.
2. Manuscript Table A3 supplies the reproducibility assessment data.
3. Existing corrected Figure 6 and Figure 7 CSV files supply the paper-level country/institution frequencies.
4. RIS metadata supplements author names and arXiv subject classes where a title match to the final 68-paper corpus was found.
5. `raw_affiliations_68_papers.txt` is retained as source material for affiliation-based country/institution checks.

## Field notes

`Algorithm_Type`, `Quantum_Framework`, and `Application_Domain` preserve the terminology used in the manuscript.

`arXiv_Categories` contains the arXiv subject classes available in the matched RIS records. The manuscript revision should describe Figure 10 using arXiv terminology consistently.

The country and institution CSVs currently contain the corrected values used by the corresponding figures. The country file contains all country bars represented in the revised figure; the institution file contains the leading institutions displayed in Figure 7.
