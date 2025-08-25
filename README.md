<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/cff071b8-4bfa-49f2-b840-9324aee7aea2" />DNA Methylation Ageing Atlas

This repository hosts the codebase developed for the DNA methylation ageing atlas project. The project integrates multi-tissue, multi-cohort DNA methylation data to map how ageing is reflected in the methylome and to uncover mechanisms, biomarkers, and targets with translational potential.

The repository is organised into analysis modules that span from raw data preprocessing to integrative network modelling and web deployment. While data files are not included, the code provides reproducible workflows and examples for each analysis stage.

Repository Structure
1. Preprocessing

Scripts for data import, cleaning, and harmonisation, including:

Curation of open-access and collaborator data

Sample and probe quality control

Normalisation and batch correction

Metadata integration

2. Differentially Methylated Positions (DMPs)

Age-associated DMP discovery using linear models

Multiple-testing correction and significance filtering

Cross-tissue overlap analysis

3. Variably Methylated Positions (VMPs)

Identification of CpGs with age-associated variance changes

Comparison of variance patterns across tissues

Enrichment of biological processes linked to variability

4. Entropy Analysis

Calculation of Shannon entropy at CpG-level

Age trajectories of epigenetic entropy across tissues

Links between entropy, functional pathways, and ageing phenotypes

5. WGCNA (Weighted Gene Co-expression Network Analysis)

Construction of CpG modules from significant sites

Identification of age-associated modules

Hub CpG and gene mapping

Functional enrichment of key modules

6. Gene–Gene Network Analysis

Integration of CpG-level data to gene-level networks

Identification of driver genes

Pathway annotation and tissue-specific network comparison

7. In-Silico Validation & Perturbation

Simulation of gene knockouts and perturbations

Module robustness testing

Exploration of beneficial vs. detrimental network shifts

8. Tissue Integration

Cross-tissue comparison of ageing signatures

Identification of shared and tissue-specific CpGs, modules, and pathways

Integration with external datasets for validation

9. Website Deployment (Website LINK: https://bioinformatics.erc.monash.edu/apps/human-aging-atlas/)

Scripts for preparing and exporting data to interactive formats

Shiny/website code for public browsing of atlas results

Efficient storage and query of large-scale methylation outputs

Usage

Each module contains example scripts and documentation. The code is designed to be modular so users can adapt specific steps (e.g., preprocessing, WGCNA, entropy analysis) for their own projects.

Citation

If you use this code, please cite our DNA Methylation Ageing Atlas Across 17 Human Tissues paper:
[doi: https://doi.org/10.1101/2025.07.21.665830]

✨ This repository is intended to serve as both a research resource and a teaching tool for researchers in ageing biology, epigenomics, and computational biology.
