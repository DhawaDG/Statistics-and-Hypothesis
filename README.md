### Statistics & Hypothesis Testing

This section of my portfolio is a deep dive into the world of statistics and hypothesis testing. It showcases my ability to apply a wide range of statistical methods to analyze data, validate assumptions, and draw meaningful, data-driven conclusions. From exploring data distributions to implementing hypothesis tests, these projects demonstrate a rigorous approach to quantitative analysis.

---

#### Topics Covered

- **Exploring Binary and Categorical Data:** Techniques for summarizing and visualizing categorical variables.
- **Correlation:** Measuring relationships between variables using correlation coefficients.
- **Exploring Two or More Variables:** Multivariate analysis to understand interactions and dependencies.
- **Data and Sampling Distributions:** Understanding how sample data relates to population distributions.
- **Sampling Distribution of a Statistic:** Examining the variability of sample statistics.
- **The Bootstrap:** Resampling methods to estimate the accuracy of sample statistics.
- **Confidence Intervals:** Calculating intervals to estimate population parameters.
- **Normal Distribution:** Properties and applications in statistical inference.
- **Long-Tailed Distributions:** Identifying and handling distributions with heavy tails.
- **Student’s t-Distribution:** Applying t-distribution for small sample sizes.
- **Binomial Distribution:** Modeling binary outcomes and proportions.
- **Poisson and Related Distributions:** Analyzing count data and rare events.
- **Techniques:** Implementing z test, t test, p value calculations, and KS test for hypothesis testing.

---
#### Hands-on Projects

