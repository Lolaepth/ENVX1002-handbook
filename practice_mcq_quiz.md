# ENVX1002 End of Semester Practice MCQ Quiz

---

## **MODULE 1: INTRODUCTION TO STATISTICAL PROGRAMMING & DATA VISUALIZATION**

**Question 1.1** - Which function in R would you use to remove missing values (NA) when calculating the mean of a dataset?
- A) `mean(data, remove.na = TRUE)`
- B) `mean(data, na.rm = TRUE)`
- C) `mean(data, ignore.na = TRUE)`
- D) `mean(data, skip.na = TRUE)`

**Question 1.2** - When comparing the mean and median of a dataset with one unusually large outlier, which statistic is more representative of the typical value?
- A) The mean, because it uses all values
- B) The median, because it's robust to extreme values
- C) They are equally representative
- D) Neither can handle outliers effectively

**Question 1.3** - In the formula for standard deviation, why are the differences from the mean squared before averaging?
- A) To make calculations easier
- B) To make all values positive and emphasize larger deviations
- C) To ensure the result is always greater than zero
- D) Because the original formula requires it

**Question 1.4** - What does the Interquartile Range (IQR) represent?
- A) The range between the minimum and maximum values
- B) The middle 50% of data values
- C) The average distance from the mean
- D) The standard deviation squared

**Question 1.5** - In ggplot2, which of the following components is NOT part of the grammar of graphics?
- A) Data
- B) Aesthetics
- C) Geometries
- D) Statistical significance

**Question 1.6** - The Central Limit Theorem states that:
- A) All data distributions are normal
- B) Sample means form a distribution that approaches normality as sample size increases
- C) The population mean equals the sample mean
- D) Larger samples always have smaller variance

**Question 1.7** - If you take samples of size n=5 vs n=30 from the same population, which will have less variability in the sample means?
- A) n=5
- B) n=30
- C) They will have equal variability
- D) It depends on the population distribution

---

## **MODULE 2: HYPOTHESIS TESTING & T-TESTS**

**Question 2.1** - For a 95% confidence interval with unknown population standard deviation, which critical value do you use?
- A) z-value from the standard normal distribution
- B) t-value from the t-distribution
- C) F-value from the F-distribution
- D) χ² value from the chi-squared distribution

**Question 2.2** - What do the degrees of freedom (df) represent in a t-test?
- A) The number of independent pieces of information in the data
- B) The number of variables in the study
- C) The total number of observations
- D) The number of hypothesis tests performed

**Question 2.3** - The Student's t-distribution differs from the standard normal distribution in that it:
- A) Is always symmetrical
- B) Has heavier tails, especially with small sample sizes
- C) Cannot be used for small samples
- D) Approaches uniformity as df increases

**Question 2.4** - Which of the following is NOT an assumption of the independent two-sample t-test?
- A) Data are continuous
- B) Data are approximately normally distributed
- C) Variances are homogeneous (equal)
- D) The two samples are dependent

**Question 2.5** - When should you use Satterthwaite's approximate t-test instead of the standard two-sample t-test?
- A) When sample sizes are very large
- B) When the data is not normally distributed
- C) When variances are unequal but data is approximately normal
- D) When you have paired samples

**Question 2.6** - What is the main difference between a paired t-test and an independent samples t-test?
- A) Paired tests use the t-distribution while independent tests use z
- B) Paired tests compare differences within pairs, independent tests compare between groups
- C) Paired tests cannot handle missing data
- D) There is no functional difference

**Question 2.7** - In the context of the Chi-squared (χ²) test, what does "goodness of fit" test?
- A) Whether the model predicts perfectly
- B) Whether observed frequencies agree with expected frequencies under a hypothesis
- C) Whether the sample size is adequate
- D) Whether assumptions are met

**Question 2.8** - For a 2×2 contingency table chi-squared test, how many degrees of freedom do you have?
- A) 1
- B) 2
- C) 3
- D) (rows-1) × (columns-1) = 1

**Question 2.9** - What is a key requirement for chi-squared tests of independence?
- A) No expected cell frequency should be less than 5
- B) All variables must be normally distributed
- C) The sample must be randomly stratified
- D) Cell frequencies must be exactly equal

