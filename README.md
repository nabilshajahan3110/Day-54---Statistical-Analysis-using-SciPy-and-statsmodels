## Day-54---Statistical-Analysis-using-SciPy-and-statsmodels
As part of a 75-day data analysis challenge, this work on Python covers statistical analysis using SciPy and statsmodels.


Statistical analysis using SciPy and statsmodels in Python involves leveraging these libraries to analyze, interpret, and infer data properties through statistical methods. These libraries provide tools for conducting various statistical tests, modeling, and data analysis. Here's an overview of how these libraries are used:

**SciPy (Scientific Python)**
SciPy is a general-purpose library that provides efficient algorithms and functions for scientific and numerical computations, including statistical analysis.

**Key Features of SciPy for Statistical Analysis:**
**Descriptive Statistics:** Functions for calculating mean, median, variance, standard deviation, skewness, kurtosis, etc.
**Statistical Tests:**
*Parametric Tests:* T-tests (ttest_ind, ttest_rel), ANOVA (f_oneway).
*Non-Parametric Tests:* Mann-Whitney U test (mannwhitneyu), Wilcoxon test (wilcoxon), Kruskal-Wallis test (kruskal).
*Correlation Analysis:* Pearson (pearsonr), Spearman (spearmanr), and Kendall Tau (kendalltau).
*Probability Distributions:*
Probability density functions (PDFs), cumulative distribution functions (CDFs), and sampling.
Common distributions like normal, uniform, binomial, Poisson, etc.
*Hypothesis Testing:*
p-values and test statistics are used to infer whether to reject a null hypothesis.
*Fitting Distributions:* Fit data to statistical distributions to estimate their parameters.

**statsmodels**
statsmodels is a library for statistical modeling and hypothesis testing, offering more advanced and detailed tools for statistical analysis compared to SciPy.

**Key Features of statsmodels:**
**Descriptive Statistics:** Similar to SciPy but includes additional summary statistics.
**Regression Models:**
*Linear Regression:* Ordinary Least Squares (OLS).
*Logistic Regression:* For binary outcomes.
Generalized Linear Models (GLM).
Time-series models (ARIMA, SARIMAX).
*Statistical Tests:*
ANOVA, hypothesis tests, goodness-of-fit tests, etc.
*Time-Series Analysis:* Tools for analyzing and forecasting time-series data.
*Custom Formulas:* Specify statistical models using R-like formulas.
*Model Diagnostics:* Tools for checking assumptions and residuals.
