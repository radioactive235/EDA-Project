# EDA Project
This project is an exploratory data analysis (EDA) on the data set of stroke risk factors.

#### -- Project Status: Completed

### Methods Used
* Basic Statistics
* Student's T-Test
* Data Visualization
* Interactive Maps

### Technologies
* R 
* HTML

## Project Description
This project provides a correlation analysis between stroke mortality rates and income. Because stroke mortality rates differ between age groups, correlation analyses are categorized according to 35-64 years old and 65+ years old age groups. This is accompanied by maps to depict the stroke mortality percent changes over the decade of 2010-2019.

What are the research questions?
 * Is income related to stroke mortality rates?
 * Do correlational analyses from current research support a relationship between these variables?
 * Do specific counties/locales present stronger evidence to support/not support a correlation between income and stroke mortality?

What are specific models and visualization techniques used in the project?
 * T-test for correlation coefficients
 * Line charts, correlation coefficient heat map, interactive choropleth map, frequency charts

Next steps and future directions
 * Isolate counties and locales within Georgia that display clusters of the greatest increases/decreases in stroke mortality and further analyze relationships between income levels and stroke mortality


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Open the EDA_final.html (codebook/EDA_final.html) directly to view the result of analysis.
3. If you wish to interact with the original R codes we used to generate the analysis, you could either:
   * open EDA_final.Rmd (codebook/EDA_final.Rmd) in your computer if RStudio has been installed
   * use the virtual environment here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/radioactive235/EDA-Project.git/HEAD) (note: any changes made in this virtual envrionment will NOT be 
     saved!). This virtual environment will take some time to launch.

## Directory Structure
```
.
└── EDA-Project/
    ├── codebook/
    │   ├── EDA_final.Rmd
    │   ├── EDA_final.html
    │   ├── diabetes_012_health_indicators_BRFSS2015.csv
    │   └── ga_data_inc.csv
    ├── .gitignore
    ├── README.md
    ├── install.r
    └── runtime.txt
```
(note: the two .csv files in the codebook/ folder are data sets used in the analysis)

## Featured Notebooks/Analysis/Deliverables
* EDA_final.Rmd (codebook/EDA_final.Rmd)


## Contributing Members
* Anji Ni and Jared Darrow
