# ENVX1002 Comprehensive General Quiz - ANSWER KEY

---

## **PART 1: MIXED MODULES (Questions 1-20)**

**Q1** - Which of the following best describes the Central Limit Theorem?
- A) Population data are always normally distributed
- B) Sample means approach a normal distribution as sample size increases ✓ **CORRECT**
- C) All samples from a population have the same mean
- D) Standard deviation equals standard error

**Explanation:** The CLT is fundamental to statistics. Regardless of the original population distribution, the distribution of sample means becomes approximately normal as n increases. This allows us to use normal-based inference for large samples.

---

**Q2** - When calculating a 95% confidence interval for a population mean with unknown standard deviation and n=15, which distribution do you use?
- A) Standard normal (z) distribution
- B) Student's t-distribution ✓ **CORRECT**
- C) Chi-squared distribution
- D) F-distribution

**Explanation:** When σ is unknown (the typical case), we use the sample standard deviation s and the t-distribution. Z-tests are rarely used in practice. With n=15, df = 14.

---

**Q3** - In a scatter plot, you observe that as x increases, y tends to decrease with moderate spread around the trend. Which correlation coefficient best fits?
- A) r = -0.72 ✓ **CORRECT**
- B) r = 0.72
- C) r = 0.05
- D) r = -0.15

**Explanation:** Negative correlation (negative sign), moderate strength (|r| in 0.7-1 range). r = -0.72 shows strong negative relationship with some scatter.

---

**Q4** - The median is preferred over the mean when:
- A) The data contains extreme outliers ✓ **CORRECT**
- B) The data is normally distributed
- C) You want to maximize the standard error
- D) The sample size is very large

**Explanation:** The median is robust to outliers. It's the middle value, so one extreme value doesn't pull it. The mean gets pulled toward outliers, making it less representative.

---

**Q5** - In a chi-squared goodness-of-fit test, what does a small p-value indicate?
- A) Observed frequencies match expected frequencies
- B) The sample size is too large
- C) Observed frequencies differ significantly from expected frequencies ✓ **CORRECT**
- D) Chi-squared statistic equals degrees of freedom

**Explanation:** Small p-value (p < α) → reject null hypothesis → observed frequencies significantly differ from expected. Large p-value → observed matches expected.

---

**Q6** - Which of the following is NOT a visual data representation discussed in Module 1?
- A) Histogram
- B) Box plot
- C) Scatter plot with regression line
- D) Pie chart with error bars ✓ **CORRECT**

**Explanation:** The handbook covers histograms, box plots, and scatter plots. Pie charts with error bars is not a standard visualization discussed (and is generally not recommended for statistical data).

---

**Q7** - A simple linear regression gives: ŷ = 12 - 0.5x with R² = 0.64. Which interpretation is correct?
- A) The model explains 64% of variance; for each unit increase in x, y decreases 0.5 units ✓ **CORRECT**
- B) The correlation is 0.5
- C) The intercept is 0.5
- D) The model perfectly predicts y

**Explanation:** R² = 0.64 means 64% of variance explained. Slope = -0.5, so y decreases 0.5 units per unit x. The intercept is 12. √0.64 ≈ 0.8 would be the correlation.

---

**Q8** - Standard error of the mean (SE) is related to standard deviation (SD) by:
- A) SE = SD
- B) SE = SD / √n ✓ **CORRECT**
- C) SE = SD × n
- D) SE = √(SD²)

**Explanation:** SE = σ/√n. Larger sample sizes produce smaller standard errors. Standard deviation (SD) measures spread of individual observations; SE measures precision of the sample mean.

---

**Q9** - What is the key difference between paired and independent samples t-tests?
- A) Paired tests use smaller samples
- B) Paired tests compare differences within pairs; independent tests compare between groups ✓ **CORRECT**
- C) Independent tests are always more powerful
- D) There is no real difference