| SN | Statistics & Hypothesis Testing Projects |
|:---:|:---|
| 1 | **[Sampling Bias and Mean Reversion in Football Analytics](https://github.com/DhawaDG/Sampling_Bias_and_Mean_Reversion_in_Football_Analytics/tree/master)** |
| 2 | **[Z-Test vs T-Test - A Practical Guide with NHANCES BMI Data Analysis](https://github.com/DhawaDG/Z-Test-vs-T-Test-A-Practical-Guide-with-NHANCES-BMI-Data-Analysis)** |
| 3 | **[Sampling-Distributions-and-Confidence-Intervals-CLT-vs-Bootstrapping](https://github.com/DhawaDG/Sampling-Distributions-and-Confidence-Intervals-CLT-vs-Bootstrapping)** |
| 4 | **[Hospital Patient Outcome Analysis Using z-test and t-test](https://github.com/DhawaDG/Hospital-Patient-Outcome-Analysis-Using-z-test-and-t-test)** |
| 5 | **[E-commerce Flash Sale and Spike Order Analysis Using Binomial and Poisson Distribution](https://github.com/DhawaDG/E-commerce-Flash-Sale-and-Spike-Order-Using-Binomial-and-Poisson-Distribution)** |
| 6 | **[Amazon Product Return Analysis Using Exponential Distribution](https://github.com/DhawaDG/Amazon-Product-Return-Analysis-Using-Exponential-Distribution)** |
| 7 | **[E-commerce Churn Rate Analysis Using Weibull Distributions](https://github.com/DhawaDG/E-commrce-Churn-Rate-analysis-using-Weibull-Distributions)** |

---

#### Handwritten Notes PDF

A collection of my detailed handwritten notes and summaries on these topics is available in PDF format.  

> **Note on Viewing PDFs on GitHub:**  
> If you encounter an "***Unable to render code block***" or preview error when opening a **📄 View PDF on GitHub** link, please reload the page or use the **⬇️ Download PDF** link right below it.

### Correlation :

| Topics Covered | Page |
| :--- | :--- |
| Correlation Introduction & Types: Definition, types based on direction (Positive, Negative, No Correlation), and types based on strength using Pearson's correlation coefficient ($r$) interpretation table | `page 1` |
| Pearson's Correlation: Definition, mathematical formula, manual calculation example using height and weight, and Python implementation using pandas (`df.corr`), NumPy (`np.corrcoef`), and SciPy (`stats.pearsonr` with p-values) | `page 2–5` |
| Spearman's Rank Correlation: Definition of monotonic relationships, formula ($r_s$), when to use, manual step-by-step calculation example with product price vs. customer satisfaction, and Python implementation (`stats.spearmanr`) | `page 6–8` |
| Kendall's Tau Correlation: Pairwise comparisons (concordant vs. discordant pairs), manual calculation example with employee experience vs. performance, Python implementation (`stats.kendalltau`), and interpretation | `page 9–10` |
| Comprehensive Comparison Summary: Pearson vs. Spearman vs. Kendall's Tau comparison table covering feature breakdown, data types, normality assumptions, outlier sensitivity, tied ranks, and performance on large datasets | `page 11` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_correlations_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_correlations_watermark.pdf)

### Data and Sampling Distributions:
| Topics Covered | Page |
| :--- | :--- |
| Random Sampling and Samples: Key Definitions (Population, Sample, Size, Random Sampling, Stratified Sampling) | `page 1` |
| Sample Biases: Causes (Non-random selection, self-selection) and Impact | `page 1` |
| Data Quality vs. Quantity, Common Pitfalls (Convenience Sampling, Survivorship Bias), and Practical Implications for Data Scientists | `page 2` |
| Intuitive Explanation of Sampling (The Soup Analogy) | `page 2` |
| Random Sampling Goal and Methods to Avoid Bias (Lottery, Stratified Sampling) | `page 3` |
| Python Example: Random vs. Biased vs. Stratified Samples (Population simulation with age and spending habits) | `page 4` |
| Deep Dive into np.random.seed(42) and np.random.randint() | `page 5` |
| Deep Dive into np.random.randint() with size and np.random.normal() (Bell curve distribution parameters) | `page 6` |
| Visualizing Spending Distribution and Pandas .loc[] Condition Filtering and Transformation | `page 7` |
| Python Code Walkthrough: Random Sampling, Biased Sampling, and Stratified Sampling logic (groupby, apply, lambda) | `page 8` |
| group_keys=False Explanation and Before/After Comparison in Stratified Sampling | `page 9` |
| What is Bias? (Systematic error vs. random noise) and The Target Analogy | `page 10` |
| Types of Bias in Data Science (Sampling, Measurement, Model Biases) and How to Detect Bias | `page 11–12` |
| Python Code: Simulating Unbiased vs. Biased Shooters (Scatter plots, axvline, axhline) | `page 13` |
| Visual Interpretation of Unbiased and Biased Shooters | `page 14` |
| Key Takeaways on Bias, Randomness, Sources, and Fixes (with a Recruiter Analogy) | `page 15` |
| Why Random Sampling? and Challenges in Defining the Population (Active vs. Inactive, Refunds, Resellers, Test Data, Timing/Flows) | `page 16` |
| Stratified Sampling Use Case and Flow, plus Python Code for Voter Race Distribution Simulation | `page 17–18` |
| Simulating Web Traffic Data by Time Stamps (pd.date_range) and Poisson Distribution (np.random.poisson) | `page 19–21` |
| Size vs. Quality: Data Quality Checks (Null values, duplicate rows, and outlier detection using standard deviations) | `page 22–25` |
| When Smaller Samples Are Better vs. When Big Data Is Necessary (Small Data vs. Big Data comparison table) | `page 26` |
| Sample Mean ($\bar{x}$) vs. Population Mean ($\mu$): Core Concepts, Law of Large Numbers, Central Limit Theorem, and Pitfalls | `page 27` |
| Python Implementation: Sample Mean vs. Population Mean and Comparison of np.random.sample vs. np.random.choice | `page 28` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_1_population_sample_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_1_population_sample_watermark.pdf)

### Sampling Distribution of a Statistic:
| Topics Covered | Page |
| :--- | :--- |
| Selection Bias: Definition and Real-World Types (Data Snooping, Cherry-Picking, Survivorship Bias, Time Interval Bias) | `page 1` |
| How to Avoid Selection Bias (Pre-specify hypotheses, holdout data, random sampling, target shuffling/permutation test) and Rules of Thumb | `page 2` |
| Conclusion on Strategies and Holdout Data in Model Validation | `page 3` |
| Python Code & Explanation: Detecting Fake Patterns (Data Snooping) using simulated stock strategies | `page 4–5` |
| Code Explanation Continued: Matrix dimensions, max(axis=0) operations, and signal vs. noise | `page 6–7` |
| Regression to the Mean: Definition, Key Examples across Sports, Testing, and Business, and Why It Matters | `page 8–9` |
| How to Avoid Mistaking Regression to the Mean for Real Change (Control groups, repeated measurements, assessing luck) | `page 10` |
| Python Code & Explanation: Simulating Rookies vs. Sophomore Year Performance to Demonstrate Regression to the Mean | `page 11–12` |
| Sampling Distribution of a Statistic: Definition, Central Limit Theorem (CLT), Standard Error, and Key Takeaways (Cookie Baking Analogy) | `page 13` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_2_selectionbias_sampling_distributions_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_2_selectionbias_sampling_distributions_watermark.pdf)

### Central Limit Theorem (CLT):
| Topics Covered | Page |
| :--- | :--- |
| Central Limit Theorem (CLT) & Sampling Distribution: Definition, what it means, and why it's useful (works on non-normal data, kicks in around $n \ge 30$, explains polls) | `page 1` |
| Data Science Reality Check on CLT & Standard Error: The "Margin of Error" metric, formula, and practical implications for sample precision | `page 1–2` |
| Python Code: Simulating weird non-normal data (exponential + normal) and demonstrating CLT across different sample sizes ($n=1, 5, 30, 100$) using matplotlib subplots | `page 2–3` |
| Code Walkthrough: Simulating skewed distributions with `np.concatenate()`, loop logic via `enumerate()`, and sampling with replacement using `np.random.choice()` | `page 3–5` |
| CLT in Action: Visualizing how sample means transition from matching the skewed original data to forming a normal-shaped distribution as sample size increases | `page 6` |
| Pure CLT Math: Independent and identically distributed (i.i.d.) random variables, population mean/variance formulas, and a discrete uniform distribution example ($n=4$) | `page 6` |
| Connecting Mathematical CLT and the Empirical Rule ($n \ge 30$): The relationship between theoretical asymptotic normality and practical simulation rules of thumb | `page 7` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_3_CLT_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_3_CLT_watermark.pdf)

### Bootstrapping :
| Topics Covered | Page |
| :--- | :--- |
| What is Bootstrapping? Definition, core idea, step-by-step workflow, and key terminology (Bootstrap Sample, Resampling) | `page 1` |
| Why Use Bootstrapping? Traditional methods vs. Bootstrap comparison, common use cases, key insights, and common pitfalls | `page 1–2` |
| Advanced Applications: Bagging (Bootstrap Aggregating) and Bootstrap Hypothesis Testing | `page 3` |
| Python Code & Walkthrough: Bootstrapping the median using lognormal data, resampling with replacement, calculating 95% confidence intervals, and plotting the distribution | `page 3–5` |
| Comparing Bootstrapping vs. Permutation Tests: Feature breakdown, methods, goals, outputs, assumptions, and practical applications | `page 5–7, 10` |
| Resampling Mechanics: With replacement vs. Without replacement (Analogies, why it matters in bootstrapping, and real-world examples) | `page 8–9` |
| Summary Guide: When to Choose Bootstrapping vs. Permutation Tests | `page 10` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_4_bootstrapping_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_4_bootstrapping_watermark.pdf)

### Confidence Interval (CI) :
| Topics Covered | Page |
| :--- | :--- |
| What is a Confidence Interval (CI)? Definition, key components (Point Estimate, Margin of Error, Confidence Level), and basic intuition | `page 1` |
| Point Estimates, Margin of Error, Confidence Level deep dive, and weather forecasting analogy | `page 2` |
| Why CIs Matter in Data Science, Bootstrap Method for calculating CIs, and interpretation tips | `page 3` |
| Confidence Level Trade-offs (90% vs. 95% vs. 99% CIs), seat belt analogy, and sample size power | `page 3–4, 6` |
| The Biggest Misconception (What 95% Really Means) and Thought Experiment with 100 researchers | `page 4–5` |
| Practical Implications for Data Science: Quick decisions vs. medical trials, and reporting sample sizes | `page 5` |
| Common Missteps: Confidence Intervals vs. Prediction Intervals (PI) | `page 5` |
| The Normality Trap ($t$-distribution limits on skewed data) and Sample Size Blindness | `page 6` |
| Solo Confidence Interval definition, formula, and Python Code (Bootstrapping 90% CI for mean income) | `page 6` |
| Walkthrough of Bootstrap Code & Output, including the Cookie Jar Analogy and step-by-step array selection | `page 7–9` |
| Comparison Table: NumPy's `percentile()` vs. Pandas' `quantile()` | `page 10` |
| Python Code & Walkthrough: Calculating Point Estimates, Margin of Error, standard normal 95% CIs vs. Scipy Bootstrap Median CIs for skewed income data | `page 10–11` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_5_CI_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_5_CI_watermark.pdf)

### Normal Distribution & Z-Test :

| Topics Covered | Page |
| :--- | :--- |
| Normal Distribution: Definition, properties, symmetry, and $Z$-score mathematical definition and interpretation | `page 1–3` |
| Standard Normal Distribution: Graphical interpretation and practical applications (Outlier detection, comparing SAT vs. ACT scales) | `page 4–5` |
| Standardizing Features for Machine Learning (`StandardScaler`), key properties, when to use/avoid $Z$-scores, and model assumptions (Linear/Logistic Regression, Neural Networks) | `page 6–9` |
| Real-World Analogy: Goal Scoring Time (Normal vs. Bimodal Distribution) and analytical insights | `page 10–11` |
| Why QQ-Plots Are Essential for Checking Normal Distributions (Comparison with histograms and statistical tests) | `page 12–13` |
| Extra Core Concepts: Standard deviation explained with a travel time analogy, variance, and the Empirical Rule (68-95-99.7) | `page 14–17` |
| Python Implementation: Finding $Z$-scores manually vs. via `scipy.stats.zscore`, SAT vs. ACT percentile calculation (`norm.cdf`), and QQ-plots for normal, right-skewed, and heavy-tailed data | `page 18–22` |
| Standardization vs. Normalization: Why standardization ($Z$-score) is a linear transformation that does not change shape, skewness, or kurtosis, and when to use non-linear transforms (Log, Box-Cox) | `page 23–27` |
| Standard Normal & QQ-Plot Warnings: Small sample warnings ($n \le 50$) and the Three-Panel Diagnostic Approach (Raw Histogram, Standardized Histogram, QQ-Plot) | `page 28–31` |
| One-Sample $Z$-Test: Theoretical background, hypothesis setup, formula, practical liquid bottling example, Python implementation (`statsmodels`), and interpretation of left-tailed vs. two-tailed tests (`norm.ppf`) | `page 32–43` |
| Two-Sample $Z$-Test: Objective, formula, machine comparison example, manual and Python calculation, p-values (`norm.sf`), and the "Rain in the park" real-world analogy for understanding p-values | `page 44–51` |
| Bridge Analogy for P-Value Tails: Step-by-step breakdown of PDF, CDF, SF, and two-tailed p-values | `page 52–55` |
| $Z$-Test for Proportions: One-sample and two-sample proportion tests, formulas, practical examples, Python code snippets, and proportion analogies | `page 56–62` |
| The Motive of Hypothesis Testing: Understanding the role of the judge/weather forecaster analogy (testing $H_0$ rather than trying to prove $H_1$) | `page 63–64` |
| Comprehensive P-Value Syntax Reference Guide: Manual vs. built-in function syntax for $Z$-tests and $T$-tests (One-sample, two-sample, proportions, independent, and paired $T$-tests) | `page 65–68` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_6_normal_ztest_watermark_compressed_compressed.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_6_normal_ztest_watermark_compressed_compressed.pdf)
  
### Long-Tailed Distributions:
| Topics Covered | Page |
| :--- | :--- |
| The Myth of Normality & Key Features of Long-Tailed Data: Real-world data distributions and the "Pizza Delivery Time" Surprise (Normal distribution predictions vs. reality) | `page 1` |
| Pizza Delivery Results & Key Takeaways: How normal distributions underestimate extreme events, and re-evaluating "Black Swans" vs. poor planning | `page 2` |
| Visualizing Long Tails & Types of Long-Tailed Distributions: Detailed breakdown and Python generator summary table for Power Law, Log-Normal, Cauchy, and Poisson distributions | `page 3` |
| Why Long-Tailed Data Matters: The danger of assuming normality (undercasting risk, faulty predictions), better approaches (Extreme Value Theory, robust statistics), and handling long-tailed data | `page 4` |
| Python Code & Walkthrough: Pizza Delivery Times Example (Simulating normal deliveries and exponential long-tail extremes, combining datasets with `np.concatenate()`, and plotting a QQ-plot) | `page 5–6` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_7_longtail_distributions_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_7_longtail_distributions_watermark.pdf)

