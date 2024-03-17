# Machine Learning and Bioinformatics Project
This is my research project, which includes three parts: machine learning modeling, FGSEA analysis, and STRINGdb analysis.

## Code Structure
- `model_prerocess.R`: Preprocessing code for machine learning models.
- `fgesa.R`: Code for enrichment analysis using FGSEA.
- `stringdb.R`: Code for network analysis using STRINGdb.

## Installation Guide
Before running these scripts, please make sure to install the following R packages:
- xgboost
- Boruta
- caret
- pROC
- ggplot2
- e1071
- MASS
- glm2
- glmnet
- BiocManager
- clusterProfiler
- fgsea
- tidyverse
- STRINGdb
- igraph
- ggraph

You can install these packages using `install.packages()` and `BiocManager::install()` commands in R.

## Usage
1. Place the required data files in the root directory of the project.
2. Run `model_prerocess.R` for data preprocessing and machine learning modeling.
3. Execute `fgsea_analysis.R` for FGSEA analysis.
4. Run `stringdb.R` for STRINGdb analysis.

## Contact
For questions or further information, please contact me at (guanrn2023@lzu.edu.cn).