**Explanation:** Paired tests analyze differences within matched pairs (e.g., before/after). Independent tests compare separate groups. The pairing reduces variability from between-pair differences.

---

**Q10** - In a residual plot, a "fan" or "cone" shape indicates violation of which assumption?
- A) Normality
- B) Linearity
- C) Equal variance ✓ **CORRECT**
- D) Independence

**Explanation:** A fan/cone shape shows heteroscedasticity (unequal variance). Spread of residuals increases (or decreases) with fitted values. This violates the equal variance assumption.

---

**Q11** - You collect data on plant height over time from the same plot repeatedly. This violates which regression assumption?
- A) Linearity
- B) Normality
- C) Independence ✓ **CORRECT**
- D) Equal variance

**Explanation:** Sequential measurements from the same unit are autocorrelated (not independent). Independence is hard to test but assumed based on study design. Time-series data violates this.

---

**Q12** - The Interquartile Range (IQR) represents:
- A) The spread from minimum to maximum value
- B) The range containing the middle 50% of data ✓ **CORRECT**
- C) The distance from Q1 to the mean
- D) The standard deviation

**Explanation:** IQR = Q3 - Q1 (75th percentile - 25th percentile). It captures the middle 50% of data and is robust to extreme values.

---

**Q13** - When using a log transformation, log(y) = 2.5 + 0.1x, a one-unit increase in x causes approximately what percent change in y?
- A) 2.5%
- B) 0.1%
- C) 10% ✓ **CORRECT**
- D) 100%

**Explanation:** For small β₁, percent change ≈ 100 × β₁ = 100 × 0.1 = 10%. More precisely: 100(e^0.1 - 1) ≈ 10.5%.

---

**Q14** - In ggplot2's grammar of graphics, which component maps variables to visual properties?
- A) geom_point()
- B) aes() ✓ **CORRECT**
- C) facet_wrap()
- D) theme()

**Explanation:** aes() specifies aesthetics (x, y, color, size, etc.). geom_* specifies plot type. facet_* creates subplots. theme() controls appearance.

---

**Q15** - Satterthwaite's t-test is used when:
- A) Sample sizes are equal
- B) Variances are homogeneous
- C) Variances are unequal but data is approximately normal ✓ **CORRECT**
- D) Data is paired

**Explanation:** Satterthwaite's test adjusts for unequal variances in independent samples t-test. It modifies the SED and degrees of freedom formulas.

---

**Q16** - A researcher finds r = 0 between study hours and test anxiety. What can they conclude?
- A) There is no relationship at all
- B) There is no linear relationship, but could be non-linear ✓ **CORRECT (best)**
- C) Study hours don't cause test anxiety
- D) Both B and C ✓ **ALSO CORRECT**

**Explanation:** r = 0 means no linear relationship, but a U-shaped or other non-linear relationship could exist. And correlation ≠ causation always. D captures both correct points.

---

**Q17** - Which metric is best for comparing regression models with different numbers of predictors?
- A) R²
- B) Adjusted R² ✓ **CORRECT**
- C) Correlation coefficient
- D) Residual standard error

**Explanation:** Adjusted R² penalizes for additional predictors. Regular R² always increases with more variables. AIC/BIC also work. RSE can be compared but adjusted R² is standard.

---

**Q18** - For a contingency table with 4 rows and 3 columns, degrees of freedom for the chi-squared test equals:
- A) 3
- B) 4
- C) 6 ✓ **CORRECT**
- D) 7

**Explanation:** df = (rows-1) × (columns-1) = (4-1) × (3-1) = 3 × 2 = 6.

---

**Q19** - Skewness and kurtosis values close to zero suggest:
- A) The data is exponentially distributed
- B) The data is approximately normally distributed ✓ **CORRECT**
- C) The data has outliers
- D) The sample size is adequate

**Explanation:** For normal distribution, skewness ≈ 0 and kurtosis ≈ 0. Positive skewness indicates right tail. Negative skewness indicates left tail.

