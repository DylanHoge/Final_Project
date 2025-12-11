## Gender, Race, and Income Correlation with Political Aﬀiliation in the United States

Team Members
- Dylan Hoge
- Virthiha Selvamuthukumaran
- Cordelia Tranfield

## Project Description

This project uses data from the 2020 American National Election Study (ANES) Time Series to examine how political party identification in the United States is related to basic demographic characteristics. The main research question is:

> How do gender, race, and income relate to identifying as a Democrat versus a Republican?

Using a cleaned subset of the ANES 2020 data, we estimate group differences in the proportion of respondents who identify as Democrats and fit a linear probability model to see how these relationships look when controlling for other variables.

## Data Source

- American National Election Studies (ANES) 2020 Time Series
- File used: `anes_timeseries_2020_stata_20220210.dta`

## Variables Used

Below are the main variables used in the analysis and how they are coded in our project dataset:

- `party_dem`: Binary outcome for party identification  
  - 1 = Democrat or leans Democrat  
  - 0 = Republican or leans Republican  
  - (Pure independents and others are excluded)

- `female`: Respondent gender  
  - 1 = Female  
  - 0 = Male  

- `white`: Race indicator  
  - 1 = White  
  - 0 = Non-white  

- `race3`: Race (3-category version, used for graphs)  
  - "White"  
  - "Black"  
  - "Other"  

- `income3`: Income group (3 categories)  
  - "Low"  
  - "Middle"  
  - "High"  

- `inc_sum`: Numeric income scale based on ordered ANES income categories  
  - Higher values = higher family income  

- `age`: Respondent age in years  

- `educ5`: Education level (5 ordered categories)  
  - Higher values = more education  

- `ideology7`: Self-placement on a 7-point liberal–conservative scale  
  - 1 = Extremely liberal  
  - 7 = Extremely conservative  

## Files and Folders in This Repository

- `.github/`  
  - GitHub configuration files (e.g., workflow or settings).  
- `data/`  
  - `anes_timeseries_2020_stata_20220210.dta` – ANES 2020 data file in Stata format.
- `presentation/`  
  - Slides for the project presentation.
- `written-report.qmd`  
  - Quarto source file for the written report.
- `written-report.pdf`  
  - Compiled PDF of the written report.
- `research-topic.qmd`  
  - Initial research topic proposal (Quarto).
- `research-topic.pdf`  
  - PDF version of the research topic proposal.
- `Final_Project.Rproj`  
  - RStudio project file for this repo.
- `.gitignore`  
  - Git ignore rules for files that should not be tracked.
- `.Rhistory`  
  - R command history (automatically generated).
- `README.md`  
  - This file, with project description and data dictionary.
