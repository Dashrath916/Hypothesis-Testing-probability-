# Hypothesis-Testing-probability

# Probability of Assembly Time Exceeding 30 Minutes

## Problem Statement
To find the probability that a randomly chosen assembly takes more than 30 minutes, you can use the standard normal distribution (Z-distribution) with the given mean and standard deviation. 

## Solution
1. **Calculate Z-Score**: Using the Z-score formula \( Z = \frac{(X - \mu)}{\sigma} \), where \( X = 30 \) minutes, \( \mu = 25 \) minutes, and \( \sigma = 4 \) minutes.
    - \( Z = \frac{30 - 25}{4} = \frac{5}{4} = 1.25 \)
2. **Find Probability**: Using a Z-table or calculator, find the probability associated with a Z-score of approximately 1.25.
    - The probability is found to be approximately 0.8944.
3. **Calculate Final Probability**:
    - Since the total area under the curve is 1, we subtract the cumulative probability from 1 to get the probability of the area beyond 1.25 standard deviations.
    - \( P(X > 30) = 1 - 0.8944 = 0.1056 \)

## Result
The probability that a randomly chosen assembly takes more than 30 minutes is approximately 0.1056, or 10.56%.



