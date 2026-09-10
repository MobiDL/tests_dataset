# 🧬 MobiDL Tests Dataset

**Test datasets for validation and qualification of MobiDL bioinformatics workflows.**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Last Commit](https://img.shields.io/github/last-commit/MobiDL/tests_dataset)](https://github.com/MobiDL/tests_dataset/commits/main)

---

## 📌 **About**
This repository contains **test datasets** designed for:
- **Validating** the correct functioning of MobiDL workflows
- **Qualifying** performance and robustness of pipelines [need to be developped]
- **Facilitating development** by providing reusable data.

> ⚠️ **Important**: These datasets are **intended for testing purposes only**. They may contain **synthetic** or **anonymized** data. Do **not** use them for clinical or production analyses.

---

## 📊 **Available Datasets**

### 🔹 **`smallest/`**

| **Property**       | **Value**                          |
|--------------------|------------------------------------|
| **Description**    | Minimal dataset for quick testing  |
| **Size**           | ~172K                              |
| **Format**         | FASTQ (paired-end), BED, BAM       |
| **Origin**         | Subset of HG002 sequencing on SRY  |
| **Use Case**       | Alignment and calling testing      |
| **Last Updated**   | 2026-09-10                         |

**Contents**:

```
├── bam
│   ├── sample.bam
│   └── sample.bam.bai
├── bed
│   └── test.bed
├── fasta
│   ├── chr.dict
│   ├── chr.fa
│   ├── chr.fa.fai
│   ├── chr.fa.l2b
│   └── chr.fa.mbw
├── fastq
│   ├── fq1.fq.gz
│   └── fq2.fq.gz
└── knownsites
    ├── knownsites1.vcf.gz
    └── knownsites1.vcf.gz.tbi
```