# ENVX1002 Module 3 - Additional Practice Questions

## Comprehensive Module 3 Revision (Correlation, Regression & Modeling)

This document provides extra practice questions focused on Module 3 topics to strengthen your understanding.

---

## **SECTION A: CORRELATION & RELATIONSHIPS**

**Q3A.1** - You're analyzing the relationship between rainfall and crop yield. The scatter plot shows points arranged in an upward trend with moderate scatter around the line. Which correlation coefficient would you expect to see?
- A) r = 0.15
- B) r = 0.45
- C) r = 0.85
- D) r = -0.65

**Q3A.2** - A study finds that ice cream sales are strongly correlated with drowning deaths (r = 0.92). Which of the following is the most likely explanation?
- A) Ice cream consumption causes drowning
- B) Drowning deaths cause people to buy ice cream
- C) A third variable (temperature/season) influences both
- D) The correlation coefficient is incorrectly calculated

**Q3A.3** - You have three datasets with the following relationships. Which would be MOST appropriate to analyze using Spearman's rank correlation instead of Pearson's?
- A) Height vs weight in humans
- B) Temperature vs oxygen dissolution in water
- C) Student ranking (1st, 2nd, 3rd...) vs starting salary
- D) Age vs income in a random sample

**Q3A.4** - Two variables have a Pearson's r = 0. Which statement is true?
- A) The variables are completely unrelated
- B) There is no linear relationship, but there could be a non-linear one
- C) One variable does not cause the other
- D) Both B and C

**Q3A.5** - When describing a relationship between two variables, which of these would strengthen a positive correlation coefficient?
- A) Points more scattered around the trend line
- B) Points closer to following a curved pattern
- C) Points more tightly clustered around the trend line
- D) One strong outlier at the extreme

---

## **SECTION B: LINEAR REGRESSION FUNDAMENTALS**

**Q3B.1** - You fit a simple linear regression and get: ŷ = 25 + 3.5x. What does the "3.5" represent?
- A) The correlation coefficient
- B) The predicted value when x = 0
- C) For each unit increase in x, y increases by 3.5 units on average
- D) The standard error of the prediction

**Q3B.2** - In the regression equation ŷ = 15 - 2.1x, what is the y-intercept?
- A) -2.1
- B) 15
- C) 2.1
- D) Cannot be determined

**Q3B.3** - Which of the following does NOT directly affect the calculation of the regression line?
- A) The covariance between x and y
- B) The variance of x
- C) The correlation between x and y
- D) The color of the data points

**Q3B.4** - You have a regression model explaining 68% of the variation in your response variable. Which interpretation is correct?
- A) The model is "good" and predictions will always be accurate
- B) 32% of variation remains unexplained
- C) The correlation between x and y is 0.82
- D) Both B and C

**Q3B.5** - When checking the "Residuals vs Fitted" plot for assumption violations, what pattern would indicate a problem?
- A) Points randomly scattered around the zero line
- B) Points forming a "fan" or "cone" shape
- C) Points falling on a horizontal line
- D) Points evenly distributed across both positive and negative

---

## **SECTION C: REGRESSION ASSUMPTIONS & DIAGNOSTICS**

**Q3C.1** - In a Q-Q plot for checking normality of residuals, what pattern indicates a violation of the normality assumption?
- A) Points fall on a straight diagonal line
- B) Points deviate from the line, especially at the tails
- C) Points form a U-shape
- D) Both B and C

**Q3C.2** - Your residual plot shows a curved pattern with residuals systematically positive then negative. What assumption is violated?
- A) Normality
- B) Linearity
- C) Independence
- D) Equal variance

**Q3C.3** - The "Scale-Location" plot is used to check which assumption?
- A) Linearity
- B) Independence
- C) Normality
- D) Equal variance (homoscedasticity)

**Q3C.4** - Which situation would MOST clearly violate the independence assumption?
- A) Sequential measurements from the same individual over time
- B) Random samples from different populations
- C) Repeated measurements on independent organisms
- D) Data from a stratified random sample

**Q3C.5** - You notice two extreme outliers in your residual plot (marked by the software). What should you do?
- A) Always remove them to improve the model
- B) Investigate why they're extreme; report results with and without them
- C) Use them as they are; they're just unusual observations
- D) Apply a transformation to all data

---

## **SECTION D: DATA TRANSFORMATION**

**Q3D.1** - Your scatter plot shows an exponential growth pattern. What transformation would you most likely try first?
- A) Square root transformation
- B) Natural log transformation of y
- C) Inverse transformation (1/y)
- D) Arcsine transformation

**Q3D.2** - After applying a log transformation to your response variable, you get the equation: log(y) = 1.2 + 0.08x. For a one-unit increase in x, what is the approximate percent change in y?
- A) 8%
- B) 1.2%
- C) 0.08%
- D) Cannot calculate from this information

