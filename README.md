# Statistical Analysis
This README summarises a collection of Jupyter notebooks that demonstrate core statistical concepts, data analysis techniques, and Python programming proficiency. Each notebook combines theoretical explanations with practical Python implementations to showcase hypothesis testing, probability distributions, and data transformations. Collectively, they highlight the author’s strong statistical understanding, effective use of scientific libraries (e.g. SciPy, NumPy, pandas, scikit-learn), and ability to analyze real datasets.

## • Two-Sample t-Test Analysis: 
Notebook File:- [2_sample_t_Test.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/2_sample_t_Test.ipynb) 


--> This notebook demonstrates a two-sample t-test, which compares the means of two independent samples to determine if they differ significantly. It reviews the test’s assumptions (normality and equal variances) and performs pre-tests (Shapiro–Wilk for normality, Levene’s test for equal variance) before applying the t-test. The code uses Python’s SciPy library to compute these tests and interpret the results.


--> By walking through a complete example with clear commentary, the notebook highlights the author’s rigor in hypothesis testing and proficiency in Python for statistical analysis.


## • Binomial Distribution Exploration:
Notebook File:- [Binomial_Distribution.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/Binomial_Distribution.ipynb)


--> This notebook covers the binomial distribution, a discrete distribution modeling the number of successes in n independent Bernoulli trials with success probability p. It explains the distribution’s parameters and includes computation of the probability mass function (PMF) for example values.


--> The content likely includes Python code to calculate and plot the PMF for various n and p values, illustrating how probabilities change with these parameters. These calculations and visualizations demonstrate the author’s facility with probability concepts and coding skills in generating and interpreting statistical plots.


## • Central Limit Theorem Demonstration:
Notebook File:- [Central_Limit_Theorem.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/Central_Limit_Theorem.ipynb)


--> This notebook explains the central limit theorem (CLT), which states that the sampling distribution of the sample mean approaches a normal distribution as sample size grows. It emphasizes that this convergence occurs regardless of the original population distribution (given independent samples and finite variance).


--> Through simulation and visualizations, the notebook shows how repeated sampling leads to a bell-shaped distribution of the mean. By coding Monte Carlo experiments and plotting results, the author illustrates the CLT in practice, showcasing strong understanding of probability theory and ability to use Python for statistical simulation.

## • CLT Applied to the Titanic Dataset:
Notebook File:- [clt-titanic.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/clt-titanic.ipynb)


--> This practical notebook applies the CLT to real-world data by sampling from the Titanic passenger dataset. For example, it repeatedly samples passenger ages (or fares) to show that the distribution of the sample mean becomes approximately normal as sample size increases.


--> The analysis involves loading the dataset, performing random sampling, and visualizing the resulting distribution of sample means. This concrete example demonstrates the author’s data handling skills and the ability to connect statistical theory with real data. It highlights practical expertise in using pandas (or similar tools) and interpreting sampling distributions.


## • Covariance and Correlation Visualization:
Notebook File:- [Covariance_and_Correlation.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/Covariance_and_Correlation.ipynb)


--> This notebook conceptually explains covariance versus correlation. It notes that covariance measures how two variables vary together, while the correlation coefficient standardizes this measure to a scale between -1 and 1, capturing both direction and strength.

--> The content likely includes formulas and scatter-plot examples showing positive, negative, and zero relationships. By computing covariance and Pearson correlation on sample data and interpreting the results, the author clarifies the difference. The clear exposition and code reflect solid understanding of statistical relationships and skill in data analysis and visualization.

## • Cumulative Distribution Function from PMF:
Notebook File:- [Cumulative_Distribution_Function_of_PMF.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/Cumulative_Distribution_Function_of_PMF.ipynb)


--> This notebook demonstrates how to compute a cumulative distribution function (CDF) from a probability mass function (PMF) for a discrete random variable. In essence, it shows that the CDF at a point k is obtained by summing the PMF values up to k.

--> Likely working through an example distribution, the code accumulates PMF probabilities to construct the CDF and plots both functions. This illustrates mastery of distribution fundamentals and Python programming (using array operations or pandas) to compute and visualize probability distributions.

## • Custom Function Transformer in Pipelines:
Notebook File:- [Function_Transformer.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/Function_Transformer.ipynb)


--> This notebook shows the use of scikit-learn’s FunctionTransformer to apply custom transformations within a preprocessing pipeline. It explains that FunctionTransformer can wrap any user-defined function (e.g. log transform, custom scaling) so it integrates seamlessly into Pipeline objects.

--> By providing a concrete example, the author demonstrates creating and applying a transformer to dataset features before modeling. This showcases familiarity with machine learning workflow in Python, modular code design, and effective use of scikit-learn for data preprocessing.

## • Kernel Density Estimation (KDE) Illustration:
Notebook File:- [Kernel_Density_Estimation.ipynb](https://github.com/AmanRajput997/Statistics/blob/main/Kernel_Density_Estimation.ipynb)


--> This notebook illustrates kernel density estimation (KDE), a non-parametric method to estimate a continuous probability density function. It explains how KDE uses kernel functions to smooth sample data and produce an estimated density curve, offering a continuous analogue to histograms.

--> Through code examples, it likely compares KDE plots to histograms for sample data (e.g. using seaborn or scipy). This demonstrates the author’s understanding of advanced density estimation techniques and skill in applying Python visualization libraries to analyze data distributions.

## *-
    |
    -> Each notebook is structured with explanatory text and well-commented Python code. Together, they form a cohesive portfolio that highlights the author’s statistical kowledge, programming ability, and capacity to communicate data-driven insights.