### Student $t$-Distributions & t- Test:
| Topics Covered | Page |
| :--- | :--- |
| Student $t$-Distributions: Definition, adjusting for small sample uncertainty, family of curves ($df = n - 1$), and confidence interval formula | `page 1` |
| Full Explanations: The "Normal-Plus" distribution, degrees of freedom ($df = n - 1$), key properties table ($t$-distribution vs. normal), and the constraint principle | `page 2` |
| Why $n - 1$ Matters: The constraint principle explained with exam scores, sample variance, Bessel's correction, and real-world implications for small vs. large samples | `page 3` |
| Variance & Degrees of Freedom: Delivery driver distance example, sum of squared deviations, and variance intuition | `page 4` |
| Population vs. Sample Variance: The pizza party analogy (Situation 1: Whole population vs. Situation 2: 4 out of 5 paying friends), and losing 1 degree of freedom | `page 5` |
| Degrees of Freedom Summary Table: Sample variance, linear regression, and ANOVA, plus Confidence Intervals with $t$-distribution formula and worked example | `page 6` |
| Confidence Level vs. Alpha ($\alpha$), Two-Tailed vs. One-Tailed Tests, and finding critical $t$-values in Python (`t.ppf`) | `page 7` |
| Gosset's Resampling Experiment, Modern Relevance for Data Scientists, and Brief Comparison Summary (Empirical Rule vs. Solo CI vs. $Z$-test vs. $t$-test) | `page 8` |
| Python Code & Detailed Walkthrough: Estimating a $90\%$ CI using the $t$-distribution, and understanding cumulative probability and PPF logic | `page 9–11` |
| Why $n$ (and not $n - 1$) is Used in the Standard Error Denominator of the Margin of Error Formula (Bessel's correction vs. standard error of the mean) | `page 12` |
| Python Code & Visualizing $t$-Distribution vs. Normal Distribution: Using `stats.t.pdf` and `stats.norm.pdf`, parameter breakdowns, and shape comparisons | `page 13–15` |
| Types of $t$-Tests & Assumptions: One-sample, Independent two-sample, and Paired sample $t$-tests, along with underlying statistical assumptions | `page 16` |
| One-Sample $t$-Test: Theoretical background, formula, worked example, combined Python code (`stats.ttest_1samp`), output, and summary table for p-value syntax | `page 17–19` |
| Independent Two-Sample $t$-Test: Concepts, assumptions, formula (pooled standard deviation $s_p$), Student's $t$ vs. Welch's $t$-test, and testing variances using Levene's test (`levene`) | `page 20–22` |
| Manual Python Implementation of Independent Two-Sample $t$-Test: Code structure, calculations, and output | `page 23` |
| Paired Sample $t$-Test: Concept, use cases, hypotheses ($H_0: \mu_d = 0$), formulas, manual vs. built-in Python implementation (`stats.ttest_rel`), output, and comprehensive summary table of p-value codes | `page 24–25` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_8_student_t_distributions_and_t_test_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_8_student_t_distributions_and_t_test_watermark.pdf)