---

**Q20** - In a two-sample t-test, the pooled variance estimate is used when:
- A) Variances are unequal
- B) Sample sizes are different
- C) Variances are assumed equal ✓ **CORRECT**
- D) Data is paired

**Explanation:** The pooled variance s²ₚ combines information from both samples. It's used when assuming equal variances (homogeneity). If unequal, use Satterthwaite's test instead.

---

## **PART 2: MODULE 1 FOCUSED (Questions 21-35)**

**Q21** - Which R function would you use to calculate the variance of a dataset with missing values?
- A) `var(data)`
- B) `var(data, na.rm = TRUE)` ✓ **CORRECT**
- C) `variance(data)`
- D) `sd(data)² / n`

**Explanation:** The na.rm = TRUE argument tells R to ignore NA values. Without it, var() returns NA if any values are missing.

---

**Q22** - The mode is most useful for describing which type of data?
- A) Continuous numerical data
- B) Categorical or count data ✓ **CORRECT**
- C) Highly skewed distributions
- D) Normal distributions

**Explanation:** Mode is the most frequent value. It's useful for discrete/categorical data. For continuous data, mode is less meaningful.

---

**Q23** - If sample size increases from n=10 to n=100, standard error will:
- A) Increase by 10 times
- B) Decrease by a factor of √10 ✓ **CORRECT**
- C) Stay the same
- D) Decrease by 10 times

**Explanation:** SE = σ/√n. If n increases by 10-fold (10→100), SE decreases by √10 ≈ 3.16-fold. SE is inversely proportional to √n.

---

**Q24** - A histogram with a long tail to the right indicates:
- A) Negative skewness
- B) Positive (right) skewness ✓ **CORRECT**
- C) Perfect normality
- D) Bimodal distribution

**Explanation:** Right tail = positive (right) skewness. Left tail = negative (left) skewness. Long tails are pulled toward the direction of skew.

---

**Q25** - In the Central Limit Theorem, as sample size increases, the sampling distribution:
- A) Becomes more spread out
- B) Becomes more normal and concentrated ✓ **CORRECT**
- C) Becomes bimodal
- D) Depends on the original population shape

**Explanation:** Sampling distribution of sample means becomes more normal (approaching normal) and more concentrated (smaller SE) as n increases.

---

**Q26** - The correlation between X and Y is 0.82. Approximately what percentage of variance in Y is explained by X?
- A) 82%
- B) 67% ✓ **CORRECT**
- C) 41%
- D) 18%

**Explanation:** R² = r² = (0.82)² = 0.6724 ≈ 67%. Correlation squared gives the proportion of variance explained.

---

**Q27** - ggplot2 builds plots in layers. Which is the correct order?
- A) geom → aes → data → labs
- B) data → aes → geom → labs ✓ **CORRECT**
- C) aes → data → geom → labs
- D) labs → data → aes → geom

**Explanation:** Start with data, map with aes(), add geometry, then labels/themes. ggplot(data, aes()) + geom_*() + labs().

---

**Q28** - Which summary statistic is LEAST affected by extreme outliers?
- A) Mean
- B) Standard deviation
- C) Median ✓ **CORRECT**
- D) Range

**Explanation:** Median is the middle value; one outlier can't pull it. Mean gets pulled toward outliers. Range and SD are affected. IQR is also robust.

---

**Q29** - For a dataset with mean=50, SD=10, approximately what percentage falls within one standard deviation (40-60)?
- A) 50%
- B) 68% ✓ **CORRECT**
- C) 95%
- D) 99.7%

**Explanation:** The empirical rule: ~68% within 1 SD, ~95% within 2 SD, ~99.7% within 3 SD (for normal distributions).

---

**Q30** - The standard error of the mean represents:
- A) How spread out individual observations are
- B) The precision of the sample mean ✓ **CORRECT**
- C) How many outliers the data contains
- D) The confidence level

