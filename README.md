# ARIC_Step

This repository contains the analysis code and results for the study deploying and comparing multiple open-source step counting algorithms in the Atherosclerosis Risk in Communities (ARIC) study.

## Study Overview

The study aims to deploy and compare five open-source step-counting algorithms (ADEPT, Oak, SDT, Verisense, and Stepcount) using wrist-worn accelerometry data from 1,150 older adults in the ARIC cohort. We examined step count distributions and their associations with health outcomes, providing insights into algorithm performance and implications for public health recommendations.

## Files and Structure

- **scripts/**: Contains all the analysis scripts used to process data and perform statistical analyses.
- **results/**: Includes results, figures, and output files generated during the analysis.
- **README.md**: This file, providing an overview of the repository and instructions for use.
- **WIT_Step_R.Rproj**: R project file for easy navigation and project management.

## How to Use

1. Clone this repository: git clone https://github.com/SNGao/ARIC_Step.git

2. Install required packages and dependencies in R (see the `scripts` folder for package requirements).
3. Run the scripts in the `scripts/` folder to replicate the analysis.

## Abstracts

**Background**: Step counting from wrist accelerometry data is widely used in physical activity research and practice. While several open-source algorithms can estimate steps from high-resolution accelerometry data, there is a critical need to compare these algorithms and provide practical recommendations for their use in older adults.

**Methods**: 1,282 Atherosclerosis Risk in Communities (ARIC) participants (mean age 83.4, 60% female) wore ActiGraph GT9X wrist devices for 7 days, collecting 80Hz tri-axial accelerometry data. Five open-source step-counting algorithms (ADEPT, Oak, SDT, Verisense, and Stepcount) were applied to this data. Step count distributions and their associations with health outcomes were compared.

**Results**: The estimated mean daily step counts varied widely across algorithms, ranging from 988 for ADEPT to 23,607 for SDT. Pearson correlations across methods ranged from moderate (r=0.52) to very strong (r=0.96). All step counts were highly associated with age, with an estimated decline of 119.0 to 142.8 steps/year (all p<0.001) with comparable trends observed across demographic subgroups. After z-score standardization (subtracting the population mean and dividing by the population standard deviation), the estimated steps from each algorithm exhibited similar directionality and magnitude of association with various metabolic, cardiovascular, physical performance, and cognitive outcomes (all p<0.001).

**Conclusion**: The estimated step counts algorithms are highly correlated, and, after z-scoring, have similar and highly significant associations with health outcomes. Because the total number of steps varies widely across algorithms, interpretation and translation of results for health monitoring and clinical use in older adults depends on the choice of step counting algorithm.

## Contact

For any questions or collaborations, please contact [SNGao](mailto:sgao57@jh.edu).

## Reference
Gao S, Zhou X, Koffman L, Wanigatunga AA, Schrack JA, Crainiceanu CM, Muschelli J. Comparing step counting algorithms for high-resolution wrist accelerometry data in older adults in the ARIC study. J Gerontol A Biol Sci Med Sci. 2025 Feb 18:glaf034. doi: 10.1093/gerona/glaf034. Epub ahead of print. PMID: 39963747.
