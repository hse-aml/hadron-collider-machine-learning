# Week3 programming assignment


## FILES at the release
training.csv - all features
check_agreement.csv - all features but mass for agreement check
check_correlation.csv - all features for correlation check
test.csv - all features but mass

## Goal

the goal is to design prediction model that will give best score (ROC AUC) and will meet the constraints of 

- similar performance on simulated and real data (agreement check)
- decorrelation with the mass (correlation check)

the preditions over `test.csv` (i.e. submission file) should be sent to coursera for evaluation.