**Q3D.3** - If you fit: sqrt(y) = 10 + 2x, and x increases by 1, how much does y increase?
- A) 2 units
- B) Cannot be simply calculated; need to consider the quadratic relationship
- C) 4 units
- D) 10 units

**Q3D.4** - When should you apply a transformation?
- A) Before fitting the model to meet assumptions
- B) After fitting the model if assumptions are violated
- C) Always, for all datasets
- D) Only if the original data is already normally distributed

**Q3D.5** - You transform data using y' = log₁₀(y) and find a good linear relationship. To report the result in the original (untransformed) scale, you should:
- A) Use the back-transformation y = 10^(ŷ')
- B) Report results only on the log scale
- C) Use y = e^(ŷ')
- D) Square all predictions

---

## **SECTION E: MULTIPLE LINEAR REGRESSION**

**Q3E.1** - In multiple regression with predictors x₁, x₂, and x₃, the coefficient for x₁ represents:
- A) The total effect of x₁ on y
- B) The effect of x₁ on y, holding x₂ and x₃ constant
- C) The correlation between x₁ and y
- D) The proportion of variance explained by x₁

**Q3E.2** - You compare two models:
- Model A: Ozone ~ Temperature (R² = 0.49)
- Model B: Ozone ~ Temperature + Wind + Solar.R (Adjusted R² = 0.655)

Which model should you prefer and why?
- A) Model A; it's simpler
- B) Model B; adjusted R² is higher and accounts for more predictors
- C) Model A; R² values shouldn't be compared across models
- D) Neither; they explain too little variance

**Q3E.3** - What does collinearity between predictors affect?
- A) The ability to estimate individual coefficient effects clearly
- B) The overall model's ability to predict
- C) The standard errors of the coefficients
- D) Both A and C

**Q3E.4** - When comparing models using the principle of parsimony, which is preferred?
- A) The model with the most variables
- B) The model that explains the most variance
- C) The simplest model that adequately explains the data
- D) The model with the highest correlation

**Q3E.5** - In summary output, you see that for a multiple regression model the overall F-statistic is significant (p < 0.001), but one individual predictor has p = 0.68. What should you do?
- A) Keep all predictors; the overall model is significant
- B) Remove the non-significant predictor and refit
- C) Report that the model is invalid
- D) Assume collinearity is present

---

## **SECTION F: POLYNOMIAL & NON-LINEAR REGRESSION**

**Q3F.1** - You fit a quadratic model: y = 50 + 2x - 0.5x². Which statement is true?
- A) This is a linear model
- B) This is an exponential model
- C) The relationship has a maximum/peak point
- D) The relationship increases indefinitely

**Q3F.2** - For polynomial regression fitting, which R function would you use?
- A) `lm(y ~ x)`
- B) `lm(y ~ poly(x, 2))`
- C) `nls(y ~ a*exp(b*x))`
- D) `lm(y ~ log(x))`

**Q3F.3** - The difference between fitting models with `lm()` vs `nls()` is:
- A) `nls()` is always more accurate
- B) `lm()` uses least squares; `nls()` uses maximum likelihood
- C) `lm()` can handle polynomial terms; `nls()` is for truly non-linear functions
- D) `nls()` requires transformed data

**Q3F.4** - For an exponential decay model (y = y₀e^(-kx)), if k > 0, what happens as x increases?
- A) y increases exponentially
- B) y decreases exponentially toward zero
- C) y remains constant
- D) y first increases then decreases

**Q3F.5** - An asymptotic growth model levels off at a maximum value. Which parameter represents this maximum?
- A) R₀
- B) Asym
- C) lrc
- D) k

---

## **SECTION G: MODEL EVALUATION & COMPARISON**

**Q3G.1** - What does residual standard error (RSE) tell you in a regression model?
- A) How many residuals there are
- B) The typical magnitude of prediction errors
- C) Whether assumptions are met
- D) The correlation strength

**Q3G.2** - Comparing three models using AIC or BIC, which model would you select?
- A) The one with the highest AIC/BIC value
- B) The one with the lowest AIC/BIC value
- C) The one with the most parameters
- D) The one that explains the most variance

**Q3G.3** - You fit a complex model with many predictors and get R² = 0.99. What should you be concerned about?
- A) The model is definitely overfitted
- B) The model might be overfitted; check adjusted R² and residuals
- C) Nothing; a high R² is always good
- D) The data must contain errors

**Q3G.4** - Which metric is most useful for comparing models with different numbers of predictors?
- A) R²
- B) Adjusted R²
- C) Residual standard error
- D) Correlation coefficient

**Q3G.5** - When should you NOT use a linear model?
- A) When the relationship is clearly non-linear
- B) When assumptions are violated
- C) When residuals show patterns
- D) All of the above

---

## **SECTION H: INTERPRETATION & APPLICATION**

