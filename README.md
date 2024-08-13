# Exploratory Data Analysis of Skin Cancer Mutations
An experiment in literate programming

## Names and Affiliations
Emily Adams  
Emory University

## Objectives
This project focuses on the exploratory data analysis (EDA) of skin cancer mutations, aiming to understand the distribution of genomic locations, the relationship between unique primary sites and mutation proportions, and the consistency of primary site data across chromosomes.

## Methods Used
- **Data Filtering and Preparation**: Filtering, removing NA values, ensuring data integrity.
- **Statistical Analysis**: Linear modeling, Chi-square test.
- **Visualization**: Histograms, scatter plots, bar charts with error bars.

## Platforms/Languages Used
- **Programming Language**: R
- **Libraries**: tidyverse
- **Platform**: RStudio

## Research Questions
1. **Distribution of Mutations**: What are the key genomic regions where skin cancer mutations are clustered?
2. **Relationship Analysis**: Is there a significant relationship between the number of unique primary sites and the proportion of mutations?
3. **Chromosome Consistency**: How does primary site consistency vary across different chromosomes?

## Specific Models and Visualization Techniques
- **Histograms**: To visualize the distribution of genomic start positions.
- **Linear Model**: Used to assess the relationship between unique primary sites and mutation proportions.
- **Scatter Plots**: To show the correlation between unique primary sites and mutation proportions, including a trend line.
- **Bar Charts**: To compare the proportions of single primary site mutations by chromosome, including error bars to represent confidence intervals.

## Challenges
- **Data Quality**: Handling NA values and ensuring all variables are correctly formatted.
- **Statistical Significance**: Interpreting weak correlations and understanding their implications.
- **Visualization**: Adjusting plot settings to highlight relevant data while maintaining clarity.

## Potential Next Steps
1. **Functional Implications**: What are the biological implications of the clusters of mutations observed in specific genomic regions? Further research could explore whether these regions are associated with known cancer-related genes or pathways.
2. **Mechanisms of Consistency**: Why do certain chromosomes exhibit higher proportions of mutations with a single primary site? Delving into the genetic and environmental factors influencing these patterns could provide valuable insights.
3. **Validation of Relationships**: Given the weak correlation between unique primary sites and mutation proportions, could other factors be influencing this relationship? Expanding the analysis to include additional variables or different types of mutations might yield more robust results.
4. **Broader Implications**: How do these findings compare with mutation patterns in other cancer types? A comparative analysis could reveal whether the observed patterns are specific to skin cancer or part of a broader trend across different cancers.

## Data Set Cited
Wellcome Sanger Institute. (2024, May 21). Cosmic_MutantCensus_Tsv_v100_GRCh37.tar (Census Genes Mutations Release v100). COSMIC Catalogue of Somatic Mutations in Cancer. [COSMIC Download Link](https://cancer.sanger.ac.uk/cosmic/download/cosmic/v100/mutantcensus)
