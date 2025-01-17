# Statistics with synthetic data

Jacob Johansson 2024

This notebook is intended to serve as a sandbox for exploring and understanding statistical concepts through the use of customizable synthetic data.

## Usage

The data and examples in this notebook have been designed to represent "best-case" scenarios where statistical analysis assumptions are valid, and results are expected to be statistically significant. By providing a collection of standard tests on synthetic data, the notebook offers a controlled environment to explore various aspects of statistical analysis.


## Synthetic data of residential energy costs

The synthetic data represents the costs of energy consumption for residential houses. Yearly energy consumption cost, measured in euros, is modeled as a function of several explanatory variables, such as house area, heating system, and other factors relevant to specific examples and analyses below.

## Contents

1. One sample t-test and point estimate
2. Two-sample t-test with mean difference and confidence interval
3. Simple linear regression
4. Multiple linear regression
5. Interactions in multiple linear regression
6. One-way Anova 
7. Two-way Anova

## Ideas for experiments

**1. Model predictions**

Synthetic data provides full control over the true effects of explanatory variables, enabling experiments on how predicted effects compare to assumed (true) effects. Specifically, you can study:

- Effect size of the focal variable: How strongly does the true effect influence p-values and confidence intervals?
- Random effects in the data: What is the impact of increased variability or noise?
- Effects of other explanatory variables: How do multicollinearity or interaction terms affect predictions?
- Sample size: Larger samples generally reduce uncertainty but may not always lead to better predictions in overparameterized models.

**2. Validity of statistical tests**

Statistical tests rely on several assumptions to yield valid results. Exploring scenarios where these assumptions are violated helps deepen understanding of their importance. Or, as Leo Tolstoy eloquently put it in Anna Karenina (1877):

"All happy families are alike; each unhappy family is unhappy in its own way."

Ways to experiment with invalidating statistical tests:

- Reducing sample size: Small sample sizes lead to reduced statistical power, increasing the likelihood of Type II errors.
- Reducing the effects of explanatory variables: Smaller effects result in weaker relationships, making it harder to detect significance.
- Generating data from non-normal distributions: Many tests assume normality; deviations can compromise validity.

**3. Comparing statistical approaches**

By applying different statistical methods to the same dataset, you can explore their scope, similarities, and differences. For instance, a single dataset with grouped data can be subjected to different treatments can be analyzed using:
- T-tests: For pairwise group comparisons.
- ANOVA: For assessing variance across groups.
- Linear regression: For modeling group effects as predictors.

Experiments include:

- Comparing result tables to identify consistent or divergent findings across methods.
- Investigating how sample size, effect size, or data distribution affects the conclusions drawn by different approaches.

 
