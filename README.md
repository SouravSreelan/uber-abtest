# Uber Eats Subscription A/B Test Simulator

## Overview
This project simulates and analyzes an A/B test to evaluate the impact of a new Uber Eats subscription feature on user conversion. It generates synthetic user data, performs a statistical hypothesis test (z-test), and visualizes the outcome.

## Objective     
Determine whether offering a subscription feature increases user conversion rates by running a simulated A/B test and assessing statistical significance.

## Features. 
- Simulates 2,000 users split into control and treatment groups
- Assigns different conversion probabilities (10% for control, 13% for treatment)
- Computes conversion rates
- Conducts a z-test for difference in proportions
- Visualizes results using matplotlib

## Methodology. 
1. **Data Simulation**:
   - 2,000 users randomly assigned to control/treatment groups
   - Binary conversion outcome simulated using binomial distribution

2. **Statistical Test**:
   - Pooled proportion calculated
   - Z-score and p-value computed to test for statistical significance

3. **Visualization**:
   - Bar chart showing conversion rate per group

## Sample Output
```
Conversion Rates:
control      0.100
Treatment    0.130
Z-Score: 2.0851, P-Value: 0.0185

```
> A p-value of 0.0185 indicates the treatment effect is statistically significant at a 5% level.

## 📂 Files
- `uber-abtest-simulator.ipynb`: Main notebook containing simulation, testing, and visualization

## 📚 Skills Demonstrated
- A/B Testing
- Hypothesis Testing (z-test)
- Data Simulation
- Python (pandas, numpy, scipy, matplotlib)
  

## 🚀 How to Run
1. Clone the repository
2. Open the notebook in Jupyter or Google Colab
3. Run all cells to simulate the test and view results

## 🔍 Real-World Use Case
Uber Eats may run A/B tests like this to determine the impact of a feature such as "Uber One" or personalized promos. This project demonstrates how to use statistical testing to evaluate such experiments.

---

