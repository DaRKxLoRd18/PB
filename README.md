# Ebola Transcriptomic Pathways Analysis

## Overview

This project, created by Group 13, focuses on analyzing the transcriptomic pathways involved in Ebola virus infections. By leveraging GEO datasets and bioinformatics tools, the project aims to identify and visualize differentially expressed genes and their enriched pathways, providing insights into the molecular mechanisms of the virus.

---

## Workflow

The project followed these steps:

1. **Data Search**:
   - Accessed the GEO database using relevant keywords to identify suitable datasets.
   - Example dataset: [GSE83563](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE83563).

2. **GEO2R Analysis**:
   - Compared gene expression between experimental groups to identify differentially expressed genes (DEGs).

3. **Grouping and Visualization**:
   - Segregated data into healthy and infected groups.
   - Plotted Volcano plots, Mean Difference plots, UMAP plots, Box plots, and P-Value histograms.

4. **Pathway Enrichment Analysis**:
   - Conducted KEGG pathway analysis using [tools](http://bioinformatics.sdstate.edu/go/).

5. **Result Interpretation**:
   - Identified pathways such as Ribosome, COVID-19, Malaria, and African Trypanosomiasis, highlighting potential host-pathogen interactions.

---

## Key Results

### Enriched Pathways:
1. **Ribosome**:
   - Fold Enrichment: 21.7
   - Suggests Ebola virus hijacks the host's protein synthesis machinery.

2. **COVID-19 Pathway**:
   - Indicates shared mechanisms between viral infections.

3. **Malaria and African Trypanosomiasis**:
   - Reflects potential co-infections or shared host response pathways.

---

## Contributions

- **Karan Yadav (2022234)**: Data Collection, Preprocessing, GEO2R Analysis.
- **Manveet Singh (2022280)**: KEGG Pathway Analysis, Result Interpretation, and Presentation.
- **Mayank Gautam (2022283)**: Python Code and Web Application for Analysis.
---

## Tools and Technologies

- **GEO2R**: For differential gene expression analysis.
- **KEGG Pathway Tools**: For pathway enrichment analysis.
- **Python**: For automating analysis and web application development.

---

## Links

- [Dataset GSE83563](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE83563)
- [KEGG Pathway Tools](http://bioinformatics.sdstate.edu/go/)

---

## Acknowledgments

Special thanks to all contributors for their efforts in completing this project and uncovering new insights into Ebola virus infections.
