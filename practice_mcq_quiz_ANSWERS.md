# ENVX1002 End of Semester Practice MCQ Quiz - ANSWER KEY

---

## **MODULE 1: INTRODUCTION TO STATISTICAL PROGRAMMING & DATA VISUALIZATION**

**Question 1.1** - Which function in R would you use to remove missing values (NA) when calculating the mean of a dataset?
- A) `mean(data, remove.na = TRUE)`
- B) `mean(data, na.rm = TRUE)` ✓ **CORRECT**
- C) `mean(data, ignore.na = TRUE)`
- D) `mean(data, skip.na = TRUE)`

**Question 1.2** - When comparing the mean and median of a dataset with one unusually large outlier, which statistic is more representative of the typical value?
- A) The mean, because it uses all values
- B) The median, because it's robust to extreme values ✓ **CORRECT**
- C) They are equally representative
- D) Neither can handle outliers effectively

**Explanation:** The median is robust to extreme values because it only depends on the middle value(s), whereas the mean is pulled toward the outlier.

**Question 1.3** - In the formula for standard deviation, why are the differences from the mean squared before averaging?
- A) To make calculations easier
- B) To make all values positive and emphasize larger deviations ✓ **CORRECT**
- C) To ensure the result is always greater than zero
- D) Because the original formula requires it

**Explanation:** Squaring makes negative differences positive (so they don't cancel out) and emphasizes larger deviations from the mean.

**Question 1.4** - What does the Interquartile Range (IQR) represent?
- A) The range between the minimum and maximum values
- B) The middle 50% of data values ✓ **CORRECT**
- C) The average distance from the mean
- D) The standard deviation squared

**Explanation:** IQR = Q3 - Q1, which contains the middle 50% of observations (between the 25th and 75th percentiles).

**Question 1.5** - In ggplot2, which of the following components is NOT part of the grammar of graphics?
- A) Data
- B) Aesthetics
- C) Geometries
- D) Statistical significance ✓ **CORRECT**

**Explanation:** The grammar of graphics includes data, aesthetics (aes), geometries (geom_*), and other layers like scales and themes. Statistical significance is not a built-in component.

**Question 1.6** - The Central Limit Theorem states that:
- A) All data distributions are normal
- B) Sample means form a distribution that approaches normality as sample size increases ✓ **CORRECT**
- C) The population mean equals the sample mean
- D) Larger samples always have smaller variance

**Explanation:** The CLT is fundamental: the sampling distribution of sample means approaches a normal distribution regardless of the original population distribution, especially as n increases.

**Question 1.7** - If you take samples of size n=5 vs n=30 from the same population, which will have less variability in the sample means?
- A) n=5
- B) n=30 ✓ **CORRECT**
- C) They will have equal variability
- D) It depends on the population distribution

**Explanation:** Standard error = σ/√n. Larger sample sizes produce smaller standard errors, so sample means vary less with larger samples.

---

## **MODULE 2: HYPOTHESIS TESTING & T-TESTS**

**Question 2.1** - For a 95% confidence interval with unknown population standard deviation, which critical value do you use?
- A) z-value from the standard normal distribution
- B) t-value from the t-distribution ✓ **CORRECT**
- C) F-value from the F-distribution
- D) χ² value from the chi-squared distribution

**Explanation:** When σ is unknown (the usual case), you estimate it with s and use the t-distribution. Z-tests are rarely used in practice.

**Question 2.2** - What do the degrees of freedom (df) represent in a t-test?
- A) The number of independent pieces of information in the data ✓ **CORRECT**
- B) The number of variables in the study
- C) The total number of observations
- D) The number of hypothesis tests performed

**Explanation:** df represents the number of values that are free to vary. For a one-sample t-test, df = n-1 because once you know the mean and n-1 values, the last value is determined.

**Question 2.3** - The Student's t-distribution differs from the standard normal distribution in that it:
- A) Is always symmetrical
- B) Has heavier tails, especially with small sample sizes ✓ **CORRECT**
- C) Cannot be used for small samples
- D) Approaches uniformity as df increases

**Explanation:** The t-distribution has heavier tails than the normal distribution, making it more conservative. As df increases, t approaches the normal distribution.

**Question 2.4** - Which of the following is NOT an assumption of the independent two-sample t-test?
- A) Data are continuous
- B) Data are approximately normally distributed
- C) Variances are homogeneous (equal)
- D) The two samples are dependent ✓ **CORRECT**

**Explanation:** Independent samples t-test requires that samples are INDEPENDENT, not dependent. If samples are dependent (paired), you use a paired t-test instead.

**Question 2.5** - When should you use Satterthwaite's approximate t-test instead of the standard two-sample t-test?
- A) When sample sizes are very large
- B) When the data is not normally distributed
- C) When variances are unequal but data is approximately normal ✓ **CORRECT**
- D) When you have paired samples

**Explanation:** Satterthwaite's test adjusts for unequal variances. It uses a modified formula for SED and corrects the degrees of freedom.

**Question 2.6** - What is the main difference between a paired t-test and an independent samples t-test?
- A) Paired tests use the t-distribution while independent tests use z
- B) Paired tests compare differences within pairs, independent tests compare between groups ✓ **CORRECT**
- C) Paired tests cannot handle missing data
- D) There is no functional difference

