# ENVX1002 Comprehensive General Quiz - All Modules

## Full Cumulative Practice Assessment

This comprehensive quiz covers all topics from Modules 1, 2, and 3. Use it as a final assessment before your exam.

---

## **PART 1: MIXED MODULES (Questions 1-20)**

**Q1** - Which of the following best describes the Central Limit Theorem?
- A) Population data are always normally distributed
- B) Sample means approach a normal distribution as sample size increases
- C) All samples from a population have the same mean
- D) Standard deviation equals standard error

**Q2** - When calculating a 95% confidence interval for a population mean with unknown standard deviation and n=15, which distribution do you use?
- A) Standard normal (z) distribution
- B) Student's t-distribution
- C) Chi-squared distribution
- D) F-distribution

**Q3** - In a scatter plot, you observe that as x increases, y tends to decrease with moderate spread around the trend. Which correlation coefficient best fits?
- A) r = -0.72
- B) r = 0.72
- C) r = 0.05
- D) r = -0.15

**Q4** - The median is preferred over the mean when:
- A) The data contains extreme outliers
- B) The data is normally distributed
- C) You want to maximize the standard error
- D) The sample size is very large

**Q5** - In a chi-squared goodness-of-fit test, what does a small p-value indicate?
- A) Observed frequencies match expected frequencies
- B) The sample size is too large
- C) Observed frequencies differ significantly from expected frequencies
- D) Chi-squared statistic equals degrees of freedom

**Q6** - Which of the following is NOT a visual data representation discussed in Module 1?
- A) Histogram
- B) Box plot
- C) Scatter plot with regression line
- D) Pie chart with error bars

**Q7** - A simple linear regression gives: ŷ = 12 - 0.5x with R² = 0.64. Which interpretation is correct?
- A) The model explains 64% of variance; for each unit increase in x, y decreases 0.5 units
- B) The correlation is 0.5
- C) The intercept is 0.5
- D) The model perfectly predicts y

**Q8** - Standard error of the mean (SE) is related to standard deviation (SD) by:
- A) SE = SD
- B) SE = SD / √n
- C) SE = SD × n
- D) SE = √(SD²)

**Q9** - What is the key difference between paired and independent samples t-tests?
- A) Paired tests use smaller samples
- B) Paired tests compare differences within pairs; independent tests compare between groups
- C) Independent tests are always more powerful
- D) There is no real difference

**Q10** - In a residual plot, a "fan" or "cone" shape indicates violation of which assumption?
- A) Normality
- B) Linearity
- C) Equal variance
- D) Independence

**Q11** - You collect data on plant height over time from the same plot repeatedly. This violates which regression assumption?
- A) Linearity
- B) Normality
- C) Independence
- D) Equal variance

**Q12** - The Interquartile Range (IQR) represents:
- A) The spread from minimum to maximum value
- B) The range containing the middle 50% of data
- C) The distance from Q1 to the mean
- D) The standard deviation

**Q13** - When using a log transformation, log(y) = 2.5 + 0.1x, a one-unit increase in x causes approximately what percent change in y?
- A) 2.5%
- B) 0.1%
- C) 10%
- D) 100%

**Q14** - In ggplot2's grammar of graphics, which component maps variables to visual properties?
- A) geom_point()
- B) aes()
- C) facet_wrap()
- D) theme()

**Q15** - Satterthwaite's t-test is used when:
- A) Sample sizes are equal
- B) Variances are homogeneous
- C) Variances are unequal but data is approximately normal
- D) Data is paired

**Q16** - A researcher finds r = 0 between study hours and test anxiety. What can they conclude?
- A) There is no relationship at all
- B) There is no linear relationship, but could be non-linear
- C) Study hours don't cause test anxiety
- D) Both B and C

**Q17** - Which metric is best for comparing regression models with different numbers of predictors?
- A) R²
- B) Adjusted R²
- C) Correlation coefficient
- D) Residual standard error

**Q18** - For a contingency table with 4 rows and 3 columns, degrees of freedom for the chi-squared test equals:
- A) 3
- B) 4
- C) 6
- D) 7

**Q19** - Skewness and kurtosis values close to zero suggest:
- A) The data is exponentially distributed
- B) The data is approximately normally distributed
- C) The data has outliers
- D) The sample size is adequate

