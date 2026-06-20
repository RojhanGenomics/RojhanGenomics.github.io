---
title: "Viral Genomics Pipeline (Nextflow DSL2)"
excerpt: "Reproducible viral genomics workflow for Illumina paired-end sequencing data"
header:
  teaser: /images/viral-pipeline-teaser.png
---

## Overview

A reproducible viral genomics workflow built with Nextflow DSL2 for processing Illumina paired-end sequencing data.

## Features

- ✅ Quality control with FastQC and fastp
- ✅ Read alignment with BWA-MEM
- ✅ BAM processing with Samtools
- ✅ Variant calling with BCFtools
- ✅ Consensus genome generation
- ✅ Resumable execution and caching
- ✅ Modular workflow architecture

## Test Results

Tested on public Ebola virus sequencing data (SRR1553428):

| Metric | Result |
|--------|--------|
| **Genome coverage** | 100% |
| **SNPs identified** | 561 |

## 🔗 Links

- [GitHub Repository](https://github.com/RojhanGenomics/viral-genomics-pipeline)
- [Author Website](https://RojhanGenomics.github.io)

## Author

**Mahdieh Rojhannezhad, Ph.D.**
