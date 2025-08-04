# Enterprise Survey 2023 - Paraguay: Geometric Data Analysis

This repository contains the scripts developed for the geometric data analysis (GDA) conducted as part of a master's thesis (*mémoire*) in Quantitative Sociology and Demography (M2 SQD, Université Paris-Saclay – Institut Polytechnique de Paris). The project focuses on the Paraguayan economic space and its internal structures of power and domination, using data from the 2023 **Enterprise Survey** by the **World Bank (WBES)**.

The analysis follows a two-step exploratory procedure:
- **Recoding of relevant variables** to align with sociological concepts (capital, competition, domination, symbolic power, etc.)
- **Geometric Data Analysis (GDA)** through **Multiple Correspondence Analysis (MCA)** and **Hierarchical Clustering (HCA)**, aimed at uncovering latent structures within the space of formal enterprises.

## Objectives

The main goal is to identify structurally differentiated groups of firms based on legal, economic, institutional, and symbolic dimensions. The analysis aims to:
- Explore patterns of domination and resource concentration in the Paraguayan business field
- Understand the role of the State and of export-oriented activities in structuring firm trajectories
- Contribute to the reflexive use of quantitative methods in economic sociology

## Structure of the repository

- `git_recod_enterprise23.Rmd`: Recoding and preprocessing of variables
- `git_AGD_enterprise23.Rmd`: MCA + HCA analysis and interpretation of clusters
- `LICENSE`: Creative Commons Attribution 4.0 International
- `.gitignore`: Standard R Markdown exclusions

> Note: Code is written in French, in line with the academic context of the original research.

## Data source

- **World Bank – Enterprise Surveys**
- Dataset: *Paraguay Enterprise Survey 2023*  
- Publicly available: [https://www.enterprisesurveys.org](https://www.enterprisesurveys.org)  
- Unit of analysis: formal firms operating in manufacturing, retail, and other services  
- Sample size: 377 observations

> Disclaimer: This repository does not include the original data. Interested users should register and download it from the official World Bank portal.

## Reference

This work was developed as part of the master's thesis:
- **Title:** *Structures, réseaux et pouvoir dans l’économie paraguayenne contemporaine*  
- **Author:** Sergio Rojas  
- **Date:** June 2025  
- **Institution:** Université Paris-Saclay – École normale supérieure Paris-Saclay - UVSQ | Institut Polytechnique de Paris – ENSAE

## Contact

For suggestions, corrections or collaboration inquiries, please contact:  
**Sergio Rojas** – rojasergio6@gmail.com

## License

This project is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License.  
See the [LICENSE](LICENSE) file for details.