**Q20** - In a two-sample t-test, the pooled variance estimate is used when:
- A) Variances are unequal
- B) Sample sizes are different
- C) Variances are assumed equal
- D) Data is paired

---

## **PART 2: MODULE 1 FOCUSED (Questions 21-35)**

**Q21** - Which R function would you use to calculate the variance of a dataset with missing values?
- A) `var(data)`
- B) `var(data, na.rm = TRUE)`
- C) `variance(data)`
- D) `sd(data)² / n`

**Q22** - The mode is most useful for describing which type of data?
- A) Continuous numerical data
- B) Categorical or count data
- C) Highly skewed distributions
- D) Normal distributions

**Q23** - If sample size increases from n=10 to n=100, standard error will:
- A) Increase by 10 times
- B) Decrease by a factor of √10
- C) Stay the same
- D) Decrease by 10 times

**Q24** - A histogram with a long tail to the right indicates:
- A) Negative skewness
- B) Positive (right) skewness
- C) Perfect normality
- D) Bimodal distribution

**Q25** - In the Central Limit Theorem, as sample size increases, the sampling distribution:
- A) Becomes more spread out
- B) Becomes more normal and concentrated
- C) Becomes bimodal
- D) Depends on the original population shape

**Q26** - The correlation between X and Y is 0.82. Approximately what percentage of variance in Y is explained by X?
- A) 82%
- B) 67%
- C) 41%
- D) 18%

**Q27** - ggplot2 builds plots in layers. Which is the correct order?
- A) geom → aes → data → labs
- B) data → aes → geom → labs
- C) aes → data → geom → labs
- D) labs → data → aes → geom

**Q28** - Which summary statistic is LEAST affected by extreme outliers?
- A) Mean
- B) Standard deviation
- C) Median
- D) Range

**Q29** - For a dataset with mean=50, SD=10, approximately what percentage falls within one standard deviation (40-60)?
- A) 50%
- B) 68%
- C) 95%
- D) 99.7%

**Q30** - The standard error of the mean represents:
- A) How spread out individual observations are
- B) The precision of the sample mean
- C) How many outliers the data contains
- D) The confidence level

**Q31** - Q1 (first quartile) represents which percentile?
- A) 25th percentile
- B) 50th percentile
- C) 75th percentile
- D) 100th percentile

**Q32** - A box plot shows the median as a line close to one edge of the box. This indicates:
- A) Symmetrical distribution
- B) Skewed distribution
- C) Perfect normality
- D) Uniform distribution

**Q33** - If data follows a lognormal distribution, which transformation would most likely normalize it?
- A) Square root
- B) Logarithmic
- C) Inverse
- D) Arcsine

**Q34** - The coefficient of variation (CV) is useful because it:
- A) Is in the same units as the original data
- B) Allows comparison of variability across datasets with different scales
- C) Always equals the mean
- D) Indicates causation

**Q35** - In a scatter plot matrix, what pattern between two variables would suggest a moderate negative relationship?
- A) Vertical scatter
- B) No visible pattern
- C) Downward trend with moderate scatter
- D) Perfect diagonal line

---

## **PART 3: MODULE 2 FOCUSED (Questions 36-55)**

**Q36** - For a one-sample t-test, degrees of freedom equals:
- A) n
- B) n - 1
- C) n - 2
- D) n / 2

**Q37** - A 99% confidence interval will be:
- A) Wider than a 95% interval
- B) Narrower than a 95% interval
- C) The same width as a 95% interval
- D) Centered on the median

**Q38** - The null hypothesis for a one-sample t-test is:
- A) H₀: μ ≠ c
- B) H₀: μ = c
- C) H₀: x̄ = μ
- D) H₀: s ≠ σ

**Q39** - When p-value = 0.03 and α = 0.05, you should:
- A) Fail to reject the null hypothesis
- B) Reject the null hypothesis
- C) Increase the sample size
- D) Cannot determine without more information

**Q40** - Type I error occurs when:
- A) You fail to reject a false null hypothesis
- B) You reject a true null hypothesis
- C) Your sample is too small
- D) Your data is not normally distributed

**Q41** - In an F-test for equality of variances, what does F_observed > F_critical indicate?
- A) Variances are equal
- B) Variances are unequal; reject equal variance assumption
- C) Sample sizes are unequal
- D) Data is normally distributed

