# katG Mutation Detector 🧬

This project simulates and detects point mutations (SNPs) in the katG gene from *Mycobacterium tuberculosis* using Python and Biopython.

## 🚀 What It Does
- Loads an original katG gene sequence (FASTA)
- Simulates a mutation (e.g. T → A at position 500)
- Compares wild-type and mutant sequences
- Outputs detected mutations in a `.txt` report

## 🗂️ Files Included
- `katG.fasta.txt` – original gene sequence
- `mutant_katG.fasta` – simulated mutated version
- `mutation_report.txt` – output file with SNP info
- `katG_Mutation_Detector.ipynb` – Jupyter Notebook with full code

## 🔧 Requirements
```bash
pip install biopython
