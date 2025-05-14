# STAT320 Final Project: Uncovering US Health Inequities Through Organ Transplant Data

Group Members: Grady Herbert, Robyn Valverde, Sriyash Singhania

## Project Description:

**Introduction**

Organ transplantation is a critical, life-saving medical procedure involving the replacement of a damaged organ with a healthy one from another individual. However, due to the scarcity and high cost of organs, the allocation process often results in disparities that disproportionately affect certain demographic groups. The disparities in organ transplants can happen across sex, racial, and socioeconomic groups, raising crucial questions about structural inequality in the healthcare system. The paper aims to uncover these systemic inequalities by investigating heart, liver, and kidney transplant data alongside corresponding disease burden data. By analyzing patterns across sex and race, the study seeks to determine whether the distribution of organ transplants aligns equitably with the burden of disease experienced by different groups.

**Project Goals**

1.      Study difference in heart, liver, and kidney organ allocation by sex and race

2.      Determine if heart, liver, and kidney organs are fairly distributed by sex and race given group disease burdens

**Dataset**

Age-adjusted mortality rates for cardiovascular, kidney, and liver diseases were sourced from the Centers for Disease Control and Prevention (CDC). These data range from the years 1997 to 2019 and are segmented by sex and race. Organ transplant recipient data were obtained from the Health Resources and Services Administration (HRSA). The dataset includes national-level statistics on recipients of heart, liver, and kidney transplants, categorized by sex and race. The HRSA dataset also includes detailed demographic subdivisions—such as age and payment method—and covers multiple organ types, including heart, liver, lung, kidney, kidney-pancreas, and pancreas. However, due to the rarity of organ transplantation procedures, small sample sizes and missing data are common in certain racial demographics. These limitations restrict the scope of this analysis to heart, liver, and kidney transplants, specifically focusing on recipients identified as White, Black, Hispanic, and Asian. One-way ANOVA tests were used to assess significant differences in organ transplants across sex and racial groups, followed by a Tukey HSD test to explore detailed differences among specific racial categories.

**Materials in "Code" Folder**

· The "Data_Wrangling" folder contains files used to explore the data.

      · The "DataWranglingRecipient.Rmd" file contains the data wrangling results for organ transplant recipients using HRSA data in a RMD file.

      · The "DataWranglingWaitlist.Rmd" file contains the data wrangling results for organ transplant candidates using HRSA data in a RMD file.

· The "Testing" folder contains files used to conduct formal testing on the data.

      · The "DataAnalysis.Rmd" file contains initial testing results on organ transplant recipients using HRSA data in a RMD file.

      · The "Diagnostics.Rmd" file contains initial testing results on disease burden using CDC data in a RMD file.

      · The "Disease_Burden_Analysis.pdf" file contains formal testing on organ transplant recipients and disease burdens using both HRSA and CDC data in a PDF file.

      · The "Disease_Burden_Analysis.qmd" file contains formal testing on organ transplant recipients and disease burdens using both HRSA and CDC data in a QMD file.

      · The "Disease_Burden_Analysis.rmarkdown" file contains formal testing on organ transplant recipients and disease burdens using both HRSA and CDC data in a R Markdown file.

**Materials in "Data_Raw" Folder**

· The "Disease_Mortality_Burden" folder contains excel files on disease burden sourced from the CDC.

      · The "Heart_Liver_Kidney_Disease_Death.xlsx" file contains the original disease burden data used in the analysis. It contains data from 1950 to 2019 on cardiovascular, liver, and kidney disease mortality rate segmented by sex and race.

· The "Organ_Transplant" folder contains files excel files on organ transplant recipients sourced from the HRSA.

      · The "Organ_Donation_and_Transplantation_Data.xlsx" file contains the original organ transplant recipient data used in the analysis. It contains data from 2019 to 2024 on heart, liver, and kidney organ transplant recipients segmented by sex and race.

      · The "OrganTransplantData.xlsx" file contains limited organ transplant recipient data used in data wrangling. It contains data from 2019 to 2024 on heart, liver, and kidney organ transplant recipients segmented by sex and race.


**Materials in "Report" Folder**

· The "Figures" folder contains the RDS files of the figures used in the summary and report. These figures are all of the code output from the "Disease_Burden_Analysis.qmd" file. File names denote if the output is a test result (ANOVA or Tukey), a graph of the data (Plot), or using HRSA (Transplant) or CDC (Mortality) data.

· The "Readings" folder contains the research articles and books used as background for the project. Many of these readings are cited in the final report, and attached as PDF files in the folder.

· The "Summary.pdf" file contains the three-page summary of our project in a PDF file.

· The "Summary.qmd" file contains the three-page summary of our project in a QMD file.

· The "Technical_Report.qmd" file contains the technical report of our project in a QMD file.

· The "Technical_Report.pdf" file contains the technical report of our project in a PDF file.

· The "Report.bib" file contains the formal citations of the readings referenced in the technical report in a BIB file.

· The "Final_Presentation.pdf" file contains the presentation of our project in a PDF file.

**Other GitHub Materials**

· The "STAT320_Final_Project.Rproj" file contains basic information to help the project files run in a Rproj file. (Note: This file is generally unnecessary to have.)



Due Date
May 12th, 2025