**Explanation:** Paired tests work with the difference scores within pairs (reducing to a one-sample problem), while independent tests compare means between two separate groups.

**Question 2.7** - In the context of the Chi-squared (χ²) test, what does "goodness of fit" test?
- A) Whether the model predicts perfectly
- B) Whether observed frequencies agree with expected frequencies under a hypothesis ✓ **CORRECT**
- C) Whether the sample size is adequate
- D) Whether assumptions are met

**Explanation:** Goodness of fit tests test the null hypothesis that observed data match expected frequencies based on a theoretical model.

**Question 2.8** - For a 2×2 contingency table chi-squared test, how many degrees of freedom do you have?
- A) 1 ✓ **CORRECT**
- B) 2
- C) 3
- D) (rows-1) × (columns-1) = 1

**Explanation:** df = (rows-1) × (columns-1) = (2-1) × (2-1) = 1. Options A and D are the same (both correct formulations).

**Question 2.9** - What is a key requirement for chi-squared tests of independence?
- A) No expected cell frequency should be less than 5 ✓ **CORRECT**
- B) All variables must be normally distributed
- C) The sample must be randomly stratified
- D) Cell frequencies must be exactly equal

**Explanation:** The chi-squared approximation is unreliable when expected frequencies are too small. The rule of thumb is no cell should have expected frequency < 5.

**Question 2.10** - When data are not normally distributed, what transformations might help meet test assumptions?
- A) Only logarithmic transformations work
- B) Only square root transformations work
- C) Logarithmic, square root, or arcsine transformations ✓ **CORRECT**
- D) No transformation can help; you must use non-parametric tests

**Explanation:** Multiple transformations can work depending on the data. Log, square root, and arcsine (for proportions) are common options. The handbook shows examples of testing which works best.

---

## **MODULE 3: CORRELATION, REGRESSION & MODELING**

**Question 3.1** - Pearson's correlation coefficient measures:
- A) Any monotonic relationship
- B) Linear relationships between two numerical variables ✓ **CORRECT**
- C) Causal relationships
- D) Rank-based associations only

**Explanation:** Pearson's r specifically measures linear relationships. For non-linear monotonic relationships, use Spearman's or Kendall's.

**Question 3.2** - What does a Pearson's r value of -0.85 indicate?
- A) A weak positive relationship
- B) A strong negative relationship ✓ **CORRECT**
- C) No relationship
- D) A perfect negative relationship

**Explanation:** |r| = 0.85 falls in the 0.7-1.0 range (strong). The negative sign indicates the relationship is inverse (as x increases, y decreases).

**Question 3.3** - Which correlation coefficient is most appropriate for non-linear but monotonic relationships?
- A) Pearson's r
- B) Spearman's rank correlation ✓ **CORRECT**
- C) Neither—you must use regression
- D) Biserial correlation

**Explanation:** Spearman's correlation ranks the data first, then calculates correlation on the ranks, making it suitable for monotonic but non-linear relationships.

**Question 3.4** - In simple linear regression, residuals are:
- A) Predicted values of y
- B) Differences between observed and predicted y values ✓ **CORRECT**
- C) The intercept of the regression line
- D) Measures of correlation strength

**Explanation:** Residuals εᵢ = yᵢ - ŷᵢ. They represent the error or deviation of observed values from the fitted line.

**Question 3.5** - The LINE assumptions for linear regression stand for:
- A) Linear, Independent, Normal, Equal variance ✓ **CORRECT**
- B) Large, Interval, Nested, Empirical
- C) Linear, Interval, Normal, Estimated
- D) Likelihood, Independence, Normality, Expectation

**Explanation:** LINE is a mnemonic for the four key assumptions: Linearity, Independence, Normality (of residuals), and Equal variance (homoscedasticity).

**Question 3.6** - What does R² represent in linear regression?
- A) The correlation coefficient
- B) The proportion of variance in y explained by x ✓ **CORRECT**
- C) The standard error of the regression
- D) The degrees of freedom

**Explanation:** R² = SSᵣₑ𝓰/SSₜₒₜ. It ranges from 0 to 1 and tells you what proportion of variation in the response is explained by the model.

**Question 3.7** - In a multiple linear regression model with more than one predictor, which R² value should you report?
- A) Multiple R-squared
- B) Adjusted R-squared ✓ **CORRECT**
- C) Either one
- D) The larger of the two

**Explanation:** Adjusted R² penalizes for adding more predictors. It's the appropriate metric for multiple regression because it prevents overfitting from artificially inflating R².

**Question 3.8** - What does the principle of parsimony suggest in model selection?
- A) Always include all possible variables
- B) Use the simplest model that adequately explains the data ✓ **CORRECT**
- C) Never remove variables once added
- D) Maximize R² at all costs

**Explanation:** Parsimony (Occam's Razor) favors simpler models. A model with 3 useful predictors is better than one with 10 predictors if they explain the same amount of variation.

**Question 3.9** - Polynomial regression of degree 2 would include which terms?
- A) Only x
- B) x and x² ✓ **CORRECT**
- C) x, x², and x³
- D) Only x²

