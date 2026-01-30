Project Title

Gender Differences in Academic Stress

Module

Data Science for Brain and Behaviour

Project Description:

This project examines whether self-reported academic stress differs between male and female university students. The analysis was conducted as part of the Data Science for Brain and Behaviour module, with the aim of practising data cleaning, exploratory visualisation, and non-parametric statistical analysis using Python.

The project focuses on reproducibility and appropriate methodological choice given the properties of the data.

Dataset

The analysis uses a publicly available dataset examining student wellbeing, mental health, and academic experiences in a multicultural university environment. The dataset includes demographic variables and self-reported measures of academic pressure collected using Likert-type scales. The dataset origin was verified via a peer-reviewed publication (Nguyen et al., 2019; DOI: https://doi.org/10.3390/data4030124
).

Key variable used:

Gender

Academic pressure (Likert-type scale from 1 to 5)

Data Preparation;

The dataset was inspected and cleaned prior to analysis. This included:

Renaming variables for consistency

Converting variables to appropriate data types

Removing missing values

Restricting the analysis to male and female categories as provided in the dataset

All preprocessing steps are documented within the notebook.

Exploratory Analysis

Descriptive statistics and visualisations were used to explore the distribution of academic pressure scores. Histograms and boxplots were produced to examine central tendency, variability, and distribution shape across gender groups. These visualisations indicated discrete, ordinal data with similar distributions across groups.

Statistical Analysis

Group differences were examined using non-parametric methods. The primary inferential test reported is the Mann–Whitney U test, chosen due to the ordinal nature of the outcome variable and the absence of assumptions regarding normality. A permutation-based approach was also used within the notebook to support interpretation of the observed mean difference.

Interpretation and Limitations

Results are interpreted with caution due to the use of a single-item self-report measure and the ordinal scale of the data. Gender was treated as a binary variable as defined in the dataset, which limits inclusivity. These limitations are discussed in the accompanying written report.

Reproducibility

The notebook is fully executable from top to bottom. All analyses were conducted in Python using standard scientific libraries, and results can be reproduced by running the notebook.