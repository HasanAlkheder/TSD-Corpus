# TSD Corpus

## Overview

The TSD Corpus is a benchmark evaluation dataset for Turkish–Syrian Arabic dialogue translation with speaker metadata.

It was developed to evaluate large language models (LLMs) under different prompting strategies for gender-aware and dialect-aware translation. The released benchmark corresponds to the evaluation set used in our study and is intended to support reproducible research on low-resource Arabic machine translation.

---

## Languages

- Turkish
- Modern Standard Arabic (MSA)
- Syrian Arabic

---

## Dataset

The released evaluation benchmark contains **1,000** human-produced dialogue segments with the following fields:

| Column | Description |
|--------|-------------|
| ID | Sentence identifier |
| Character | Speaker name |
| Gender | Speaker gender |
| Turkish | Source sentence |
| MSA | Human Modern Standard Arabic translation |
| Syrian_Arabic | Human Syrian Arabic dubbing translation |

---

## Statistics

- Total evaluation sentence pairs: **1,000**
- Languages: Turkish, Modern Standard Arabic, Syrian Arabic
- Parallel dialogue corpus
- Human-produced translations
- Speaker metadata available for every sentence

---

## Repository Contents

```
TSD-Corpus/
│
├── dataset/
│   └── TSD-Corpus.csv
│
├── statistics/
│   └── statistics.txt
│
└── README.md
```

---

## Usage

This benchmark is intended for academic research, benchmarking, and reproducibility studies on Turkish–Arabic machine translation, gender-aware translation, and Arabic dialect processing.

If you use this benchmark in your research, please cite the accompanying paper.

---

## Citation

```
Hasan Alkhder et al.

Gender Ambiguity in Turkish–Syrian Arabic Dubbing:
A Benchmark and Empirical Study of Large Language Models

(IEEE Access, under review)
```

BibTeX will be added after publication.

---

## License


This benchmark is released under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License.

The released evaluation benchmark is provided for academic and non-commercial research purposes with permission from the content provider. Commercial use is not permitted.

You are free to:

- Share the benchmark.
- Adapt and build upon the benchmark.
- Use it for non-commercial research purposes.

Under the following conditions:

- Appropriate credit must be given.
- A link to the license must be provided.
- Commercial use is not permitted.

For details, see:

https://creativecommons.org/licenses/by-nc/4.0/

---

## Contact

For questions regarding the benchmark, please contact:

**Hasan Alkhder**

GitHub: https://github.com/HasanAlkheder