**Question 2.10** - When data are not normally distributed, what transformations might help meet test assumptions?
- A) Only logarithmic transformations work
- B) Only square root transformations work
- C) Logarithmic, square root, or arcsine transformations
- D) No transformation can help; you must use non-parametric tests

---

## **MODULE 3: CORRELATION, REGRESSION & MODELING**

**Question 3.1** - Pearson's correlation coefficient measures:
- A) Any monotonic relationship
- B) Linear relationships between two numerical variables
- C) Causal relationships
- D) Rank-based associations only

**Question 3.2** - What does a Pearson's r value of -0.85 indicate?
- A) A weak positive relationship
- B) A strong negative relationship
- C) No relationship
- D) A perfect negative relationship

**Question 3.3** - Which correlation coefficient is most appropriate for non-linear but monotonic relationships?
- A) Pearson's r
- B) Spearman's rank correlation
- C) Neither—you must use regression
- D) Biserial correlation

**Question 3.4** - In simple linear regression, residuals are:
- A) Predicted values of y
- B) Differences between observed and predicted y values
- C) The intercept of the regression line
- D) Measures of correlation strength

**Question 3.5** - The LINE assumptions for linear regression stand for:
- A) Linear, Independent, Normal, Equal variance
- B) Large, Interval, Nested, Empirical
- C) Linear, Interval, Normal, Estimated
- D) Likelihood, Independence, Normality, Expectation

**Question 3.6** - What does R² represent in linear regression?
- A) The correlation coefficient
- B) The proportion of variance in y explained by x
- C) The standard error of the regression
- D) The degrees of freedom

**Question 3.7** - In a multiple linear regression model with more than one predictor, which R² value should you report?
- A) Multiple R-squared
- B) Adjusted R-squared
- C) Either one
- D) The larger of the two

**Question 3.8** - What does the principle of parsimony suggest in model selection?
- A) Always include all possible variables
- B) Use the simplest model that adequately explains the data
- C) Never remove variables once added
- D) Maximize R² at all costs

**Question 3.9** - Polynomial regression of degree 2 would include which terms?
- A) Only x
- B) x and x²
- C) x, x², and x³
- D) Only x²

**Question 3.10** - When using log transformation on the response variable, to interpret the effect of a one-unit increase in x, you should:
- A) Exponentiate the coefficient and subtract 1, then multiply by 100%
- B) Simply report the coefficient value
- C) Take the logarithm of the coefficient
- D) Square the coefficient

**Question 3.11** - Non-linear regression differs from polynomial regression in that:
- A) Non-linear regression cannot use least squares
- B) Polynomial regression uses the `lm()` function while non-linear uses `nls()`
- C) Polynomial regression is always more accurate
- D) Non-linear regression requires transformed variables

**Question 3.12** - For exponential regression (y = y₀e^(kx)), which parameter represents the value of y when x=0?
- A) k
- B) y₀
- C) The slope
- D) The intercept

**Question 3.13** - An asymptotic relationship is best described as:
- A) Linear with constant slope
- B) Polynomial with multiple turning points
- C) Increases rapidly then levels off at a limit
- D) Decreases symmetrically

**Question 3.14** - Collinearity in multiple regression refers to:
- A) When residuals are not independent
- B) When two or more predictors are highly correlated
- C) When the outcome variable is binary
- D) When variances are unequal

**Question 3.15** - "Correlation does not imply causation" means:
- A) Correlations are never useful
- B) Two variables can be correlated without one causing the other
- C) You should never report correlations
- D) Only experiments can show causation

---

## **BONUS CHALLENGE QUESTIONS**

**Bonus 1** - A researcher collects data on plant height and finds it follows a lognormal distribution. Should they use the raw data or transformed data for their one-sample t-test?
- A) Always use raw data
- B) Always use transformed data
- C) Use the transformed data to meet normality assumptions
- D) Use raw data if sample size is large enough

**Bonus 2** - When interpreting a partial regression coefficient in multiple regression, what must you remember?
- A) It represents the total effect of that predictor
- B) It's interpreted holding all other variables constant
- C) It measures correlation, not causation
- D) Both B and C

**Bonus 3** - If your linear regression assumptions are violated, which is NOT a reasonable next step?
- A) Transform the data
- B) Use a different model (e.g., non-linear)
- C) Increase your sample size
- D) Report results anyway since sample size is large

---

Good luck with your revision! Review the handbook for each topic area if you're unsure about any questions.