**Q3H.1** - You have the model: log(Income) = 9.5 + 0.15(Education), where Education is years of schooling. Interpret the coefficient 0.15:
- A) Each additional year of education increases income by $0.15
- B) Each additional year of education increases income by approximately 15%
- C) The relationship is negative
- D) The intercept is 0.15

**Q3H.2** - A biologist fits: Growth = 50 - 0.8(Temperature). Temperature ranges from 10°C to 30°C in the data. Can you reliably predict growth at 50°C?
- A) Yes, the linear equation works at any temperature
- B) No; 50°C is outside the range of observed data (extrapolation)
- C) Yes, but only if R² > 0.7
- D) No; temperature is a categorical variable

**Q3H.3** - Your multiple regression shows that adding a new predictor decreases adjusted R² but increases regular R². What does this indicate?
- A) The new predictor is useful
- B) The new predictor is adding noise, not signal
- C) The model is overfitting
- D) Both B and C

**Q3H.4** - In a scientific paper, you read: "We found a significant positive correlation (r = 0.42, p = 0.03) between study hours and exam scores." Which is the best interpretation?
- A) More study hours definitely cause higher exam scores
- B) There is a moderate positive linear relationship, statistically significant
- C) Study hours explain 42% of exam score variation
- D) The relationship is practically important

**Q3H.5** - When presenting regression results, which elements should you always include?
- A) The equation, R², and residual diagnostics
- B) P-values and confidence intervals for coefficients
- C) Interpretation in context of the research question
- D) All of the above

---

## **SECTION I: SCENARIO-BASED QUESTIONS**

**Q3I.1** - Scenario: You're analyzing plant biomass vs. soil nitrogen. The scatter plot looks exponential, and diagnostic plots show curved residuals. What's your best first step?
- A) Report the linear model as-is
- B) Try a log transformation on biomass
- C) Remove outliers
- D) Use a non-linear model immediately

**Q3I.2** - Scenario: Your regression has high R² (0.92) but residuals show clear patterns in the Residuals vs Fitted plot. What do you conclude?
- A) The model is perfect
- B) The LINE assumptions are violated despite high R²
- C) You should report results anyway because R² is high
- D) The data contains errors

**Q3I.3** - Scenario: You fit a polynomial model (degree 3) and get R² = 0.87. You fit a polynomial model (degree 5) and get R² = 0.889. Which should you use?
- A) The degree 5 model; higher R²
- B) The degree 3 model; principle of parsimony
- C) It depends on adjusted R² and whether all coefficients are significant
- D) They're equivalent

**Q3I.4** - Scenario: In multiple regression for predicting house prices, you have predictors: square footage, number of bedrooms, age, and location. Bedrooms and square footage are highly correlated (r = 0.89). What might happen?
- A) The model will be more accurate
- B) Coefficients may be unstable and hard to interpret
- C) You can include both without any issues
- D) The model's R² will be artificially low

**Q3I.5** - Scenario: You're modeling fish growth rate vs. water temperature. The relationship is asymptotic (levels off at high temps). Which model is most appropriate?
- A) Simple linear regression
- B) Polynomial regression
- C) Asymptotic non-linear model (SSasymp)
- D) Log transformation of temperature

---

## **BONUS: CONCEPTUAL QUESTIONS**

**Q3Bonus.1** - Why is it important to check assumptions BEFORE reporting regression results, rather than only looking at R²?
- A) High R² guarantees assumptions are met
- B) Violated assumptions make p-values and confidence intervals unreliable
- C) Assumptions don't really matter for modern computers
- D) It's just a formality

**Q3Bonus.2** - Explain why you cannot reliably extrapolate beyond the range of your original data:
- A) The relationship might change outside the observed range
- B) You're assuming the pattern continues, which may not be true
- C) The model was fit only to the observed data
- D) All of the above

**Q3Bonus.3** - If two variables are uncorrelated (r ≈ 0), why might you still find a significant p-value in simple linear regression?
- A) Because p-values and correlations measure different things
- B) You can't; uncorrelated variables always have non-significant p-values
- C) Sample size is very large
- D) The model is invalid

**Q3Bonus.4** - Why do we prefer adjusted R² over regular R² in multiple regression?
- A) Adjusted R² prevents overfitting by penalizing additional predictors
- B) Adjusted R² is always larger
- C) Regular R² cannot be calculated for multiple regression
- D) There's no real difference

**Q3Bonus.5** - In the context of model building, what does "the simplest model that adequately explains the data" mean?
- A) Use the fewest predictors that still provide good explanatory power
- B) Always use a linear model
- C) Remove any predictor that isn't perfectly significant
- D) Use the model that matches your preferred statistical test

---

## **ANSWER GUIDE COMING SOON**

Use these questions to:
✓ Identify weak areas in Module 3
✓ Test deeper understanding
✓ Practice interpretation
✓ Build confidence for application questions

Review the handbook's Module 3 sections for each topic area before attempting these questions. A detailed answer key with explanations will follow.

Good luck with your Module 3 revision!