**Explanation:** A quadratic (degree 2) polynomial includes up to x². Degree 3 would include x³, etc.

**Question 3.10** - When using log transformation on the response variable, to interpret the effect of a one-unit increase in x, you should:
- A) Exponentiate the coefficient and subtract 1, then multiply by 100% ✓ **CORRECT**
- B) Simply report the coefficient value
- C) Take the logarithm of the coefficient
- D) Square the coefficient

**Explanation:** For log(y) = β₀ + β₁x, a one-unit increase in x multiplies y by e^β₁. The percent change is 100×(e^β₁ - 1)%.

**Question 3.11** - Non-linear regression differs from polynomial regression in that:
- A) Non-linear regression cannot use least squares
- B) Polynomial regression uses the `lm()` function while non-linear uses `nls()` ✓ **CORRECT**
- C) Polynomial regression is always more accurate
- D) Non-linear regression requires transformed variables

**Explanation:** Polynomials can be fit with `lm()` because they're linear in the coefficients. True non-linear models (exponential, logistic) require `nls()` because there's no closed-form analytical solution.

**Question 3.12** - For exponential regression (y = y₀e^(kx)), which parameter represents the value of y when x=0?
- A) k
- B) y₀ ✓ **CORRECT**
- C) The slope
- D) The intercept

**Explanation:** When x=0, y = y₀e⁰ = y₀(1) = y₀. So y₀ is the initial value or y-intercept of the exponential curve.

**Question 3.13** - An asymptotic relationship is best described as:
- A) Linear with constant slope
- B) Polynomial with multiple turning points
- C) Increases rapidly then levels off at a limit ✓ **CORRECT**
- D) Decreases symmetrically

**Explanation:** Asymptotic curves approach a horizontal limit. They increase (or decrease) rapidly at first, then level off. Common in growth and saturation curves.

**Question 3.14** - Collinearity in multiple regression refers to:
- A) When residuals are not independent
- B) When two or more predictors are highly correlated ✓ **CORRECT**
- C) When the outcome variable is binary
- D) When variances are unequal

**Explanation:** Collinearity (part of CLINE assumptions) occurs when predictors are highly correlated with each other, making it hard to separate their individual effects.

**Question 3.15** - "Correlation does not imply causation" means:
- A) Correlations are never useful
- B) Two variables can be correlated without one causing the other ✓ **CORRECT**
- C) You should never report correlations
- D) Only experiments can show causation

**Explanation:** A third variable might cause both observed variables to correlate. Causation requires experimental design or strong theoretical reasoning, not just correlation.

---

## **BONUS CHALLENGE QUESTIONS**

**Bonus 1** - A researcher collects data on plant height and finds it follows a lognormal distribution. Should they use the raw data or transformed data for their one-sample t-test?
- A) Always use raw data
- B) Always use transformed data
- C) Use the transformed data to meet normality assumptions ✓ **CORRECT**
- D) Use raw data if sample size is large enough

**Explanation:** The t-test assumes normality of the data. If raw data is lognormal, a log transformation will make it approximately normal, meeting the assumption.

**Bonus 2** - When interpreting a partial regression coefficient in multiple regression, what must you remember?
- A) It represents the total effect of that predictor
- B) It's interpreted holding all other variables constant ✓ **CORRECT (Part 1)**
- C) It measures correlation, not causation
- D) Both B and C ✓ **CORRECT (Best Answer)**

**Explanation:** Partial regression coefficients show the effect of one predictor while controlling for (holding constant) all other predictors. And like all observational correlations, they don't prove causation without experimental design.

**Bonus 3** - If your linear regression assumptions are violated, which is NOT a reasonable next step?
- A) Transform the data
- B) Use a different model (e.g., non-linear)
- C) Increase your sample size
- D) Report results anyway since sample size is large ✓ **CORRECT**

**Explanation:** Violating assumptions makes your p-values and confidence intervals unreliable—increasing sample size doesn't fix this. Transform data, use a different model, or acknowledge limitations, but don't report as if assumptions are met.

---

## **SCORING GUIDE**

| Score | Performance |
|-------|-------------|
| 30-32 | Excellent - Ready for exam |
| 27-29 | Good - Review weak areas |
| 24-26 | Satisfactory - More review needed |
| 20-23 | Needs improvement - Focus on concepts |
| <20 | Significant gaps - Intensive review recommended |

---

## **KEY CONCEPTS BY MODULE**

### Module 1 Concepts to Master:
- Summary statistics and their interpretations
- Robustness of median vs mean
- Central Limit Theorem and sampling distributions
- Data visualization principles

### Module 2 Concepts to Master:
- Confidence intervals and hypothesis testing framework
- One-sample vs two-sample t-tests
- Paired vs independent samples
- Chi-squared tests and contingency tables
- Data transformations

### Module 3 Concepts to Master:
- Correlation types and appropriate use
- Linear regression assumptions (LINE)
- Model interpretation and diagnostics
- Simple vs multiple regression
- Polynomial and non-linear models
- When to use each modeling approach

---

Good luck with your exam preparation!
