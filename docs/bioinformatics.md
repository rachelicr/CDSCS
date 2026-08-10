# Bioinformatics

## File Formats
- **FASTA** — raw sequences.
- **FASTQ** — sequence + quality scores (raw sequencer output).
- **SAM/BAM** — aligned reads (text/binary). `samtools`
- **CRAM** — compressed BAM.
- **VCF** — variant calls.
- **BED/GTF/GFF** — genomic intervals, gene annotation.
- **MAF** — mutation annotation format (TCGA standard).

## QC & Preprocessing
- **Phred quality score** — per-base confidence.
- **FastQC** — raw read QC. `FastQC`
- **Adapter trimming** — remove sequencing adapters. `Trimmomatic`, `fastp`
- **Duplicate marking** — flag PCR duplicates. `Picard`

## Alignment
- **Reference genome** — GRCh38/hg38 standard for human.
- **Read alignment/mapping** — placing reads on genome. `BWA` (DNA), `STAR` (RNA), `Bowtie2`
- **Indel realignment** — legacy step, largely replaced by haplotype-based callers.
- **Base quality score recalibration (BQSR)** — `GATK`

## Variant Calling
- **SNV** — single nucleotide variant.
- **Indel** — insertion/deletion.
- **Somatic vs. germline calling** — tumor-only or tumor-normal paired. `GATK Mutect2`, `Strelka2`
- **Copy number variant (CNV)** — gains/losses of genomic regions. `CNVkit`, `GATK CNV`
- **Structural variant (SV)** — large rearrangements. `Manta`, `Delly`
- **Variant annotation** — functional consequence. `VEP`, `ANNOVAR`, `SnpEff`
- **Variant filtering** — remove artifacts (panel of normals, allele frequency).

## Pipelines & Workflow
- **Pipeline/workflow manager** — reproducible multi-step analysis. `Nextflow`, `Snakemake`
- **Containers** — environment reproducibility. `Docker`, `Singularity`
- **nf-core** — curated cancer genomics pipelines (sarek, rnaseq).

## Databases & Resources
- **TCGA** — The Cancer Genome Atlas, large multi-omic cancer cohort.
- **COSMIC** — Catalogue of Somatic Mutations in Cancer.
- **cBioPortal** — visualization/query of cancer genomics data.
- **ClinVar** — variant clinical significance.
- **GDC (Genomic Data Commons)** — NCI data repository.

## Links
- [Galaxy Project (no-code pipelines)](https://usegalaxy.org/)
- [rnabio.org training](https://rnabio.org/)
- [GATK Best Practices](https://gatk.broadinstitute.org/hc/en-us/sections/360007226651-Best-Practices-Workflows)
