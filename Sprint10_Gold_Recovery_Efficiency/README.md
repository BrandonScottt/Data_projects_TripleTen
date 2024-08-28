## Project Description

In this project, we aim to develop a model to predict the efficiency of gold recovery in mining operations. The data provided includes various stages of the gold recovery process, including raw feed, rougher concentrate, and final concentrate. The goal is to ensure accurate predictions by thoroughly preparing and analyzing the data before building the model.

## Data Sources

The data is stored in three files:

- `gold_recovery_train.csv` — Training dataset.
- `gold_recovery_test.csv` — Test dataset.
- `gold_recovery_full.csv` — Source dataset containing all features.

## Description of the data
- **`rougher.output.recovery`** - Output of the rougher
- **`rougher.output.tail_ag`** - Concentration of Silver
- **`rougher.output.tail_sol`** - Concentration of solution
- **`rougher.output.tail_au`** - Concentration of Gold
- **`rougher.input.floatbank11_xanthate`** - Floatation bank input
- **`secondary_cleaner.output.tail_sol`** - Secondary stage cleaner concentrate
- **`final.output.recovery`** - Final output
- **`rougher.calculation.au_pb_ratio`** - Gold to Lead ratio
- **`primary_cleaner.input.sulfate`** - Concentrate of sulphate
- **`primary_cleaner.input.depressant`** - Concentrate of depressant

## Answer these questions:
- Check that recovery is calculated correctly. Using the training set, calculate recovery for the rougher.output.recovery feature. Find the MAE between your calculations and the feature values. Provide findings.
- Analyze the features not available in the test set. What are these parameters? What is their type?
- Perform data preprocessing.
- Take note of how the concentrations of metals (Au, Ag, Pb) change depending on the purification stage.
- Compare the feed particle size distributions in the training set and in the test set. If the distributions vary significantly, the model evaluation will be incorrect.
- Consider the total concentrations of all substances at different stages: raw feed, rougher concentrate, and final concentrate. Do you notice any abnormal values in the total distribution? If you do, is it worth removing - - such values from both samples? Describe the findings and eliminate anomalies.
- Write a function to calculate the final sMAPE value.
- Train different models. Evaluate them using cross-validation. Pick the best model and test it using the test sample. Provide findings.
