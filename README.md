# Titanic Fare Analysis using Central Limit Theorem

## Project Overview
The Titanic dataset contains fare values that are highly skewed and not normally distributed.
Since direct estimation of population mean may be misleading, this project applies the
Central Limit Theorem (CLT) to estimate the mean fare using sampling distributions.

## Objective
- Analyze the distribution of fare values
- Apply Central Limit Theorem using random sampling
- Estimate the population mean
- Demonstrate how sampling means approach normality

## Dataset
- train.csv
- test.csv
(Both datasets were combined after removing the target variable.)

## Methodology
1. Combined train and test datasets and shuffled data
2. Visualized fare distribution (non-normal)
3. Drew 100 random samples of size 50
4. Calculated sampling means
5. Visualized sampling distribution
6. Estimated mean 

## Key Results
- Original Fare Distribution: Right-skewed
- Sampling Mean Distribution: Approximately normal
- Estimated Mean Fare Range (95% CI):
  29.97 to 33.58

## Libraries Used
- Python
- Pandas
- NumPy
- Seaborn

## Key Learning
This project demonstrates how the Central Limit Theorem allows reliable
mean estimation even when the underlying data is not normally distributed.

## Author
Akash Kumar
