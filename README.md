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