### Binomial Distribution :
| Topics Covered | Page |
| :--- | :--- |
| Binomial Distribution Core Concepts: Bernoulli trials, binomial distribution formula, calculation example, and real-world ad campaign scenario | `page 1` |
| Cumulative Probability & Key Properties Table: Calculating cumulative probabilities (`binom.cdf`) and summary of PMF, CDF, Expected Value ($np$), and Variance ($np(1-p)$) formulas | `page 2` |
| When to Use the Binomial Distribution & Normal Approximation: Core idea, requirements, and rule of thumb conditions ($np \ge 10$, $n(1-p) \ge 10$) | `page 3` |
| Normal Approximation Exercise & Continuity Correction: Converting parameters, applying $\pm 0.5$ continuity correction, $Z$-score transformation, lookup table probabilities, and skewness | `page 4` |
| Poisson Approximation to the Binomial Distribution: When to use (large $n$, small $p$, moderate $\lambda = np$), factory defect example, and exact binomial comparison | `page 5` |
| Approximation Selection Summary Table: Rule of thumb guidelines for choosing between Poisson, Normal, and Exact Binomial methods | `page 6` |
| Detailed Overview of Approximation Methods: In-depth breakdown of when to use Poisson, Normal, or Exact Binomial calculations with parameter guidelines | `page 7` |
| Python Code & PMF Breakdown: Generating and plotting the Binomial Probability Mass Function using `binom.pmf`, `np.arange`, and `plt.stem()` | `page 8` |
| Mathematical PMF vs. Array Output & CDF Python Code: Comparing single-value mathematical formulas to NumPy array outputs, and computing binomial CDF values | `page 9` |
| Approximating Binomial CDF & PMF vs. CDF Comparison: Poisson and Normal CDF approximation formulas with continuity correction, why approximations are used, and PMF vs. CDF comparison table | `page 10` |
| Python Code: Comprehensive implementation of binomial distribution approximation using Poisson and Normal distributions (`binom`, `poisson`, `norm`) with continuity correction | `page 10–11` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_9_binomial_distributions_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_9_binomial_distributions_watermark.pdf)