**Explanation:** SE tells us how precise our estimate is. It's the standard deviation of the sampling distribution. Smaller SE = more precise estimate.

---

**Q31** - Q1 (first quartile) represents which percentile?
- A) 25th percentile ✓ **CORRECT**
- B) 50th percentile
- C) 75th percentile
- D) 100th percentile

**Explanation:** Q1 = 25th percentile (25% below, 75% above). Q2 (median) = 50th. Q3 = 75th. Q4 = 100th.

---

**Q32** - A box plot shows the median as a line close to one edge of the box. This indicates:
- A) Symmetrical distribution
- B) Skewed distribution ✓ **CORRECT**
- C) Perfect normality
- D) Uniform distribution

**Explanation:** If median line is off-center in the box, data is skewed. If median is toward lower edge, data is right-skewed (long tail right).

---

**Q33** - If data follows a lognormal distribution, which transformation would most likely normalize it?
- A) Square root
- B) Logarithmic ✓ **CORRECT**
- C) Inverse
- D) Arcsine

**Explanation:** Lognormal means log(y) is normal. Taking log of lognormal data makes it normal. This is the defining property of lognormal distributions.

---

**Q34** - The coefficient of variation (CV) is useful because it:
- A) Is in the same units as the original data
- B) Allows comparison of variability across datasets with different scales ✓ **CORRECT**
- C) Always equals the mean
- D) Indicates causation

**Explanation:** CV = SD/mean (unitless). Allows comparison of relative variability between datasets with different scales/units.

---

**Q35** - In a scatter plot matrix, what pattern between two variables would suggest a moderate negative relationship?
- A) Vertical scatter
- B) No visible pattern
- C) Downward trend with moderate scatter ✓ **CORRECT**
- D) Perfect diagonal line

**Explanation:** Downward trend = negative relationship. Moderate scatter = moderate strength (not r = -1). Tight cluster = strong; loose = weak.

---

## **PART 3: MODULE 2 FOCUSED (Questions 36-55)**

**Q36** - For a one-sample t-test, degrees of freedom equals:
- A) n
- B) n - 1 ✓ **CORRECT**
- C) n - 2
- D) n / 2

**Explanation:** df = n - 1. One constraint is that the sum of deviations equals zero, so only n-1 values are free to vary.

---

**Q37** - A 99% confidence interval will be:
- A) Wider than a 95% interval ✓ **CORRECT**
- B) Narrower than a 95% interval
- C) The same width as a 95% interval
- D) Centered on the median

**Explanation:** Higher confidence level = wider interval (t-value is larger). 99% CI uses a larger critical value than 95%.

---

**Q38** - The null hypothesis for a one-sample t-test is:
- A) H₀: μ ≠ c
- B) H₀: μ = c ✓ **CORRECT**
- C) H₀: x̄ = μ
- D) H₀: s ≠ σ

**Explanation:** We test if population mean μ equals some value c. The null assumes equality. The alternative is typically μ ≠ c (two-tailed).

---

**Q39** - When p-value = 0.03 and α = 0.05, you should:
- A) Fail to reject the null hypothesis
- B) Reject the null hypothesis ✓ **CORRECT**
- C) Increase the sample size
- D) Cannot determine without more information

**Explanation:** p < α → reject H₀. p = 0.03 < 0.05, so reject the null hypothesis.

---

**Q40** - Type I error occurs when:
- A) You fail to reject a false null hypothesis
- B) You reject a true null hypothesis ✓ **CORRECT**
- C) Your sample is too small
- D) Your data is not normally distributed

**Explanation:** Type I = false positive (α level). Type II = false negative (β level). We control Type I by choosing α.

---

**Q41** - In an F-test for equality of variances, what does F_observed > F_critical indicate?
- A) Variances are equal
- B) Variances are unequal; reject equal variance assumption ✓ **CORRECT**
- C) Sample sizes are unequal
- D) Data is normally distributed

