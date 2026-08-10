# Genomics

## Basics
- **Gene / Exon / Intron** — coding unit; expressed vs. spliced-out regions.
- **Genotype vs. Phenotype** — genetic makeup vs. observed trait.
- **Germline vs. Somatic mutation** — inherited vs. acquired-in-tumor.
- **Driver vs. Passenger mutation** — causally contributes to cancer vs. incidental.
- **Oncogene / Tumor suppressor** — gain-of-function cancer-promoting / loss-of-function protective gene.
- **Tumor mutational burden (TMB)** — mutation count per Mb; immunotherapy biomarker.
- **Microsatellite instability (MSI)** — DNA repair deficiency marker.

## Sequencing Types
- **WGS** — whole genome sequencing.
- **WES** — whole exome sequencing (coding regions only, cheaper).
- **Targeted panel sequencing** — clinical gene panels (e.g. FoundationOne).
- **RNA-seq** — transcriptome/expression profiling.
- **Single-cell RNA-seq (scRNA-seq)** — per-cell expression, tumor heterogeneity. `scanpy`, `Seurat`
- **Spatial transcriptomics** — expression with tissue location (Visium, Xenium).
- **ATAC-seq** — chromatin accessibility.
- **ChIP-seq** — protein-DNA binding (transcription factors, histone marks).
- **Bisulfite sequencing** — DNA methylation profiling.
- **Liquid biopsy / ctDNA** — cell-free tumor DNA from blood.

## Variant Concepts
- **Allele frequency (VAF)** — fraction of reads supporting a variant; tumor purity/clonality signal.
- **Tumor heterogeneity** — subclonal variation within a tumor.
- **Clonal evolution** — how subclones change over time/treatment.
- **Fusion gene** — hybrid gene from structural rearrangement (e.g. BCR-ABL).
- **Loss of heterozygosity (LOH)** — loss of one allele, often uncovering a recessive mutation.

## Expression & Regulation
- **Differential expression** — genes changed between conditions. `DESeq2`, `edgeR`, `limma`
- **Gene set enrichment analysis (GSEA)** — pathway-level significance.
- **Molecular subtype** — expression-based tumor classification (e.g. PAM50 for breast cancer).
- **Epigenetics** — heritable regulation without sequence change (methylation, histone marks).

## Databases
- **Ensembl / RefSeq** — gene/transcript annotation.
- **dbSNP / gnomAD** — population variant frequency.
- **OncoKB / CIViC** — clinical variant interpretation for cancer.
- **DepMap** — cancer cell line dependency/CRISPR screen data.

## Links
- [gnomAD browser](https://gnomad.broadinstitute.org/)
- [UCSC Genome Browser](https://genome.ucsc.edu/)
- [cBioPortal](https://www.cbioportal.org/)