### Poisson Distribution: 
| Topics Covered | Page |
| :--- | :--- |
| Lambda ($\lambda$) in Poisson Distribution: Definition, key properties ($\lambda = \text{mean} = \text{variance}$), and how it shapes distribution curves (low $\lambda$ vs. high $\lambda$) | `page 1` |
| Calculating Probability: Probability Mass Function (PMF) formula and step-by-step calculation example ($\lambda = 3, k = 2$) | `page 1–2` |
| Cumulative Distribution Function (CDF): Formula, step-by-step summation for $P(X \le 2)$, and summary of PMF vs. CDF | `page 2–3` |
| Real-World Poisson Examples: Call center calls, website visits, and manufacturing quality control | `page 3` |
| Poisson-Normal Approximation ($\lambda \ge 20$): Core foundation, Central Limit Theorem convergence, mean/variance matching, and food delivery company example | `page 4` |
| Normal Approximation Calculation & Percentile Point Function (PPF): Applying continuity correction and $Z$-scores, plus introduction to the PPF (inverse CDF) | `page 5` |
| Manual Exercise & CDF/PPF Relationship: Calculating cumulative probabilities for $\lambda = 3$, finding the 95th percentile ($k = 5$), and comparing CDF vs. PPF roles | `page 5–6` |
| Poisson PMF Mathematical Concepts & Python Code: Detailed breakdown of the PMF formula, call center/website examples, and Python implementation with `poisson.pmf` and `plt.bar` | `page 7–8` |
| Poisson CDF Mathematical Concepts & Python Code: Definition, network failures example, Python implementation (`poisson.cdf`), and step-plot visualization | `page 8–9` |
| Normal Approximation to Poisson PMF and CDF: Comparing the $Z$-score method without continuity correction versus the Continuity Correction Method, with Python code and comparison table | `page 10–12` |
| Poisson Percentile Point Function (PPF) Detailed Breakdown: Mathematical definition, server request example ($\lambda = 5, p = 0.95$), manual CDF iteration up to $k = 9$, and Python implementation (`poisson.ppf`) | `page 12–13` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_10_poissondistributions_and_related_distributions.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_10_poissondistributions_and_related_distributions.pdf)

