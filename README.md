# TSD Corpus

## Overview

The TSD Corpus is a benchmark evaluation dataset for Turkish–Syrian Arabic dialogue translation with speaker metadata.

The benchmark was developed to evaluate large language models under different prompting strategies for gender-aware and dialect-aware translation.

## Languages

* Turkish
* Modern Standard Arabic (MSA)
* Syrian Arabic

## Dataset

The released benchmark contains human-produced dialogue segments with the following fields:

| Column        | Description                              |
| ------------- | ---------------------------------------- |
| ID            | Sentence identifier                      |
| Character     | Speaker name                             |
| Gender        | Speaker gender                           |
| Turkish       | Source sentence                          |
| MSA           | Human Modern Standard Arabic translation |
| Syrian_Arabic | Human Syrian Arabic dubbing translation  |

## Statistics

* Total evaluation sentence pairs: **1,000**
* Languages: Turkish, MSA, Syrian Arabic
* Parallel corpus
* Human-produced translations

## Repository Contents

```
dataset/
statistics/
README.md
```

## Citation

If you use this dataset, please cite:

```
Hasan Alkhder et al.

Gender Ambiguity in Turkish–Syrian Arabic Dubbing:
A Benchmark and Empirical Study of Large Language Models
```

## License

The released benchmark is intended for research purposes.
The complete corpus is not publicly redistributed due to licensing restrictions associated with the original source material.
