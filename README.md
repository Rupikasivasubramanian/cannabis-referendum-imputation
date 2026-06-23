## Cannabis Referendum Imputation Analysis

Analysis of New Zealand's 2020 Cannabis Referendum survey data.

### What this project does
- Investigates what proportion of people supported legalisation
- Identifies who was more likely to vote yes based on age and gender
- Handles missing data using two approaches: complete cases and multiple imputation (mice package)

### Tools used
R Studio

### Key outputs
- Missingness summary table
- Age distribution by gender visualisation  
- Logistic regression on complete cases
- Logistic regression on imputed data
- Comparison of both analyses

### Data
Survey responses containing Age, Gender, and referendum vote (yes=1, no=0)
with considerable missingness, particularly among younger respondents.
