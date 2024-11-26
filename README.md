# Machine Learning Model building to predict Recurrence of Kidney Stone Disease

## Script directory
This repository details the scripts used to:

#### 1. Scripts to build dataset from UK Biobank derived data
  1. Process the dietary information in UK Biobank
  2. Process the Biochemistry data in UK Biobank
  3. Add genomic data (PRS and rare variants)
  4. Ascertain kidney stone formers in UK Biobank
  5. Ascertain Past medical history for kidney stone formers
  6. Merge datasets

The dataset building script 4 (ascertain kidney stone formers) currently derives a cohort of only those with either intervention or ureteric colic as 1st presentation (excluding generic diagnostic codes e.g. N20) - this can be adjusted as necessary to include these.

Recurrence is defined as intervention or ureteric colic >6 months after the previous episode. 
For 5 and 10 year recurrence rates, if an individual has not reached 5/10 years of follow-up and has not had a recurrence within that time they have been excluded from the cohort.

#### 2. Cleaning, Preprocessing, Model building and Validation scripts are:     
  7. Data cleaning
  8. Preprocessing
  9. Modelling
  10. Validation
