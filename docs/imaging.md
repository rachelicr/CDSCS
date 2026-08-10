# Imaging

## Modalities
- **Radiology (CT/MRI/PET/Ultrasound)** — macroscopic, non-invasive tumor imaging.
- **Histopathology (H&E slides)** — microscopic tissue structure, diagnostic gold standard.
- **Immunohistochemistry (IHC)** — antibody-based protein detection in tissue.
- **Whole slide imaging (WSI)** — digitized gigapixel pathology slides.
- **Multiplex/spatial imaging (CODEX, IMC, Visium)** — many markers + spatial location simultaneously.

## Formats & Tools
- **DICOM** — standard medical imaging format (radiology).
- **SVS/NDPI** — whole slide image formats.
- **QuPath** — open-source pathology image analysis. `QuPath`
- **3D Slicer / ITK-SNAP** — radiology segmentation tools.

## Preprocessing
- **Stain normalization** — correct color variation across H&E slides (Macenko, Reinhard methods).
- **Tiling/patching** — split gigapixel WSI into manageable tiles for ML.
- **Registration** — aligning images across modalities/timepoints.
- **Segmentation** — delineating tumor, organ, or cell boundaries.

## Radiomics
- **Radiomics** — extracting quantitative features (shape, texture, intensity) from radiology images. `PyRadiomics`
- **Texture features** — GLCM, GLRLM — quantify heterogeneity.
- **RECIST criteria** — standardized tumor response measurement from imaging.

## Deep Learning for Imaging
- **CNN** — standard architecture for image classification/segmentation.
- **U-Net** — standard segmentation architecture (medical imaging default).
- **Multiple instance learning (MIL)** — standard for WSI-level prediction from tile-level features (no tile labels needed).
- **Foundation models (pathology)** — pretrained tile/slide encoders (e.g. UNI, CONCH, Virchow).
- **Vision Transformer (ViT)** — attention-based image architecture.

## Applications
- **Tumor grading/subtyping from WSI** — automated histology classification.
- **Mitosis/cell detection** — proliferation quantification.
- **Survival prediction from imaging** — combining WSI or radiomic features with outcomes.
- **Biomarker prediction from H&E** — inferring molecular status (e.g. MSI, mutation) directly from routine slides.

## Databases
- **TCGA imaging (Genomic Data Commons)** — paired WSI + multi-omic data.
- **The Cancer Imaging Archive (TCIA)** — public radiology datasets.
- **CAMELYON** — benchmark WSI metastasis detection dataset.

## Links
- [QuPath docs](https://qupath.readthedocs.io/)
- [PyRadiomics docs](https://pyradiomics.readthedocs.io/)
- [The Cancer Imaging Archive](https://www.cancerimagingarchive.net/)