**Q42** - A paired t-test compares:
- A) Means of two independent groups
- B) Means before and after treatment on same subjects
- C) More than two groups
- D) Categorical variables

**Q43** - For a paired t-test with n=12 pairs, degrees of freedom equals:
- A) 11
- B) 12
- C) 23
- D) 24

**Q44** - The assumptions for independent samples t-test include all EXCEPT:
- A) Continuous data
- B) Approximate normality
- C) Homogeneous (equal) variances
- D) The samples must be related/paired

**Q45** - In chi-squared test, if expected frequency < 5 in a cell, you should:
- A) Remove the cell
- B) Combine categories or acknowledge limitation
- C) Always proceed with the test
- D) Increase sample size immediately

**Q46** - A 2×3 contingency table chi-squared test has degrees of freedom equal to:
- A) 2
- B) 3
- C) 6
- D) 5

**Q47** - For the chi-squared calculation, you need:
- A) Only observed frequencies
- B) Only expected frequencies
- C) Both observed and expected frequencies
- D) Correlation coefficients

**Q48** - Power of a test refers to:
- A) The probability of Type I error
- B) The probability of rejecting H₀ when it's false
- C) The sample size
- D) The significance level

**Q49** - When comparing two independent samples, the Standard Error of the Difference (SED) depends on:
- A) Both sample variances and sizes
- B) Only the larger sample size
- C) Only the smaller variance
- D) The means of both samples

**Q50** - If you cannot assume normality in your data, which test is NOT appropriate?
- A) Mann-Whitney U test (non-parametric alternative)
- B) Wilcoxon signed-rank test (non-parametric alternative)
- C) Parametric t-test on raw data
- D) Either A or B

**Q51** - A confidence interval that does NOT contain the hypothesized parameter value suggests:
- A) The parameter doesn't exist
- B) The hypothesis should be rejected at that confidence level
- C) The sample size was too large
- D) You made a calculation error

**Q52** - The interpretation "95% CI" means:
- A) 95% of data falls within the interval
- B) There's a 95% probability the true parameter is in this interval
- C) If experiments were repeated, ~95% of intervals would contain the true parameter
- D) The parameter is definitely in this interval

**Q53** - Transforming data to meet test assumptions:
- A) Should always be done regardless of need
- B) Should be done only if needed to meet assumptions
- C) Makes the results invalid
- D) Eliminates the need to check assumptions

**Q54** - When should you use a one-tailed vs two-tailed test?
- A) Always use two-tailed (more conservative)
- B) Use one-tailed if you have directional predictions before seeing data
- C) One-tailed always gives more power
- D) Two-tailed is always preferred

**Q55** - For a chi-squared goodness-of-fit test with expected frequencies all equal, the expected frequency for each category is:
- A) n / k (where k = number of categories)
- B) n × k
- C) n - k
- D) √(n / k)

---

## **PART 4: MODULE 3 FOCUSED (Questions 56-75)**

**Q56** - Pearson's correlation coefficient requires data to be:
- A) Ranked
- B) Categorical
- C) Continuous and numerical
- D) Normally distributed (always)

**Q57** - A correlation of r = -0.92 between two variables indicates:
- A) One variable causes the other to decrease
- B) A strong negative linear relationship
- C) 92% of variance is explained
- D) No relationship exists

**Q58** - Spearman's rank correlation should be used instead of Pearson's when:
- A) Sample size is small
- B) Data are monotonic but potentially non-linear
- C) You want a more powerful test
- D) The relationship is definitely linear

**Q59** - In linear regression ŷ = β₀ + β₁x, the intercept β₀ represents:
- A) The slope of the line
- B) The predicted value when x = 0
- C) The correlation coefficient
- D) The standard error

**Q60** - Residuals in regression are:
- A) Predicted values
- B) Actual observed values
- C) Differences between observed and predicted values
- D) The regression coefficients

**Q61** - The "L" in LINE assumptions stands for:
- A) Linear
- B) Large sample
- C) Lower outliers
- D) Likelihood

**Q62** - When checking the normality assumption for regression, you examine:
- A) The histogram of x values
- B) The Q-Q plot of residuals
- C) The scatter plot of x vs y
- D) The histogram of y values

