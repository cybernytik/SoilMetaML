# SoilMetaML
A reproducible bioinformatics and machine learning pipeline for soil microbiome analysis using 16S rRNA sequencing data.

## About
SoilMetaML is a bioinformatics research project focused on analyzing soil microbial communities using 16S rRNA amplicon sequencing data and machine learning approaches.

The project aims to develop a reproducible computational workflow that transforms raw sequencing reads into taxonomic profiles and uses microbial community composition for predictive modeling.

## Research question
Can soil microbial community composition, determined through 16S rRNA amplicon sequencing, be used to predict differences between soil environmental or land-use categories?

### Research objectives
1. Retrieve publicly available soil 16S rRNA sequencing datasets.
2. Characterize microbial communities using amplicon sequence variants (ASVs).
3. Investigate differences in taxonomic composition between sample groups.
4. Develop and compare machine learning classifiers.
5. Optimize model hyperparameters using Optuna.
6. Identify microbial taxons associated with predictive performance.

The final classification task will be selected based on the availability and quality of sample metadata.

## Dataset

## Workflow
1. Data acquisition and metadata parsing.
2. Quality control using FastQC.
3. Amplicon processing using DADA2.
4. Taxonomic assignment using the SILVA reference database.
5. Feature extraction and dataset preparation.
6. Machine learning with scikit-learn.
7. Hyperparameter optimization using Optuna.
8. Model evaluation and visualization.

## Technology stack
- Python
- R
- DADA2
- FastQC
- SILVA
- Pandas
- NumPy
- Scikit-learn
- Optuna
- Matplotlib
- Seaborn
- Git and GitHub

## Results

## Reproducibility

## References
