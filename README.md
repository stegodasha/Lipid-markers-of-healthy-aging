# Lipid Markers of Healthy Aging Project

This repository contains the research project conducted for the Bioinformatics Institute.
The analysis is performed in the R programming language.

## Data Description
- **Samples:** 990 blood plasma samples of elderly people (aged from 89 to 104) were analyzed.
- **Lipid Classes:** The following lipid classes were measured in the samples:
  - Glycerophosphocholines (PC, LPC for lyso species)
  - Glycerophosphoethanolamines (PE, LPE for lyso species)
  - Glycerophosphoinositols (PI)
  - Diacylglycerolipids (DAG)
  - Triacylglycerolipids (TAG)
  - Ceramides (Cer)
  - Sphingomyelins (SM)
  - Cholesteryl esters (CE)
  - Acylcarnitines (CAR)

- **Scales:** Various scales were utilized in the analysis, including:
  - Mini Mental State Exam (mmse): reflects the patient's level of dementia.
  - Short Physical Performance Battery (sppb): reflects the patient's physical condition.
  - Barthel scale: shows how dependent the patient is on other people's help in daily life.
  - Frontal Assessment Battery (fab): also characterises the patient's level of dementia.
  - Charlson Comorbidity Index: based on the patient's previous illnesses, predicts survival rates.
  The higher the score on a particular scale, the worse the patient's condition.

## Project Objective
The aim of this project is to investigate the variation in the blood lipidome profiles of nonagenerians and identify potential lipid markers of healthy aging.

## Tasks
1. Identify blood lipid profiles of nonagenarians associated with cognitive state (mmse scale).
2. Cluster the data based on geriatric scales to identify individuals with optimal, average, and less optimal aging.
3. Identify blood lipid profiles associated with scale-defined aging successfulness.

## Notebooks Description
- `Exploratory_Data_Analysis.rmd`: The notebook contains exploratory analyses of the available data.
- `Analysing_the_data_according_to_the_mmse_scale.rmd`: The notebook contains analyses of patient groups according to the mmse scale.
- `Analysing_the_contribution_of_mmse_and_sppb_scales_to_changes_in_lipid_profile.rmd`: The notebook contains analyses of the contribution of physical (sppb scale) and cognitive (mmse scale) state of patients to differences in lipid profile.
- `Cluster_analysis.rmd`: The notebook contains clustering of samples according to scales and analysis of differences in lipid profile among clusters with different levels of successful ageing.

## Folder Structure
- `Notebooks`: contains R notebooks with data analysis
- `Converted_Reports`: Contains converted reports from R notebooks to PDF format.
- `Sample_Data`: Contains an example dataset for analysis.

## Results
1. Identified plasma lipid changes associated with dementia according to the mmse scale.
2. Identified plasma lipid changes in patients with successful and less successful ageing according to the results of clustering by mmse, fab, barthel, sppb and charlson scales.
3. Both analyses showed that most classes of lipids are reduced in patients with less successful ageing. Polyunsaturated lipids and long-chain lipids are also reduced in these groups of patients.



