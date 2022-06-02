# MechaCar_Statistical_Analysis
Statistical Analysis using R

# Overview & Purpose


## Deliverable 1 - Linear Regression to Predict MPG

mpg=

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

At a confidence level of 95%, the significance level is 0.05. Therefore, the p-value should be less than 0.05 to be statistically significant.

As a result, the variables or coefficients that provides a non-random amount of variance to the mpg values are vehicle length(Pr(>|t|)=2.60e-12),ground-clearance(Pr(>|t|)=5.21e-08) and also the intercept(Pr(>|t|)=5.08e-08).

**Is the slope of the linear model considered to be zero? Why or why not?**

In case of linear regression analysis,

H<sub>0</sub> : The slope of the linear model is zero 

H<sub>1</sub>: The slope of the linear model is not zero

In this case, our p-value is less than our assumed significance level of 0.05

p-value=5.35e-11

p-value<0.05

Therefore, we reject the null hypothesis, which means that the slope of the linear model is not zero.
