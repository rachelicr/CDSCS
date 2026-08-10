# Statistics

## Descriptive
- **Mean/Median/Mode** — central tendency.
- **SD / Variance** — spread. `numpy`
- **IQR** — Q3–Q1, outlier-robust spread.
- **Skewness/Kurtosis** — shape of distribution.

## Distributions
- **Normal** — bell curve; assumed by many parametric tests.
- **Binomial** — success/failure counts (e.g. mutation present/absent).
- **Poisson** — rare event counts (e.g. read counts).
- **Negative Binomial** — overdispersed counts; standard for RNA-seq. `DESeq2`, `edgeR`

## Hypothesis Testing
- **Null/Alt hypothesis (H0/H1)** — baseline vs. effect claim.
- **p-value** — probability of data given H0.
- **t-test** — compare two group means.
- **ANOVA** — compare >2 group means.
- **Chi-square test** — categorical association (e.g. mutation vs. subtype).
- **Fisher's exact test** — categorical, small samples.
- **Mann-Whitney U / Wilcoxon** — non-parametric group comparison.
- **Log-rank test** — compare survival curves.

## Multiple Testing
- **Multiple testing problem** — inflated false positives across many genes/features.
- **Bonferroni correction** — conservative family-wise correction.
- **FDR (Benjamini-Hochberg)** — standard for genomics (q-value). `statsmodels`

## Effect & Uncertainty
- **Effect size** — Cohen's d, odds ratio, hazard ratio.
- **Confidence interval (CI)** — range of plausible true values.
- **Power analysis** — sample size needed to detect effect. `statsmodels.stats.power`

## Regression
- **Linear regression** — continuous outcome.
- **Logistic regression** — binary outcome (e.g. relapse yes/no).
- **Cox proportional hazards** — survival with covariates. `lifelines`, `survival` (R)
- **Kaplan-Meier estimator** — survival curve estimation. `lifelines`

## Bayesian
- **Prior/Posterior/Likelihood** — Bayes' theorem components.
- **Bayesian inference** — updating belief with data. `PyMC`, `Stan`

## Links
- [StatQuest (YouTube)](https://www.youtube.com/@statquest)
- [Points of Significance (Nature Methods series)](https://www.nature.com/collections/qghhqm/pointsofsignificance)