### Negative Binomial GLMs & Overdispersion:
| Topics Covered | Page |
| :--- | :--- |
| Negative Binomial GLMs & Overdispersion: Introduction, why Poisson regression fails when variance exceeds the mean, core components, random component, and Probability Mass Function (PMF) with dispersion parameter $\alpha$ and Gamma functions | `page 1` |
| Customer Complaints Worked Example & Poisson Comparison: Step-by-step PMF calculation for $y=4$ given $\mu=3$ and $\alpha=0.5$, combinatorial terms, and variance/probability comparison against a Poisson distribution | `page 2` |
| Negative Binomial GLM Systematic Component: Linear predictor ($\eta_i$), log link function, temperature vs. site visits example, and interpretation of regression coefficients | `page 3` |
| Negative Binomial Distribution vs. GLM: Similarities and structural differences comparison table (purposes, inputs, parameters, link functions) | `page 4` |
| Discrete MLE vs. GLM Comparison & Python Implementation: Feature comparison table between discrete Negative Binomial (MLE) and GLM (`Family=NegativeBinomial`), statsmodels code (`NegativeBinomial(y, x)`), and model summary breakdown | `page 5–6` |
| Data Preparation for Count Models: Combining datetime features, extracting time-based features (`hour_of_day`, `day_of_week`, `is_weekend`), and handling log-transformations with small constants ($1e-6$) | `page 7` |
| Understanding Offsets in GLMs: Shopkeeper analogy (Alice vs. Bob), adjusting for exposure/opportunity, and contrasting visitor count as a regular feature versus an offset | `page 8` |
| Fitting Negative Binomial GLM with Offsets: Creating dummy variables (`pd.get_dummies`), feature matrix setup, fitting with statsmodels GLM, robust standard errors (`cov_type='HC1'`), and extracting dispersion parameter $\alpha$ | `page 9` |
| Pearson Residuals: Definition, formula, comparison with model-based variance for Poisson vs. NB models, and interpreting standardized residuals for outlier detection | `page 10` |
| Zero-Inflated Negative Binomial (ZINB) Models: Introduction to excess zeros, dual-process model (logistic for excess zeros + NB count process), e-commerce traffic example, logit formula, coefficient interpretation, and calculating probability of excess zeros ($p_i$) | `page 11–12` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_negative_binomial.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_negative_binomial.pdf)
  