**Explanation:** Large F-statistic (F_obs > F_crit) means variances differ significantly. Reject equal variance assumption. Use Satterthwaite's test instead.

---

**Q42** - A paired t-test compares:
- A) Means of two independent groups
- B) Means before and after treatment on same subjects ✓ **CORRECT**
- C) More than two groups
- D) Categorical variables

**Explanation:** Paired data: same subjects measured twice (before/after), matched pairs, or repeated measures. Compare differences within pairs.

---

**Q43** - For a paired t-test with n=12 pairs, degrees of freedom equals:
- A) 11 ✓ **CORRECT**
- B) 12
- C) 23
- D) 24

**Explanation:** For paired t-test, df = n_pairs - 1 = 12 - 1 = 11. You calculate differences (12 differences), so df = 11.

---

**Q44** - The assumptions for independent samples t-test include all EXCEPT:
- A) Continuous data
- B) Approximate normality
- C) Homogeneous (equal) variances
- D) The samples must be related/paired ✓ **CORRECT**

**Explanation:** Independent samples t-test requires samples to be INDEPENDENT, not related. If related, use paired t-test. A, B, C are actual assumptions.

---

**Q45** - In chi-squared test, if expected frequency < 5 in a cell, you should:
- A) Remove the cell
- B) Combine categories or acknowledge limitation ✓ **CORRECT**
- C) Always proceed with the test
- D) Increase sample size immediately

**Explanation:** Small expected frequencies violate assumptions. Combine categories to increase expected frequency, or report limitation. Chi-squared approximation is unreliable with low expected values.

---

**Q46** - A 2×3 contingency table chi-squared test has degrees of freedom equal to:
- A) 2
- B) 3
- C) 6
- D) 5 ✓ **CORRECT**

**Explanation:** df = (rows-1) × (columns-1) = (2-1) × (3-1) = 1 × 2 = 2. Wait, that's 2, not 5. Let me recalculate: (2-1)(3-1) = 1×2 = 2. **Actually, the correct answer should be A) 2.** The question has an error; D should not be marked correct.

**[CORRECTION: Q46 answer is A) 2, not D) 5. The error is in the question construction.]**

---

**Q47** - For the chi-squared calculation, you need:
- A) Only observed frequencies
- B) Only expected frequencies
- C) Both observed and expected frequencies ✓ **CORRECT**
- D) Correlation coefficients

**Explanation:** χ² = Σ[(Observed - Expected)² / Expected]. You need both to calculate the test statistic.

---

**Q48** - Power of a test refers to:
- A) The probability of Type I error
- B) The probability of rejecting H₀ when it's false ✓ **CORRECT**
- C) The sample size
- D) The significance level

**Explanation:** Power = 1 - β (sensitivity). It's the probability of correctly rejecting a false null hypothesis. Larger samples increase power.

---

**Q49** - When comparing two independent samples, the Standard Error of the Difference (SED) depends on:
- A) Both sample variances and sizes ✓ **CORRECT**
- B) Only the larger sample size
- C) Only the smaller variance
- D) The means of both samples

**Explanation:** SED depends on both variances and both sample sizes. For equal variances: SED = √[s²ₚ(1/n₁ + 1/n₂)].

---

**Q50** - If you cannot assume normality in your data, which test is NOT appropriate?
- A) Mann-Whitney U test (non-parametric alternative)
- B) Wilcoxon signed-rank test (non-parametric alternative)
- C) Parametric t-test on raw data ✓ **CORRECT**
- D) Either A or B

**Explanation:** Parametric t-tests assume normality. If violated, use non-parametric alternatives (Mann-Whitney U, Wilcoxon). Or transform data then test.

---

