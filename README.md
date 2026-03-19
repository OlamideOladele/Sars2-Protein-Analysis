#SARS-CoV-2 Complete Genome Analysis Project Overview

This bioinformatics project focuses on the genomic characterization of the SARS-CoV-2 isolate Wuhan-Hu-1. Using Python, I developed a pipeline to parse the complete viral genome, calculate nucleotide distribution, and perform essential Quality Control (QC) metrics to ensure data integrity.

Dataset Information
Target: Severe acute respiratory syndrome coronavirus 2 (Complete Genome)
NCBI Reference Sequence: NC_045512.2
Sequence Length: 29,903 base pairs (bp)

Technical StackLanguage: Python 3.13.5
Environment: Jupyter Lab (.ipynb)
Libraries: Matplotlib (Visualization), OS (File Handling)

Key Features
Full-Genome Parsing: Handles large-scale FASTA files by stripping metadata and formatting raw strings.
Nucleotide Distribution: Precise calculation of A, T, G, and C percentages across nearly 30,000 bases.
GC/AT Content Mapping: Identifies the molecular balance (37.98% GC) which influences viral stability and evolution.
Quality Control Gate: Integrated logic to verify sequence purity and flag unknown ("N") bases.
Data Visualization: Generates a professional bar chart to represent the genomic "fingerprint."

Final Sequence Report
Nucleotide Percentage
Adenine (A)29.94%
Thymine (T)32.08%
Guanine (G)19.61%
Cytosine (C)18.37%
Total GC Content37.98%
Total AT Content62.02%

QC Status: ✅ PASS (100% Sequence Integrity)

How to Run
Clone the repository.
Place sequence.fasta in the project root.
Open Sars2spikeprotein.ipynb and run all cells to reproduce the report and charts.
