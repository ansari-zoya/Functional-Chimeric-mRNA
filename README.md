# Functional Chimeric mRNA Analysis

## Project Overview

This project focuses on the computational identification and analysis of functional chimeric mRNAs using long-read and short-read RNA sequencing data.

The project is inspired by the study "Functional chimeric mRNAs encode proteins in mammalian immunity."

## Main Objectives

- Identify candidate chimeric mRNAs
- Validate candidate transcripts computationally
- Analyze exon structures and fusion breakpoints
- Predict potential open reading frames (ORFs)
- Compare selected findings across species

## Software Environment

### Programming Environment

- Python 3.12.3
- Biopython 1.88
- NumPy 2.5.3
- pandas 3.0.6
- Matplotlib 3.11.2
- ORFipy 0.0.4

### Bioinformatics Tools

- Minimap2 2.26-r1175
- Samtools 1.19.2
- Salmon 1.10.2

### Development Environment

- Ubuntu 24.04.5 LTS (WSL2)
- Git 2.43.0
- Python virtual environment (.venv)

## Project Structure

Functional_Chimeric_mRNA/
├── data/
├── reference/
├── results/
├── scripts/
├── README.md
├── requirements.txt
└── .gitignore

## Analysis Workflow

The project will follow a computational workflow for identifying and characterizing candidate chimeric mRNAs:

1. Data acquisition
2. Quality control of sequencing data
3. Reference genome and transcriptome preparation
4. Long-read alignment
5. Chimeric transcript detection
6. Fusion breakpoint and exon-structure analysis
7. Short-read validation
8. ORF prediction
9. Transcript quantification
10. Differential expression analysis
11. Comparative analysis
12. Visualization and interpretation

### Planned Tools

- Minimap2 — long-read sequence alignment
- Samtools — alignment-file processing
- ORFipy — open reading frame prediction
- Salmon — transcript quantification
- Python — sequence processing and analysis
- R — statistical analysis and visualization

## Project Status

### Completed

- Project repository initialized with Git
- WSL2 development environment configured
- Python virtual environment created
- Core Python packages installed
- Core bioinformatics tools installed and verified
- Project directory structure established
- Initial project documentation created

### Next Steps

- Reference genome and transcriptome preparation
- RNA-seq dataset selection
- Chimeric transcript detection workflow
- Computational validation of candidate transcripts

### Planned

- ORF analysis of candidate chimeric transcripts
- Transcript quantification
- Differential expression analysis
- Comparative analysis
- Visualization of results
- Final project documentation

## Critical parameter note (from TYPHON GitHub issue #1, Oct 2026)

- JAFFAL MIN_LOW_SPANNING_READS set to 1 (not default 2)
  - TYPHON applies this automatically during setup
  - Many chimeras including Gsdmd:Tmem106a have only 1 supporting read
  - Running JAFFAL standalone without this change causes ~30% missed chimeras
- JAFFAL: use version 2.3 (self-reports as 2.4_dev at runtime, same thing)
- Reference: GENCODE M28 confirmed by authors, do not upgrade
- Source: https://github.com/erenada/TYPHON/issues/1
## TYPHON version
Commit: 2179e9daa445f055c5b228ed6f7b33c2373ed765
Cloned: Sat Oct  3 12:00:14 UTC 2026
Source: https://github.com/erenada/TYPHON

## Tool versions (typhon_env)
Minimap2: 2.31-r1302
SAMtools: 1.24
Environment installed: Sun Oct  4 07:03:07 UTC 2026
LongGF: 0.1.2 (called as 'LongGF' with capital L)