**Q63** - A curved pattern in the Residuals vs Fitted plot suggests:
- A) Normality assumption is violated
- B) Independence assumption is violated
- C) Linearity assumption is violated
- D) Equal variance assumption is violated

**Q64** - R² = 0.75 means:
- A) The correlation is 0.75
- B) 75% of variance in y is explained by the model
- C) The slope is 0.75
- D) There are 75 data points

**Q65** - In multiple regression, adjusted R² differs from regular R² by:
- A) Penalizing for additional predictors
- B) Using a different formula entirely
- C) Only being valid for simple regression
- D) Nothing; they're identical

**Q66** - Collinearity in multiple regression means:
- A) Predictors are independent
- B) Two or more predictors are highly correlated
- C) The outcome is binary
- D) Variances are unequal

**Q67** - When using polynomial regression with poly(x, 3), which terms are included?
- A) Only x³
- B) x, x², x³
- C) x and x³ (not x²)
- D) Cannot determine without more information

**Q68** - Non-linear regression using nls() is necessary when:
- A) The model is linear in parameters
- B) Polynomial regression suffices
- C) The model is non-linear in parameters (e.g., exponential)
- D) You want better predictions

**Q69** - For exponential growth model y = y₀e^(kx) with k > 0:
- A) y decreases as x increases
- B) y remains constant
- C) y increases exponentially
- D) y increases linearly

**Q70** - An asymptotic growth model levels off at a maximum. This maximum is represented by:
- A) The slope parameter
- B) The rate parameter
- C) The asymptote parameter
- D) The y-intercept

**Q71** - When should you NOT extrapolate beyond your data range?
- A) Never; extrapolation is always reasonable
- B) Always; it's never safe
- C) Only if the model has low R²
- D) When the relationship may change outside observed range

**Q72** - Log transformation of the response variable linearizes which type of relationship?
- A) Quadratic
- B) Exponential
- C) Asymptotic
- D) Logistic

**Q73** - For the model log(y) = 1.5 + 0.05x, the approximate percent change in y per unit increase in x is:
- A) 1.5%
- B) 5%
- C) 0.5%
- D) 15%

**Q74** - Which is NOT a common reason to compare multiple regression models?
- A) Different numbers of predictors
- B) Different functional forms (linear vs polynomial)
- C) Different transformation strategies
- D) The intercept differs between models

**Q75** - The principle of parsimony suggests choosing:
- A) The model with the highest R²
- B) The most complex model
- C) The simplest model that adequately explains the data
- D) The model with the most parameters

---

## **SCORING GUIDE**

| Score (out of 75) | Performance |
|---|---|
| 66-75 | Excellent - Ready for exam |
| 59-65 | Very Good - Strong performance |
| 52-58 | Good - Solid understanding |
| 45-51 | Satisfactory - Review weak areas |
| 38-44 | Needs Improvement - Significant review needed |
| <38 | Significant Gaps - Intensive study required |

---

## **TIPS FOR BEST RESULTS**

✓ **Before taking the quiz:**
- Review all three modules
- Have your notes handy but try without them first
- Time yourself (75 questions ≈ 90 minutes)

✓ **While taking the quiz:**
- Don't spend > 2 minutes per question
- Mark difficult questions to revisit
- Make your best guess; you can review later

✓ **After completing:**
- Compare to answer key
- Note which modules/topics you struggled with
- Review those specific sections in the handbook
- Retake the quiz after 1-2 days

---

## **BY TOPIC BREAKDOWN**

Use this to identify weak areas:

- **Questions by Module:**
  - Part 1 (Mixed): 1-20
  - Part 2 (Module 1): 21-35
  - Part 3 (Module 2): 36-55
  - Part 4 (Module 3): 56-75

- **Key Topic Areas:**
  - Summary Statistics: Q4, Q8, Q12, Q21, Q28-29, Q31-32
  - Data Visualization: Q6, Q14, Q27, Q35
  - Hypothesis Testing: Q2, Q36-39, Q41-45, Q49-55
  - Correlation: Q3, Q16, Q26, Q56-58
  - Linear Regression: Q7, Q59-67, Q71-72
  - Non-linear Modeling: Q68-70, Q73
  - Model Comparison: Q10-11, Q17, Q62-66, Q74-75

---

Good luck! This quiz will give you a comprehensive assessment of your ENVX1002 knowledge.

