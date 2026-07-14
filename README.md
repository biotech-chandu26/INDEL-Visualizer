# INDEL-Visualizer

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Platform](https://img.shields.io/badge/Linux-Windows-Mac-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## Overview

Indel Visualizer is a Python tool for analyzing pairwise sequence alignments and automatically detecting insertions and deletions (indels). It generates summary statistics together with publication-quality visualizations highlighting each indel event.

The program accepts an aligned FASTA file containing exactly two sequences (reference and query).

---

## Features

- Detects insertions and deletions
- Counts insertion/deletion events
- Counts inserted/deleted bases
- Calculates alignment identity
- Calculates gap percentage
- Generates CSV reports
- Produces publication-quality figures for every indel
- Saves alignment statistics
- Compatible with Google Colab

---

## Workflow

Alignment FASTA

↓

Load sequences

↓

Indel detection

↓

Alignment statistics

↓

CSV reports

↓

Generate figures

↓

Output directory

---

## Installation

Clone the repository

```bash
git clone https://github.com/USERNAME/Indel-Visualizer.git

cd Indel-Visualizer
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

```bash
python indel_visualizer.py alignment.fasta
```

or simply

```bash
python indel_visualizer.py
```

if the file is named

```
alignment.fasta
```

---

## Output

```
Output/

alignment_summary.txt

alignment_statistics.csv

indel_summary.csv

figures/

indel_001_insertion_5bp.png

indel_002_deletion_3bp.png

...
```

---

## Example Figure

(Add screenshot here)

---

## Input Format

```
>Reference
ACTGACTGACTGACTG

>Read
ACTGACT--CTGACTG
```

---

## Statistics Reported

- Alignment length
- Sequence identity
- Number of insertions
- Number of deletions
- Number of inserted bases
- Number of deleted bases
- Gap percentage
- Alignment score (approximate)

---

## Applications

- ONT sequencing
- Illumina sequencing
- Variant analysis
- Genome assembly validation
- Structural variation studies
- Comparative genomics
- Teaching sequence alignment concepts

---

## Citation

If you use this software, please cite this GitHub repository.

---

## License

MIT License

---

## Author

Chandrajeet