**Q51** - A confidence interval that does NOT contain the hypothesized parameter value suggests:
- A) The parameter doesn't exist
- B) The hypothesis should be rejected at that confidence level ✓ **CORRECT**
- C) The sample size was too large
- D) You made a calculation error

**Explanation:** If the hypothesized value lies outside the CI, it's not a plausible value at that confidence level. Reject the hypothesis.

---

**Q52** - The interpretation "95% CI" means:
- A) 95% of data falls within the interval
- B) There's a 95% probability the true parameter is in this interval
- C) If experiments were repeated, ~95% of intervals would contain the true parameter ✓ **CORRECT**
- D) The parameter is definitely in this interval

**Explanation:** Correct interpretation is C (frequentist). The parameter is fixed; the interval is random. Repeated experiments produce intervals ~95% of which contain the parameter.

---

**Q53** - Transforming data to meet test assumptions:
- A) Should always be done regardless of need
- B) Should be done only if needed to meet assumptions ✓ **CORRECT**
- C) Makes the results invalid
- D) Eliminates the need to check assumptions

**Explanation:** Transform data only if needed. Unnecessary transformation complicates interpretation. Always check assumptions before and after transformation.

---

**Q54** - When should you use a one-tailed vs two-tailed test?
- A) Always use two-tailed (more conservative)
- B) Use one-tailed if you have directional predictions before seeing data ✓ **CORRECT**
- C) One-tailed always gives more power
- D) Two-tailed is always preferred

**Explanation:** One-tailed requires pre-specified direction (before data analysis). Two-tailed is default when direction is unknown. One-tailed has more power but higher Type I risk if direction is wrong.

---

**Q55** - For a chi-squared goodness-of-fit test with expected frequencies all equal, the expected frequency for each category is:
- A) n / k (where k = number of categories) ✓ **CORRECT**
- B) n × k
- C) n - k
- D) √(n / k)

**Explanation:** If equally likely categories, each expected frequency = n / k. For example, fair die: n = 600 rolls, k = 6 sides, expected per side = 100.

---

## **PART 4: MODULE 3 FOCUSED (Questions 56-75)**

**Q56** - Pearson's correlation coefficient requires data to be:
- A) Ranked
- B) Categorical
- C) Continuous and numerical ✓ **CORRECT**
- D) Normally distributed (always)

**Explanation:** Pearson's r works for continuous numerical variables. Data don't need to be normally distributed (though helps for inference). Use Spearman's for ranked data.

---

**Q57** - A correlation of r = -0.92 between two variables indicates:
- A) One variable causes the other to decrease
- B) A strong negative linear relationship ✓ **CORRECT**
- C) 92% of variance is explained
- D) No relationship exists

**Explanation:** |r| = 0.92 is strong (≥0.7). Negative sign means inverse relationship. R² = 0.85 (85% variance explained), not 92%.

---

**Q58** - Spearman's rank correlation should be used instead of Pearson's when:
- A) Sample size is small
- B) Data are monotonic but potentially non-linear ✓ **CORRECT**
- C) You want a more powerful test
- D) The relationship is definitely linear

**Explanation:** Spearman's rank correlation handles non-linear monotonic relationships. Ranks data first, then calculates Pearson's on ranks. Useful for non-linear but consistent trend.

---

**Q59** - In linear regression ŷ = β₀ + β₁x, the intercept β₀ represents:
- A) The slope of the line
- B) The predicted value when x = 0 ✓ **CORRECT**
- C) The correlation coefficient
- D) The standard error

**Explanation:** β₀ is the y-intercept (where line crosses y-axis). β₁ is the slope. When x = 0, ŷ = β₀ + β₁(0) = β₀.

---

**Q60** - Residuals in regression are:
- A) Predicted values
- B) Actual observed values
- C) Differences between observed and predicted values ✓ **CORRECT**
- D) The regression coefficients

**Explanation:** eᵢ = yᵢ - ŷᵢ. Residuals represent error/unexplained variation. The goal is to minimize the sum of squared residuals.

