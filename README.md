# Somatic Variant Calling and Annotation Pipeline

## Overview

A reproducible bioinformatics workflow for identifying genetic variants from whole-exome sequencing (WES) data using GATK Best Practices.

The project explores read quality control, alignment, duplicate marking, base quality score recalibration (BQSR), variant calling, filtering, and functional annotation.

## Dataset

- **Sample:** NA12878
- **Sequencing:** Whole Exome Sequencing (WES)
- **Platform:** Illumina HiSeq
- **Reference genome:** GRCh38 (hg38)
- **Benchmark:** Genome in a Bottle (GIAB)

## Workflow

1. Reference genome preparation
2. Read quality control
3. Read alignment using BWA
4. Duplicate marking
5. Base Quality Score Recalibration (BQSR)
6. Variant calling using GATK HaplotypeCaller
7. Variant filtering
8. Variant annotation
9. Benchmarking against GIAB truth calls

## Tools

- BWA
- SAMtools
- GATK
- FastQC
- fastp
- Picard
- BCFtools
- SnpEff
- SnpSift

## Project Structure

See the repository directory structure for scripts, configurations, documentation, and results.

## Note

NA12878 is a reference genome sample, not a CLL tumor-normal patient dataset. This project demonstrates germline variant calling and benchmarking, not actual somatic mutation discovery.

## Status

In progress.