### Exponential Distribution :
| Topics Covered | Page |
| :--- | :--- |
| Exponential Distribution Core Concepts: Rate parameter ($\lambda$), mean ($1/\lambda$), variance ($1/\lambda^2$), and Probability Density Function (PDF) formula $f(x) = \lambda e^{-\lambda x}$ | `page 1` |
| PDF Example Calculations & Exercises: Evaluating PDF for $\lambda=0.2, x=3$, calculating probabilities over intervals ($P(2 \le x \le 5)$), and waiting time problems | `page 2` |
| Bus Waiting Times & Rate Comparisons: CDF formula for waiting times ($F(x) = 1 - e^{-\lambda x}$), probabilities of waiting within or beyond a threshold, and comparing PDF shapes for different rates ($\lambda=0.1$ vs $\lambda=0.3$) | `page 3` |
| Cumulative Distribution Function (CDF): Mathematical formulation, derivation from PDF by integration, key properties, and examples | `page 4` |
| CDF Calculations & Key Applications: System rate comparisons (System A vs. B), applications in service intervals, equipment failures, web traffic, and relationship with Poisson | `page 5` |
| PDF Overview & Continuous vs. Discrete: Why PDF is used instead of PMF for continuous data, and understanding probability as area under the curve | `page 6` |
| Probability Over Intervals & Density: Density context, why probabilities require integration over ranges, and integration example for $P(1 \le x \le 3)$ | `page 7` |
| Deriving the Exponential CDF from PDF: Step-by-step integration limits, why CDF uses $1 - e^{-\lambda x}$, and intuitive explanations of occurrence vs. no occurrence | `page 8` |
| Exponential PDF vs. CDF Comparison: Aspect table comparing PDF and CDF, equivalence of interval probability via PDF integration versus CDF difference ($F(b) - F(a)$), and bank customer waiting time example | `page 9` |
| Memoryless Property: Definition, mathematical proof using the survival function, intuitive explanations, and machine failure real-life example | `page 10` |
| Survival Function Overview: Definition ($S(x) = P(X > x)$), derivation from CDF, and no event occurring by time $x$ vs. surviving beyond time $x$ | `page 11` |
| Survival Function Example & Python Code: Machine failure survival probability, and Python implementation of manual and built-in exponential PDF (`expon.pdf`) | `page 12` |
| Python Code for PDF Interval Probability: Using `scipy.integrate.quad`, and detailed breakdown of function passing vs. immediate evaluation (the painter analogy) | `page 13` |
| Interval Filling & Built-in CDF Probability: Code explanation for filling intervals (`plt.fill_between`) and calculating interval probabilities using `expon.cdf` | `page 14` |
| Python Program for Exponential CDF & Memoryless Property: Manual and built-in CDF functions, and Python code verifying the memoryless property | `page 15` |
| Python Code for Survival Function: Manual vs. built-in scipy survival function (`expon.sf`) implementation | `page 16` |
| Generalized Linear Models (GLM) Real-World Analogy: Coffee shop sales example, linear predictor, link functions, Poisson distribution assumption, and statsmodels GLM syntax | `page 17` |
| Summary Evaluation Methods Table: Comprehensive comparison of methods and tests (PMF/CDF, $Z$-score, GLM Poisson, GLM Negative Binomial) across different conditions | `page 18` |
| Kolmogorov-Smirnov (KS) Test: Definition, hypothesis testing, empirical CDF (ECDF), KS test statistic ($D_n$), and step-by-step customer lifetime manual example | `page 19` |
| KS Critical Values & Python Implementation: Determining $D_{critical}$, significance levels table, and Python code for manual & built-in KS tests (`kstest`) | `page 20` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_11_exponential_distribution_watermarks.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_11_exponential_distribution_watermarks.pdf)
  