---

**Q61** - The "L" in LINE assumptions stands for:
- A) Linear ✓ **CORRECT**
- B) Large sample
- C) Lower outliers
- D) Likelihood

**Explanation:** LINE = Linearity, Independence, Normality, Equal variance. Linearity is the assumption of a linear relationship between x and y.

---

**Q62** - When checking the normality assumption for regression, you examine:
- A) The histogram of x values
- B) The Q-Q plot of residuals ✓ **CORRECT**
- C) The scatter plot of x vs y
- D) The histogram of y values

**Explanation:** Normality is about residuals, not raw data. Q-Q plot of residuals shows if they follow normal distribution. Points should fall on the diagonal line.

---

**Q63** - A curved pattern in the Residuals vs Fitted plot suggests:
- A) Normality assumption is violated
- B) Independence assumption is violated
- C) Linearity assumption is violated ✓ **CORRECT**
- D) Equal variance assumption is violated

**Explanation:** Curved residuals indicate systematic pattern; the linear model doesn't capture true relationship. Try polynomial or non-linear model, or transform data.

---

**Q64** - R² = 0.75 means:
- A) The correlation is 0.75
- B) 75% of variance in y is explained by the model ✓ **CORRECT**
- C) The slope is 0.75
- D) There are 75 data points

**Explanation:** R² is proportion of variance explained. R² = 0.75 → r = √0.75 ≈ 0.87 (for simple regression). Not the same as correlation.

---

**Q65** - In multiple regression, adjusted R² differs from regular R² by:
- A) Penalizing for additional predictors ✓ **CORRECT**
- B) Using a different formula entirely
- C) Only being valid for simple regression
- D) Nothing; they're identical

**Explanation:** Adjusted R² = 1 - (1-R²)(n-1)/(n-p-1). It adjusts for number of predictors (p), preventing inflation from unnecessary variables.

---

**Q66** - Collinearity in multiple regression means:
- A) Predictors are independent
- B) Two or more predictors are highly correlated ✓ **CORRECT**
- C) The outcome is binary
- D) Variances are unequal

**Explanation:** Collinearity (part of CLINE assumptions) occurs when predictors are correlated. It inflates standard errors, making coefficients hard to estimate precisely.

---

**Q67** - When using polynomial regression with poly(x, 3), which terms are included?
- A) Only x³
- B) x, x², x³ ✓ **CORRECT**
- C) x and x³ (not x²)
- D) Cannot determine without more information

**Explanation:** poly(x, 3) creates orthogonal polynomials up to degree 3: x, x², x³. This is equivalent to y ~ x + I(x²) + I(x³) but with orthogonalization.

---

**Q68** - Non-linear regression using nls() is necessary when:
- A) The model is linear in parameters
- B) Polynomial regression suffices
- C) The model is non-linear in parameters (e.g., exponential) ✓ **CORRECT**
- D) You want better predictions

**Explanation:** nls() is for truly non-linear models (exponential, logistic, asymptotic). lm() handles polynomial (which are linear in coefficients). nls() iteratively searches for parameter values.

---

**Q69** - For exponential growth model y = y₀e^(kx) with k > 0:
- A) y decreases as x increases
- B) y remains constant
- C) y increases exponentially ✓ **CORRECT**
- D) y increases linearly

**Explanation:** Positive k means y₀ × e^(kx) grows exponentially. For decay, use k < 0. For k = 0, y = y₀ (constant).

---

**Q70** - An asymptotic growth model levels off at a maximum. This maximum is represented by:
- A) The slope parameter
- B) The rate parameter
- C) The asymptote parameter ✓ **CORRECT**
- D) The y-intercept

**Explanation:** In SSasymp(x, Asym, R0, lrc), Asym is the asymptote (limit). R0 is starting value. lrc is log rate constant.

---

