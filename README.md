# ChIP-Seq Analysis of TRRAP and CHD8 proteins in Autism

## Overview
This project analyzes ChIP-seq data for the proteins TRRAP and CHD8 to explore their roles in transcriptional regulation, particularly in the context of autism spectrum disorder (ASD). The study focuses on identifying binding sites, enriched motifs, and potential functional pathways associated with these proteins.

## Data and Methods

### Data
- **ChIP-Seq Samples**
  - **TRRAP sample**: Identifies TRRAP-bound genomic regions.
  - **CHD8 sample**: Identifies CHD8-bound genomic regions.
  - **Control sample**: Used to filter out non-specific signals.
- **Reference Genome**: hg38
- **Databases Used**: ENCODE, GREAT and HOMER

### Tools and Software
- **Peak Calling**: MACS2
- **Genome Visualization**: IGV
- **Motif Enrichment Analysis**: MEME Suite, HOMER
- **Functional Annotation**: GREAT, EnrichR
- **Data Processing**: Python, R

## Key Findings
- **Motif Enrichment**:
  - E2F and MYC motifs were enriched, linking TRRAP and CHD8 to cell cycle regulation and neural development.
  - **IRF motifs** were identified in both TRRAP and CHD8 samples, suggesting their involvement in immune-related transcriptional programs.
- **Functional Pathways**:
  - Shared genes between TRRAP and CHD8 suggest common regulatory roles.
  - Unique CHD8 targets were associated with **cobalamin (B12) metabolism**, a process linked to ASD.
  - TRRAP and CHD8 binding sites overlap with genes involved in **antiviral signaling**, aligning with literature suggesting immune dysfunction in ASD.