### Weibull Distribution:
| Topics Covered | Page |
| :--- | :--- |
| Weibull Distribution Core Concepts & Light Bulb Analogy: Extending the exponential distribution, lifespan analysis, shape parameter ($\beta < 1, \beta = 1, \beta > 1$), and scale parameter ($\eta$) | `page 1` |
| Why $63.2\%$ Fail by the Scale Parameter ($\eta$): Characteristic life interpretation, mathematical derivation of the Weibull CDF, and key parameters summary table | `page 2` |
| Probability Density Function (PDF): Theoretical explanation, mathematical derivation, practical bearing example, and finding the peak of the Weibull PDF ($t_{\text{peak}}$) | `page 3` |
| Cumulative Distribution Function (CDF) & Inflection Point: S-shaped CDF formula, practical exercises, inflection point definition and formula (car engine example), and median life ($q_{0.5}$) calculation | `page 4` |
| Weibull PPF Overview & Parameter Deep Dive: Breaking down the PDF formula (normalization, power, and exponential decay terms), scale parameter ("time horizon"), and shape parameter hazard functions ($h(t)$ for $\beta = 1, 2, 0.5$) | `page 5–6` |
| Interval Probability, Mean & Variance: Calculating interval probabilities via CDF/PDF integration, formulas for mean and variance using the Gamma function $\Gamma$, and a numerical worked example | `page 7–8` |
| Weibull Survival Function & Moment-Generating Function (MGF): Survival function properties, median survival time, relation to hazard function, MGF definition, first/second moments, and closed-form discussion | `page 9–13` |
| Python Implementation: Programs for Weibull PDF, interval probabilities, and peak PDF (`weibull_min` and manual calculations) | `page 14–15` |
| Python Implementation (CDF & Inflection Point): Calculating Weibull CDF and inflection points using manual functions and SciPy | `page 16` |
| Python Implementation (Survival & Median Time): Manual and built-in SciPy functions for Weibull survival functions and median survival time | `page 17` |
| Python Implementation (Mean & Variance): Calculating Weibull mean and variance using manual Gamma functions vs. built-in SciPy methods | `page 18` |

- [📄 View PDF on GitHub](https://github.com/DhawaDG/Statistics-and-Hypothesis/blob/main/stat_12_weibull_distributions_watermark.pdf)
- [⬇️ Download PDF](https://github.com/DhawaDG/Statistics-and-Hypothesis/raw/refs/heads/main/stat_12_weibull_distributions_watermark.pdf)
  

---

#### Book References

Key resources and books that guided my learning journey:

- *Practical Statistics for Data Scientists* by Peter Bruce, Andrew Bruce, and Peter Gedeck

---
## ⬅️⬅️ [Back to Main Profile](https://github.com/DhawaDG)