**Q71** - When should you NOT extrapolate beyond your data range?
- A) Never; extrapolation is always reasonable
- B) Always; it's never safe ✓ **BEST ANSWER** (C is also correct)
- C) Only if the model has low R²
- D) When the relationship may change outside observed range ✓ **ALSO CORRECT**

**Explanation:** Extrapolation is risky. Relationships can change, biological limits apply, you make assumptions without evidence. D is more nuanced answer.

---

**Q72** - Log transformation of the response variable linearizes which type of relationship?
- A) Quadratic
- B) Exponential ✓ **CORRECT**
- C) Asymptotic
- D) Logistic

**Explanation:** Exponential y = ae^(bx) linearizes to log(y) = log(a) + bx. Square root for quadratic. Log transform doesn't linearize asymptotic/logistic directly.

---

**Q73** - For the model log(y) = 1.5 + 0.05x, the approximate percent change in y per unit increase in x is:
- A) 1.5%
- B) 5% ✓ **CORRECT**
- C) 0.5%
- D) 15%

**Explanation:** Percent change ≈ 100 × β = 100 × 0.05 = 5% (when β is small). More precisely: 100(e^0.05 - 1) ≈ 5.1%.

---

**Q74** - Which is NOT a common reason to compare multiple regression models?
- A) Different numbers of predictors
- B) Different functional forms (linear vs polynomial)
- C) Different transformation strategies
- D) The intercept differs between models ✓ **CORRECT**

**Explanation:** A, B, C are reasons to compare models. D (different intercepts) is not a primary reason; you'd focus on fit and complexity.

---

**Q75** - The principle of parsimony suggests choosing:
- A) The model with the highest R²
- B) The most complex model
- C) The simplest model that adequately explains the data ✓ **CORRECT**
- D) The model with the most parameters

**Explanation:** Parsimony (Occam's Razor): simpler is better if adequate. Use adjusted R², AIC, or BIC to balance fit and complexity. Avoid overfitting.

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

## **PERFORMANCE ANALYSIS**

Use this table to identify your weak areas:

| Area | Questions | Review if Score < 80% |
|---|---|---|
| Central Limit Theorem | 1, 25 | Module 1 §3 |
| Confidence Intervals | 2, 37 | Module 2 §1 |
| Hypothesis Testing | 39-40, 48 | Module 2 §2 |
| T-tests (all types) | 2, 36, 38, 42-43 | Module 2 §1-2 |
| Chi-squared Tests | 5, 18, 45-47, 55 | Module 2 §3 |
| Summary Statistics | 4, 8, 12, 21-23, 28-32 | Module 1 §1-2 |
| Data Visualization | 6, 14, 27, 35 | Module 1 §2 |
| Correlation | 3, 16, 26, 56-58 | Module 3 §1 |
| Simple Regression | 7, 59-64, 71-72 | Module 3 §2 |
| Multiple Regression | 17, 65-66 | Module 3 §3 |
| Non-linear Modeling | 68-70, 73 | Module 3 §4-5 |
| Assumptions & Diagnostics | 10-11, 62-63 | Module 3 §2 |

---

## **NEXT STEPS**

✓ **If score 66-75 (Excellent):**
- You're ready for the exam!
- Do a final review of any topics you struggled with
- Practice writing out explanations

✓ **If score 52-65 (Good/Very Good):**
- Identify weak topic areas from the table above
- Review those sections in the handbook
- Retake the quiz after 2 days

✓ **If score 38-51 (Needs Improvement):**
- Significant gaps detected
- Focus on Module areas with lowest scores
- Review conceptual foundations
- Use the other practice quizzes (Module 3 extended, original MCQ)

✓ **If score <38 (Significant Gaps):**
- Don't panic! You have time to improve
- Start with Module 1 fundamentals
- Work through each module systematically
- Use all available practice materials

---

Great work completing the comprehensive quiz! You're well on your way to exam readiness.

